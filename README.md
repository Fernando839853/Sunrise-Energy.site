<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sunrise Energy</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: #f0fdf4;
      color: #1b1b1b;
    }
    header {
      background: linear-gradient(90deg, #00c853, #64dd17);
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 60px;
    }
    nav {
      background: #388e3c;
      text-align: center;
    }
    nav a {
      display: inline-block;
      color: white;
      padding: 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      background: #2e7d32;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #2e7d32;
    }
    .valores {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .valor {
      flex: 1 1 200px;
      background: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin-top: 20px;
    }
    input, textarea, button {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 1rem;
    }
    button {
      background-color: #43a047;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #388e3c;
    }
    footer {
      background: #1b5e20;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      margin-top: 20px;
    }
    .gallery img {
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.imgur.com/3oGMG7v.png" alt="Logo Sunrise Energy" />
    <h1>Sunrise Energy</h1>
    <p>Iluminando o futuro com energia solar</p>
  </header>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#missao">Missão</a>
    <a href="#valores">Valores</a>
    <a href="#galeria">Galeria</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre">
    <h2>Sobre a Empresa</h2>
    <p>A Sunrise Energy foi fundada em 2010, em Tóquio – Japão, pela união de Técnicos de Sistemas de Energias Renováveis. Hoje somos líderes em energia solar fotovoltaica, com atuação global. Nosso foco está na sustentabilidade, inovação e autonomia energética.</p>
  </section>

  <section id="missao">
    <h2>Missão e Visão</h2>
    <p><strong>Missão:</strong> Democratizar o acesso à energia solar com soluções inovadoras, acessíveis e sustentáveis.</p>
    <p><strong>Visão:</strong> Ser referência global em energia renovável, com impacto positivo no planeta e reconhecimento pela excelência.</p>
  </section>

  <section id="valores">
    <h2>Valores Fundamentais</h2>
    <div class="valores">
      <div class="valor">
        <h3>Sustentabilidade</h3>
        <p>Comprometimento com o meio ambiente e práticas que minimizem impactos ecológicos.</p>
      </div>
      <div class="valor">
        <h3>Inovação</h3>
        <p>Atualização constante com as melhores tecnologias e soluções do mercado.</p>
      </div>
      <div class="valor">
        <h3>Excelência</h3>
        <p>Entrega de projetos com alto padrão de qualidade, superando expectativas.</p>
      </div>
      <div class="valor">
        <h3>Transparência</h3>
        <p>Relacionamento ético e aberto com clientes, parceiros e colaboradores.</p>
      </div>
      <div class="valor">
        <h3>Responsabilidade Social</h3>
        <p>Atuação pelo bem-estar coletivo e acesso à energia limpa para todos.</p>
      </div>
    </div>
  </section>

  <section id="galeria">
    <h2>Galeria de Projetos</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1606149051153-8fd68f7cc637" alt="Painel solar 1" />
      <img src="https://images.unsplash.com/photo-1584270354949-8cd68ec38fb7" alt="Painel solar 2" />
      <img src="https://images.unsplash.com/photo-1615800008263-287a6f6e2e2f" alt="Painel solar 3" />
    </div>
  </section>

  <section id="contato">
    <h2>Fale Conosco</h2>
    <form>
      <input type="text" name="nome" placeholder="Seu nome" required />
      <input type="email" name="email" placeholder="Seu e-mail" required />
      <textarea name="mensagem" rows="5" placeholder="Sua mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Sunrise Energy. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
