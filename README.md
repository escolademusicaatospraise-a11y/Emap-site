# <!DOCTYPE html>
<html lang="pt-br">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Escola de Música Ministério Atos Praise</title>
   <style>
       * {
           margin: 0;
           padding: 0;
           box-sizing: border-box;
           font-family: 'Arial', sans-serif;
       }

       body {
           background-color: #f0f0f0;
           color: #010658;
       }

       /* Header */
       header {
           background-color: #010658;
           color: white;
           padding: 1rem;
           position: fixed;
           width: 100%;
           top: 0;
           z-index: 1000;
       }

       nav {
           display: flex;
           justify-content: space-between;
           align-items: center;
           max-width: 1200px;
           margin: 0 auto;
       }

       .logo-placeholder {
           font-size: 1.5rem;
           font-weight: bold;
       }

       nav ul {
           list-style: none;
           display: flex;
           gap: 1.5rem;
       }

       nav a {
           color: white;
           text-decoration: none;
           font-weight: bold;
           transition: color 0.3s;
       }

       nav a:hover {
           color: #ffb246;
       }

       /* Hero Section */
       .hero {
           background: linear-gradient(135deg, #5a199c, #010658);
           color: white;
           text-align: center;
           padding: 5rem 1rem;
           margin-top: 80px;
       }

       .hero h1 {
           font-size: 2.5rem;
           margin-bottom: 1rem;
       }

       .hero p {
           font-size: 1.2rem;
           margin-bottom: 2rem;
       }

       .cta-button {
           background-color: #d80816;
           color: white;
           padding: 0.8rem 2rem;
           border: none;
           border-radius: 5px;
           font-size: 1rem;
           cursor: pointer;
           transition: background-color 0.3s;
       }

       .cta-button:hover {
           background-color: #ffb246;
       }

       /* Sections */
       section {
           padding: 3rem 1rem;
           max-width: 1200px;
           margin: 0 auto;
       }

       h2 {
           color: #5a199c;
           text-align: center;
           margin-bottom: 2rem;
       }

       /* Cursos */
       .courses-grid {
           display: grid;
           grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
           gap: 1.5rem;
       }

       .course-card {
           background-color: white;
           border-radius: 10px;
           box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
           padding: 1.5rem;
           text-align: center;
           transition: transform 0.3s;
       }

       .course-card:hover {
           transform: translateY(-5px);
       }

       .course-card h3 {
           color: #d80816;
           margin-bottom: 1rem;
       }

       /* Contato */
       .contact-form {
           max-width: 600px;
           margin: 0 auto;
           display: flex;
           flex-direction: column;
           gap: 1rem;
       }

       .contact-form input, .contact-form textarea {
           padding: 0.8rem;
           border: 2px solid #010658;
           border-radius: 5px;
           font-size: 1rem;
       }

       .contact-form button {
           background-color: #5a199c;
           color: white;
           padding: 0.8rem;
           border: none;
           border-radius: 5px;
           cursor: pointer;
           transition: background-color 0.3s;
       }

       .contact-form button:hover {
           background-color: #d80816;
       }

       /* Footer */
       footer {
           background-color: #010658;
           color: white;
           text-align: center;
           padding: 1rem;
       }

       footer a {
           color: #ffb246;
           text-decoration: none;
       }

       footer a:hover {
           text-decoration: underline;
       }

       /* Responsividade */
       @media (max-width: 768px) {
           .hero h1 {
               font-size: 1.8rem;
           }

           nav ul {
               flex-direction: column;
               gap: 1rem;
           }
       }
   </style>
</head>
<body>
   <!-- Header -->
   <header>
       <nav>
           <div class="logo-placeholder">EMAP (Logo Placeholder)</div>
           <ul>
               <li><a href="#home">Home</a></li>
               <li><a href="#sobre">Sobre</a></li>
               <li><a href="#cursos">Cursos</a></li>
               <li><a href="#eventos">Eventos</a></li>
               <li><a href="#contato">Contato</a></li>
           </ul>
       </nav>
   </header>

   <!-- Hero Section -->
   <section id="home" class="hero">
       <h1>Escola de Música Ministério Atos Praise</h1>
       <p>Inspirar, Formar e Transformar através da música</p>
       <button class="cta-button">Conheça nossos cursos</button>
   </section>

   <!-- Sobre -->
   <section id="sobre">
       <h2>Sobre a EMAP</h2>
       <p>Nossa missão é <strong>Inspirar, Formar e Transformar</strong> vidas por meio da música. A Escola de Música Ministério Atos Praise é um espaço dedicado ao ensino musical com professores especializados, comprometidos em oferecer uma experiência única e transformadora.</p>
   </section>

   <!-- Cursos -->
   <section id="cursos">
       <h2>Nossos Cursos</h2>
       <div class="courses-grid">
           <div class="course-card">
               <h3>Violão</h3>
               <p>Aprenda técnicas de violão com professores experientes.</p>
           </div>
           <div class="course-card">
               <h3>Guitarra</h3>
               <p>Domine riffs e solos com aulas práticas e dinâmicas.</p>
           </div>
           <div class="course-card">
               <h3>Teclado</h3>
               <p>Explore harmonias e melodias no teclado.</p>
           </div>
           <div class="course-card">
               <h3>Canto</h3>
               <p>Desenvolva sua voz com técnicas de canto profissional.</p>
           </div>
           <div class="course-card">
               <h3>Musicalização Infantil</h3>
               <p>Introdução à música para crianças de forma lúdica.</p>
           </div>
           <div class="course-card">
               <h3>Baixo</h3>
               <p>Aprenda a criar grooves incríveis no baixo.</p>
           </div>
           <div class="course-card">
               <h3>Bateria</h3>
               <p>Desenvolva ritmo e coordenação com aulas de bateria.</p>
           </div>
       </div>
   </section>

   <!-- Eventos -->
   <section id="eventos">
       <h2>Eventos e Apresentações</h2>
       <p>A EMAP é uma escola nova, mas conta com professores altamente especializados, prontos para formar músicos de excelência. Fique ligado para nossas futuras apresentações e eventos!</p>
   </section>

   <!-- Contato -->
   <section id="contato">
       <h2>Entre em Contato</h2>
       <form class="contact-form">
           <input type="text" placeholder="Nome" required>
           <input type="email" placeholder="E-mail" required>
           <textarea placeholder="Mensagem" rows="5" required></textarea>
           <button type="submit">Enviar</button>
       </form>
       <p style="text-align: center; margin-top: 1rem;">
           Siga-nos no <a href="https://instagram.com/ematospraise" target="_blank">Instagram: @ematospraise</a>
       </p>
   </section>

   <!-- Footer -->
   <footer>
       <p>&copy; 2025 Escola de Música Ministério Atos Praise. Todos os direitos reservados.</p>
       <p><a href="https://instagram.com/ematospraise" target="_blank">Instagram: @ematospraise</a></p>
   </footer>

   <script>
       // JavaScript para suavizar a rolagem ao clicar nos links do menu
       document.querySelectorAll('nav a').forEach(anchor => {
           anchor.addEventListener('click', function (e) {
               e.preventDefault();
               const sectionId = this.getAttribute('href');
               document.querySelector(sectionId).scrollIntoView({ behavior: 'smooth' });
           });
       });

       // Placeholder para o formulário (exemplo de funcionalidade)
       document.querySelector('.contact-form').addEventListener('submit', function (e) {
           e.preventDefault();
           alert('Mensagem enviada! Entraremos em contato em breve.');
           this.reset();
       });
   </script>
</body>
</html>