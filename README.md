Daniela Medeiros


Meu site pessoal


<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Sobre Mim - Daniela Medeiros</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav>
    <a href="index.html">Sobre Mim</a>
    <a href="formacao.html">Formação</a>
    <a href="portfolio.html">Portfólio</a>
    <a href="contato.html">Contato</a>
  </nav>

  <div class="container">
    <h1>Sobre Mim</h1>
    <p>Olá! Meu nome é Daniela Medeiros. Sou uma pessoa apaixonada por tecnologia, aprendizado e desafios.</p>
    <p>No meu tempo livre, gosto de assistir filmes e explorar coisas novas na internet. Tenho dois filhos: Pietro (3 anos) e Sophia (9 meses).</p>
    <p>Estou cursando Análise e Desenvolvimento de Sistemas e este site é parte do meu aprendizado. Seja bem-vindo(a)!</p>
  </div>

</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Formação - Daniela Medeiros</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav>
    <a href="index.html">Sobre Mim</a>
    <a href="formacao.html">Formação</a>
    <a href="portfolio.html">Portfólio</a>
    <a href="contato.html">Contato</a>
  </nav>

  <div class="container">
    <h1>Formação Educacional</h1>
    <p>Atualmente estou cursando Análise e Desenvolvimento de Sistemas na Uninter.</p>
    <p>Tenho interesse nas áreas de desenvolvimento web, design e tecnologia em geral.</p>

    <h2>Idiomas</h2>
    <ul>
      <li>Português: Nativo</li>
      <li>Inglês: Básico</li>
      <li>Espanhol: Básico</li>
    </ul>
  </div>

</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Portfólio - Daniela Medeiros</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav>
    <a href="index.html">Sobre Mim</a>
    <a href="formacao.html">Formação</a>
    <a href="portfolio.html">Portfólio</a>
    <a href="contato.html">Contato</a>
  </nav>

  <div class="container">
    <h1>Meu Portfólio</h1>
    <h2>Projeto 2</h2>
    <img src="projeto2.png" alt="Projeto 2" width="300">
    <p>Este foi um exercício prático da faculdade para criar quadrados coloridos com texto nos cantos da tela.</p>
  </div>

</body>
</html>


<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Contato - Daniela Medeiros</title>
  <link rel="stylesheet" href="style.css">
  <style>
    .social-buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .social-buttons a img {
      width: 40px;
      height: 40px;
      transition: transform 0.2s;
    }

    .social-buttons a:hover img {
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <nav>
    <a href="index.html">Sobre Mim</a>
    <a href="formacao.html">Formação</a>
    <a href="portfolio.html">Portfólio</a>
    <a href="contato.html">Contato</a>
  </nav>

  <div class="container">
    <h1>Fale Comigo</h1>

    <form>
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="email" name="email" placeholder="Seu email" required>
      <textarea name="mensagem" rows="5" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>

    <div class="social-buttons">
      <a href="https://wa.me/5531973100854" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
      </a>
      <a href="https://www.linkedin.com/in/ddaniela-medeiros/" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" alt="LinkedIn">
      </a>
      <a href="mailto:dddani95@hotmail.com.br">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email">
      </a>
    </div>
  </div>

</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f5f5f5;
  color: #333;
}

nav {
  background-color: #3f51b5;
  padding: 15px;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.container {
  padding: 100px 20px 40px;
  max-width: 800px;
  margin: auto;
}

form {
  display: flex;
  flex-direction: column;
}

input, textarea {
  margin-bottom: 15px;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  background-color: #3f51b5;
  color: white;
  padding: 10px;
  border: none;
  cursor: pointer;
  border-radius: 4px;
}

button:hover {
  background-color: #303f9f;
}


