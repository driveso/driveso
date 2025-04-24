
  <title>Fatos Sobre Tudo</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #1a1a1a;
      color: #f5f5f5;
    }
    header, footer {
      background-color: #ff6700;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #ffa94d;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #1a1a1a;
      font-weight: bold;
    }
    .hero {
      background-image: url('URL-DA-IMAGEM-POEMAS-TECNOLOGIA'); /* Substitua por imagem real */
      background-size: cover;
      background-position: center;
      padding: 4rem 2rem;
      text-align: center;
      color: #fff;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: auto;
    }
    .hero a {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.75rem 1.5rem;
      background: #ff6700;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }
    .section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .section img {
      max-width: 100%;
      border-radius: 8px;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .feature-item {
      background: #292929;
      padding: 1rem;
      border-radius: 8px;
    }
    .feature-item h3 {
      margin-top: 0;
      color: #ffa94d;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 600px;
      margin: auto;
    }
    input, textarea {
      padding: 0.75rem;
      border-radius: 4px;
      border: none;
    }
    button {
      padding: 0.75rem;
      background-color: #ff6700;
      color: white;
      border: none;
      border-radius: 4px;
      font-weight: bold;
    }
  </style>
</head>
<body>

<header>
  <h1>Fatos Sobre Tudo</h1>
  <p>Conhecimento para todos, com a cara do Brasil</p>
</header>

<nav>
  <a href="#inicio">Início</a>
  <a href="#temas">Temas</a>
  <a href="#contato">Contato</a>
</nav>

<section class="hero" id="inicio">
  <h1>Descubra Fatos Sobre Tudo</h1>
  <p>De poemas antigos a tecnologias modernas, aqui você encontra conhecimento para todos os gostos — e com a linguagem do povo.</p>
  <a href="#temas">Explorar agora</a>
</section>

<section class="section">
  <h2>A sabedoria é de todos</h2>
  <p>Nosso conteúdo mistura o clássico com o atual, trazendo ciência, cultura e poesia em uma linguagem que todo mundo entende.</p>
  <img src="URL-DA-IMAGEM-SABEDORIA-POPULAR" alt="Sabedoria Popular">
</section>

<section class="section" id="temas">
  <h2>Nossos Temas</h2>
  <div class="features">
    <div class="feature-item">
      <h3>Poemas & Citações</h3>
      <p>Reflexões e inspirações de autores antigos e populares.</p>
    </div>
    <div class="feature-item">
      <h3>Ciência & Tecnologia</h3>
      <p>Descobertas e inovações explicadas de forma fácil e interessante.</p>
    </div>
    <div class="feature-item">
      <h3>Universo Geek/Nerd</h3>
      <p>Tudo sobre cultura pop, HQs, filmes, animes e games.</p>
    </div>
    <div class="feature-item">
      <h3>Curiosidades</h3>
      <p>Fatos surpreendentes sobre o mundo e o cotidiano.</p>
    </div>
  </div>
</section>

<section class="section" id="contato">
  <h2>Fale com a gente</h2>
  <form action="mailto:wesleyonplay@gmail.com" method="post" enctype="text/plain">
    <input type="text" name="nome" placeholder="Seu nome" required>
    <input type="email" name="email" placeholder="Seu email" required>
    <textarea name="mensagem" placeholder="Escreva sua mensagem aqui..." rows="5" required></textarea>
    <button type="submit">Enviar mensagem</button>
  </form>
</section>

<footer>
  <p>© 2025 Fatos Sobre Tudo. Todos os direitos reservados.</p>
</footer>

</body>
</html>
