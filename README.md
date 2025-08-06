<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="EMAP - Escola de Música Ministério Atos Praise. Cursos de violão, guitarra, canto e musicalização infantil em um ambiente inspirador.">
  <meta name="keywords" content="escola de música, EMAP, Ministério Atos Praise, cursos de música, musicalização infantil">
  <title>EMAP – Escola de Música Ministério Atos Praise</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="bg-primary text-white p-3 sticky-top">
    <div class="container d-flex justify-content-between align-items-center">
      <h1 class="h3 m-0">EMAP</h1>
      <nav aria-label="Navegação principal">
        <a href="#home" class="text-white me-3" aria-current="page">Home</a>
        <a href="#quem-somos" class="text-white me-3">Quem Somos</a>
        <a href="#cursos" class="text-white me-3">Cursos</a>
        <a href="#kids" class="text-white me-3">Kids</a>
        <a href="#galeria" class="text-white me-3">Galeria</a>
        <a href="#contato" class="text-white">Contato</a>
      </nav>
    </div>
  </header>

  <section id="home" class="text-white text-center py-5">
    <div class="container" data-aos="fade-up">
      <h2>Inspirar, Formar e Transformar</h2>
      <p>Bem-vindo à EMAP – Escola de Música Ministério Atos Praise</p>
      <a href="#contato" class="btn btn-primary mt-3">Entre em Contato</a>
    </div>
  </section>

  <section id="quem-somos" class="py-5" data-aos="fade-right">
    <div class="container">
      <h2>Quem Somos</h2>
      <p>Somos uma escola nova, mas com professores especializados em suas áreas de atuação, comprometidos em inspirar e transformar vidas através da música.</p>
    </div>
  </section>

  <section id="cursos" class="py-5 bg-light" data-aos="fade-left">
    <div class="container">
      <h2>Cursos Oferecidos</h2>
      <ul class="list-unstyled row">
        <li class="col-md-4 mb-2">Violão</li>
        <li class="col-md-4 mb-2">Guitarra</li>
        <li class="col-md-4 mb-2">Teclado</li>
        <li class="col-md-4 mb-2">Canto</li>
        <li class="col-md-4 mb-2">Musicalização Infantil</li>
        <li class="col-md-4 mb-2">Baixo</li>
        <li class="col-md-4 mb-2">Bateria</li>
      </ul>
      <a href="#contato" class="btn btn-primary mt-3">Inscreva-se Agora</a>
    </div>
  </section>

  <section id="kids" class="py-5" data-aos="fade-up">
    <div class="container">
      <h2>Musicalização Infantil (Kids)</h2>
      <p>Abordagem lúdica e criativa para as crianças com paleta especial, desenvolvendo habilidades musicais de forma divertida.</p>
      <a href="#contato" class="btn btn-primary mt-3">Saiba Mais</a>
    </div>
  </section>

  <section id="galeria" class="py-5 bg-light" data-aos="zoom-in">
    <div class="container">
      <h2>Galeria</h2>
      <div class="row">
        <div class="col-md-4 mb-3">
          <img src="https://via.placeholder.com/300x200?text=Aula+de+Violão" class="img-fluid rounded" alt="Aula de violão na EMAP">
        </div>
        <div class="col-md-4 mb-3">
          <img src="https://via.placeholder.com/300x200?text=Musicalização+Infantil" class="img-fluid rounded" alt="Musicalização infantil na EMAP">
        </div>
        <div class="col-md-4 mb-3">
          <img src="https://via.placeholder.com/300x200?text=Evento+EMAP" class="img-fluid rounded" alt="Evento musical da EMAP">
        </div>
      </div>
    </div>
  </section>

  <section id="contato" class="py-5" data-aos="flip-up">
    <div class="container">
      <h2>Contato</h2>
      <form action="https://formspree.io/f/moqgqqdn" method="POST" id="contact-form">
        <div class="mb-3">
          <input type="text" class="form-control" name="nome" placeholder="Nome" required>
        </div>
        <div class="mb-3">
          <input type="email" class="form-control" name="email" placeholder="E-mail" required>
        </div>
        <div class="mb-3">
          <textarea class="form-control" name="message" rows="4" placeholder="Mensagem" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Enviar</button>
      </form>
      <p class="mt-3">Siga-nos no Instagram: <a href="https://instagram.com/ematospraise" target="_blank" class="text-warning">@ematospraise</a></p>
    </div>
  </section>

  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 EMAP – Todos os direitos reservados</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
  <script>window.bootstrap || document.write('<script src="js/bootstrap.bundle.min.js"><\/script>');</script>
  <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init();
    // Smooth scroll para links de navegação
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
    // Feedback do formulário
    document.getElementById('contact-form').addEventListener('submit', function() {
      alert('Mensagem enviada com sucesso!');
    });
  </script>
</body>
</html>