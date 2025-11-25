<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfólio — Kauã Peixoto</title>
  <link rel="stylesheet" href="css/style.css" />
  <link rel="icon" href="img/favicon.png" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <h1 class="logo"><a href="index.html">Kauã Peixoto</a></h1>
      <nav class="main-nav">
        <a href="index.html">Home</a>
        <a href="about.html">Sobre</a>
        <a href="projects.html">Projetos</a>
        <a href="contact.html">Contato</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <h2>Olá — eu sou Kauã Peixoto</h2>
      <p>Desenvolvedor Web | Projeto demonstrativo para P2.</p>
      <p><a class="btn" href="projects.html">Ver projetos</a></p>
    </section>

    <section class="cards">
      <article class="card">
        <h3>Habilidades</h3>
        <ul>
          <li>HTML semântico</li>
          <li>CSS (Flexbox e Grid)</li>
          <li>JavaScript básico</li>
        </ul>
      </article>

      <article class="card">
        <h3>Sobre o MyRefuge</h3>
        <p>Projeto MyRefuge — plataforma de apoio emocional com foco em saúde mental.</p>
      </article>

      <article class="card">
        <h3>Contato rápido</h3>
        <p>E-mail: seuemail@exemplo.com</p>
      </article>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>Portfólio de Kauã Peixoto</p>
    </div>
  </footer>
</body>
</html>
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sobre — Kauã Peixoto</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

<header class="site-header">
  <div class="container header-inner">
    <h1 class="logo"><a href="index.html">Kauã Peixoto</a></h1>
    <nav class="main-nav">
      <a href="index.html">Home</a>
      <a href="about.html">Sobre</a>
      <a href="projects.html">Projetos</a>
      <a href="contact.html">Contato</a>
    </nav>
  </div>
</header>

<main class="container">
  <h2>Sobre mim</h2>
  <p>Meu nome é <strong>Kauã Peixoto</strong>. Sou estudante de Desenvolvimento Web e este portfólio faz parte da avaliação P2.</p>

  <h3>Objetivos</h3>
  <ul>
    <li>Desenvolver habilidades em HTML e CSS</li>
    <li>Aplicar responsividade</li>
    <li>Melhorar organização de projetos</li>
  </ul>
</main>

<footer class="site-footer">
  <div class="container">
    <p><a href="index.html">Voltar</a></p>
  </div>
</footer>

</body>
</html>
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Projetos — Kauã Peixoto</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

<header class="site-header">
  <div class="container header-inner">
    <h1 class="logo"><a href="index.html">Kauã Peixoto</a></h1>
    <nav class="main-nav">
      <a href="index.html">Home</a>
      <a href="about.html">Sobre</a>
      <a href="projects.html">Projetos</a>
      <a href="contact.html">Contato</a>
    </nav>
  </div>
</header>

<main class="container">
  <h2>Projetos</h2>

  <section class="project-list">
    <article class="project">
      <h3>MyRefuge</h3>
      <p>Plataforma digital de apoio emocional com funcionalidades como diário de emoções, fóruns e conteúdo educativo.</p>
    </article>

    <article class="project">
      <h3>Projeto X (exemplo)</h3>
      <p>Descrição breve do Projeto X.</p>
    </article>
  </section>
</main>

<footer class="site-footer">
  <div class="container">
    <p><a href="index.html">Voltar</a></p>
  </div>
</footer>

</body>
</html>
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Contato — Kauã Peixoto</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

<header class="site-header">
  <div class="container header-inner">
    <h1 class="logo"><a href="index.html">Kauã Peixoto</a></h1>
    <nav class="main-nav">
      <a href="index.html">Home</a>
      <a href="about.html">Sobre</a>
      <a href="projects.html">Projetos</a>
      <a href="contact.html">Contato</a>
    </nav>
  </div>
</header>

<main class="container">
  <h2>Fale comigo</h2>

  <form id="contactForm" onsubmit="handleSubmit(event)">
    <label>Nome</label>
    <input type="text" id="name" required>

    <label>E-mail</label>
    <input type="email" id="email" required>

    <label>Mensagem</label>
    <textarea id="message" rows="5" required></textarea>

    <button class="btn" type="submit">Enviar</button>
  </form>
</main>

<footer class="site-footer">
  <div class="container">
    <p><a href="index.html">Voltar</a></p>
  </div>
</footer>

<script src="js/main.js"></script>
</body>
</html>
:root{--max-width:1100px;--accent:#2b7cff;--bg:#f7f9fc}
*{box-sizing:border-box}
body{font-family:Arial,Helvetica,sans-serif;margin:0;color:#222;background:var(--bg)}
.container{max-width:var(--max-width);margin:0 auto;padding:1rem}
.site-header{background:#fff;border-bottom:1px solid #e6eef9}
.header-inner{display:flex;align-items:center;justify-content:space-between}
.logo a{text-decoration:none;color:#000;font-weight:bold;font-size:1.2rem}
.main-nav a{margin-left:1rem;text-decoration:none;color:#333}
.hero{background:#fff;padding:2rem;border-radius:8px;margin-top:1rem}
.btn{background:#2b7cff;color:#fff;padding:.6rem 1rem;border-radius:8px;text-decoration:none}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:1rem;margin-top:1rem}
.card{background:#fff;padding:1rem;border-radius:8px}
.site-footer{text-align:center;padding:1rem;color:#555;margin-top:2rem}
form label{display:block;margin-top:.7rem}
input,textarea{width:100%;padding:.5rem;margin-top:.3rem;border:1px solid #ccc;border-radius:6px}
:root{--max-width:1100px;--accent:#2b7cff;--bg:#f7f9fc}
*{box-sizing:border-box}
body{font-family:Arial,Helvetica,sans-serif;margin:0;color:#222;background:var(--bg)}
.container{max-width:var(--max-width);margin:0 auto;padding:1rem}
.site-header{background:#fff;border-bottom:1px solid #e6eef9}
.header-inner{display:flex;align-items:center;justify-content:space-between}
.logo a{text-decoration:none;color:#000;font-weight:bold;font-size:1.2rem}
.main-nav a{margin-left:1rem;text-decoration:none;color:#333}
.hero{background:#fff;padding:2rem;border-radius:8px;margin-top:1rem}
.btn{background:#2b7cff;color:#fff;padding:.6rem 1rem;border-radius:8px;text-decoration:none}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:1rem;margin-top:1rem}
.card{background:#fff;padding:1rem;border-radius:8px}
.site-footer{text-align:center;padding:1rem;color:#555;margin-top:2rem}
form label{display:block;margin-top:.7rem}
input,textarea{width:100%;padding:.5rem;margin-top:.3rem;border:1px solid #ccc;border-radius:6px}
