<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tsiky Rivoherison – Portfolio</title>
  <meta name="description" content="Portfolio de Tsiky Rivoherison – Ingénieur informatique CY Tech" />

  <!-- Google Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #001f3f;
      --bg-dark: #000814;
      --gold: #d4af37;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --card: rgba(0,0,0,0.35);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(180deg, var(--bg-dark), var(--bg));
      color: var(--text);
      line-height: 1.6;
    }

    a { color: inherit; text-decoration: none; }

    section { padding: 5rem 1.5rem; }

    .container { max-width: 1100px; margin: auto; }

    /* HERO */
    header {
      padding: 8rem 1.5rem 6rem;
      text-align: center;
      background: radial-gradient(circle at top, rgba(212,175,55,0.15), transparent 60%);
      border-bottom: 1px solid rgba(212,175,55,0.2);
    }

    h1 {
      font-size: clamp(2.5rem, 5vw, 4rem);
      font-weight: 800;
      color: var(--gold);
    }

    header p.role {
      font-size: 1.5rem;
      font-weight: 300;
      color: #d1d5db;
      margin-top: 1rem;
    }

    header p.quote {
      margin-top: 1rem;
      font-style: italic;
      color: rgba(212,175,55,0.8);
    }

    .socials {
      margin-top: 2.5rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    .socials a {
      font-weight: 600;
      border-bottom: 1px solid transparent;
      transition: 0.3s;
    }

    .socials a:hover {
      color: var(--gold);
      border-color: var(--gold);
    }

    /* TITLES */
    h2 {
      font-size: 2.5rem;
      text-align: center;
      margin-bottom: 4rem;
      font-weight: 700;
    }

    h2 span {
      color: var(--gold);
      font-style: italic;
    }

    /* CARDS */
    .grid {
      display: grid;
      gap: 2rem;
    }

    .grid-3 { grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }
    .grid-2 { grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); }

    .card {
      background: var(--card);
      padding: 2rem;
      border-radius: 1.25rem;
      border: 1px solid rgba(255,255,255,0.05);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: var(--gold);
    }

    .card h3 {
      color: var(--gold);
      margin-bottom: 1rem;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 1rem;
    }

    .tag {
      font-size: 0.65rem;
      padding: 0.3rem 0.6rem;
      border-radius: 999px;
      background: rgba(255,255,255,0.08);
      color: #d1d5db;
      text-transform: uppercase;
      letter-spacing: 0.08em;
    }

    /* TIMELINE */
    .timeline {
      max-width: 800px;
      margin: auto;
      border-left: 2px solid rgba(212,175,55,0.3);
      padding-left: 2rem;
    }

    .job {
      margin-bottom: 3rem;
      position: relative;
    }

    .job::before {
      content: '';
      position: absolute;
      left: -2.65rem;
      top: 0.3rem;
      width: 14px;
      height: 14px;
      background: var(--gold);
      border-radius: 50%;
      box-shadow: 0 0 12px var(--gold);
    }

    .job h3 { font-size: 1.4rem; }

    .job span {
      font-family: monospace;
      color: var(--gold);
      font-size: 0.9rem;
    }

    .job p { margin-top: 0.5rem; color: #d1d5db; }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 4rem 1.5rem;
      border-top: 1px solid rgba(255,255,255,0.05);
      color: var(--muted);
    }

    footer small {
      display: block;
      margin-top: 1rem;
      font-size: 0.65rem;
      letter-spacing: 0.25em;
      text-transform: uppercase;
    }
  </style>
</head>
<body>

<header>
  <h1>Tsiky Rivoherison</h1>
  <p class="role">Ingénieur CY Tech – Spécialité Informatique</p>
  <p class="quote">« Transformer chaque défi technique en une réussite humaine. »</p>

  <div class="socials">
    <a href="https://www.linkedin.com/in/tsiky-rivoherison/" target="_blank">LinkedIn</a>
    <a href="mailto:tsikyrivoherison94@hotmail.fr">Email</a>
  </div>
</header>

<section class="container">
  <h2><span>Compétences</span> Techniques</h2>
  <div class="grid grid-3">
    <div class="card">
      <h3>Langages</h3>
      <p>Python, Java, C, C#, PHP, SQL, JavaScript</p>
    </div>
    <div class="card">
      <h3>Frameworks & Tools</h3>
      <p>React, Django, Unity, Docker, GitFlow, CI/CD</p>
    </div>
    <div class="card">
      <h3>Systèmes</h3>
      <p>Linux (Debian, Ubuntu), Windows, VMware</p>
    </div>
  </div>
</section>

<section class="container">
  <h2><span>Portfolio</span> de Projets</h2>
  <div class="grid grid-3">

    <div class="card">
      <h3>Optimisation Flotte – Java</h3>
      <p>Collecte de données camions via prise OBD‑2, transmission Wi‑Fi et traitement applicatif en autonomie complète.</p>
      <div class="tags"><span class="tag">Java</span><span class="tag">OBD‑2</span><span class="tag">Wi‑Fi</span></div>
    </div>

    <div class="card">
      <h3>E‑Commerce Artisan</h3>
      <p>Site e‑commerce complet avec base de données et documentation technique détaillée (~100 pages).</p>
      <div class="tags"><span class="tag">PHP</span><span class="tag">MySQL</span><span class="tag">jQuery</span></div>
    </div>

    <div class="card">
      <h3>Bracelet Connecté</h3>
      <p>Bracelet d'urgence avec application mobile, électronique embarquée et programmation Arduino.</p>
      <div class="tags"><span class="tag">Arduino</span><span class="tag">Mobile</span></div>
    </div>

    <div class="card">
      <h3>RPG Python – Engine</h3>
      <p>Moteur de jeu POO avancé, contrôlable depuis une interface mobile via Flask & Socket.IO.</p>
      <div class="tags"><span class="tag">Python</span><span class="tag">Flask</span><span class="tag">Socket.IO</span></div>
    </div>

    <div class="card">
      <h3>Jeux Logiques</h3>
      <p>Implémentation de l'Awalé (C/Tkinter) et du Jeu de la Vie (Java MVC).</p>
      <div class="tags"><span class="tag">Algorithmie</span><span class="tag">Java</span></div>
    </div>

  </div>
</section>

<section>
  <h2><span>Expériences</span> Professionnelles</h2>
  <div class="timeline">

    <div class="job">
      <h3>La Poste Groupe</h3>
      <span>Février 2024 – Mai 2024</span>
      <p>Refonte d'un outil interne d'audit cybersécurité. Intégration Nessus/Nmap, automatisation et CI/CD GitLab.</p>
    </div>

    <div class="job">
      <h3>Observatoire de Paris</h3>
      <span>Mai 2021 – Juillet 2021</span>
      <p>Migration critique Java → C pour un logiciel de pilotage d'antenne. Scripts Python pour interface web.</p>
    </div>

    <div class="job">
      <h3>McDonald's & Big Bang</h3>
      <span>2021 – Aujourd'hui</span>
      <p>Gestion d'équipe (Aspirant Manager), rigueur opérationnelle, leadership et gestion du stress.</p>
    </div>

  </div>
</section>

<footer>
  <p>Tsiky Rivoherison – 94230 Cachan</p>
  <p>+33 6 68 40 66 75</p>
  <small>© 2026 – Portfolio personnel</small>
</footer>

</body>
</html>
