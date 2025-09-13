<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Renato Rodrigues da Silva — Educador Social</title>
  <style>
    :root {
      --primary: #003366;
      --secondary: #0066cc;
      --light: #f4f6f9;
      --dark: #222;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: var(--light);
      color: var(--dark);
      line-height: 1.6;
    }
    header {
      background: var(--primary);
      color: white;
      text-align: center;
      padding: 4rem 1rem 3rem;
    }
    header img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 5px solid white;
      margin-bottom: 1rem;
      object-fit: cover;
    }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.2rem; margin-top: .5rem; }
    nav {
      background: white;
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      gap: 2rem;
    }
    nav a {
      color: var(--primary);
      font-weight: bold;
      text-decoration: none;
      transition: color .3s;
    }
    nav a:hover { color: var(--secondary); }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 2rem;
    }
    section { margin-bottom: 3rem; }
    h2 { color: var(--primary); margin-bottom: 1rem; font-size: 1.8rem; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform .3s;
    }
    .card:hover { transform: translateY(-5px); }
    .project-images {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 1rem;
    }
    .project-images img {
      width: 100%;
      max-width: 300px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .contact { text-align: center; margin-top: 2rem; }
    .btn {
      display: inline-block;
      background: var(--secondary);
      color: white;
      padding: 0.75rem 1.5rem;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: background .3s;
    }
    .btn:hover { background: #004c99; }
    footer {
      text-align: center;
      padding: 2rem;
      background: var(--primary);
      color: white;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header id="home">
    <img src="1000090043.jpg" alt="Foto de Renato Rodrigues da Silva">
    <h1>Renato Rodrigues da Silva</h1>
    <p>Educador Social | Projetos de Inclusão e Acolhimento</p>
  </header>

  <nav>
    <ul>
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#competencias">Competências</a></li>
      <li><a href="#projeto">Projeto</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
  </nav>

  <div class="container">
    <section id="sobre">
      <h2>Sobre Mim</h2>
      <p>
        Sou <strong>Renato Rodrigues da Silva</strong>, Educador Social com experiência em projetos de acolhimento, inclusão e intervenção comunitária. 
        Atuo com foco na promoção da autonomia, desenvolvimento socioemocional e inclusão de crianças e adolescentes, especialmente em contextos de vulnerabilidade social.
      </p>
    </section>

    <section id="competencias">
      <h2>Competências</h2>
      <div class="grid">
        <div class="card">
          <ul>
            <li>Planejamento e execução de atividades socioeducativas</li>
            <li>Desenvolvimento de projetos de inclusão e acessibilidade</li>
            <li>Mediação de conflitos e escuta ativa</li>
            <li>Trabalho em equipe multiprofissional</li>
            <li>Adaptação de atividades para diferentes perfis sensoriais</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="projeto">
      <h2>Projeto: Inclusão Sensorial — Espaços que Acolhem</h2>
      <div class="card">
        <p>
          Projeto de criação de ambientes e atividades sensoriais adaptadas para alunos com Transtorno do Espectro Autista (TEA), 
          promovendo participação ativa, autorregulação e bem-estar.
        </p>
        <div class="project-images">
          <img src="1000116938.png" alt="Projeto Sensorial de Inclusão">
          <img src="1000116937.png" alt="Campanha Autismo e Paternidade">
        </div>
      </div>
    </section>

    <section>
      <h2>Resultados Esperados</h2>
      <div class="grid">
        <div class="card">
          <ul>
            <li>Aumento da participação nas atividades coletivas</li>
            <li>Redução de crises relacionadas à sobrecarga sensorial</li>
            <li>Melhora na autorregulação e no foco</li>
            <li>Empoderamento de familiares e professores</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="contato" class="contact">
      <h2>Entre em Contato</h2>
      <p>📧 <a href="mailto:dasilvarodrigues413@gmail.com">dasilvarodrigues413@gmail.com</a></p>
      <p>📞 (51) 99766-2723</p>
      <a href="mailto:dasilvarodrigues413@gmail.com" class="btn">Fale Comigo</a>
    </section>
  </div>

  <footer>
    <p>© 2025 Renato Rodrigues da Silva — Todos os direitos reservados.</p>
  </footer>
</body>
</html>


