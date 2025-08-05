# Emap-site
Portfólio da Escola de Música Ministério Atos Praise
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EMAP - Escola de Música Ministério Atos Praise</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>EMAP</h1>
    <p>Escola de Música Ministério Atos Praise</p>
    <nav>
      <ul>
        <li><a href="#quem-somos">Quem Somos</a></li>
        <li><a href="#cursos">Cursos</a></li>
        <li><a href="#portfolio">Portfólio</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="quem-somos">
    <h2>Missão</h2>
    <p>Inspirar, formar e transformar por meio da música e da adoração.</p>
    <p>A EMAP é uma escola de música cristã que visa capacitar músicos com excelência técnica e propósito espiritual. Apesar de nova, conta com professores especializados e apaixonados pelo ensino musical.</p>
  </section>

  <section id="cursos">
    <h2>Cursos Oferecidos</h2>
    <ul>
      <li>Violão</li>
      <li>Guitarra</li>
      <li>Teclado</li>
      <li>Canto</li>
      <li>Musicalização Infantil</li>
      <li>Baixo</li>
      <li>Bateria</li>
    </ul>
  </section>

  <section id="portfolio">
    <h2>Portfólio</h2>
    <p>Em breve: registros dos nossos alunos, professores e eventos!</p>
    <p>Estamos preparando um ensaio fotográfico especial para apresentar nossa escola e equipe.</p>
    <img src="imagens/evento1.jpg" alt="Evento musical" width="300">
    <img src="imagens/aula1.jpg" alt="Aula de música" width="300">
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <form action="https://formspree.io/f/mnqekgwp" method="POST">
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="email" name="email" placeholder="Seu e-mail" required>
      <textarea name="mensagem" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>Siga-nos nas redes sociais:</p>
    <a href="https://instagram.com/ematospraise" target="_blank">@ematospraise</a>
    <p>&copy; 2025 EMAP - Todos os direitos reservados.</p>
  </footer>
</body>
</html>
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background: #f5f5f5;
  color: #333;
}

header {
  background: #010658;
  color: white;
  text-align: center;
  padding: 30px 20px;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 40px 20px;
  background: white;
  margin-bottom: 20px;
}

section h2 {
  color: #5a199c;
}

ul {
  list-style: disc;
  padding-left: 20px;
}

form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
  margin: auto;
}

form input, form textarea {
  margin-bottom: 15px;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
}

form button {
  background: #d80816;
  color: white;
  padding: 10px;
  border: none;
  cursor: pointer;
  transition: 0.3s;
}

form button:hover {
  background: #ffb246;
  color: #010658;
}

footer {
  background: #eee;
  text-align: center;
  padding: 20px;
}