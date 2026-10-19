<!-- README.md - Versão limpa, premium, com tema claro/escuro e animações sutis -->
<div align="center">
  <svg width="100%" height="120" viewBox="0 0 1200 120" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg" style="max-width:720px;margin:28px 0">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0%" stop-color="#ff7a18">
          <animate attributeName="stop-color" values="#ff7a18;#ff5a7a;#6a11cb;#ff7a18" dur="8s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#6a11cb">
          <animate attributeName="stop-color" values="#6a11cb;#18a0ff;#ff5a7a;#6a11cb" dur="8s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
      <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
        <feDropShadow dx="0" dy="8" stdDeviation="16" flood-opacity="0.12" />
      </filter>
    </defs>
    <text x="50%" y="50%" text-anchor="middle" dominant-baseline="middle" font-family:"-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="46" fill="url(#g)" style="font-weight:700;filter:url(#shadow);">
      Victor Leonardo
    </text>
  </svg>

  <p style="margin:6px 0 18px;color:var(--muted);font-family:system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;">
    Olá — eu sou o Victor! 👋 · Técnico em Desenvolvimento de Sistemas · Cursando Full‑Stack em Python
  </p>
</div>

<style>
:root{
  --bg:#ffffff; --card:#f7f7fb; --text:#0b1220; --muted:#556; --accent:#ff7a18;
}
@media (prefers-color-scheme: dark){
  :root{ --bg:#0b0f14; --card:#0f1620; --text:#e6eef8; --muted:#9aa6b2; --accent:#6a11cb; }
}
body{background:var(--bg); color:var(--text)}
.readme-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px;align-items:start;margin:18px 0}
.card{background:var(--card);border-radius:12px;padding:18px;box-shadow:0 6px 20px rgba(2,6,23,0.06);transition:transform .28s ease,box-shadow .28s ease}
.card:hover{transform:translateY(-6px);box-shadow:0 18px 40px rgba(2,6,23,0.12)}
.techs{display:flex;gap:12px;flex-wrap:wrap;align-items:center;justify-content:center}
.techs img{width:40px;height:40px;filter:grayscale(0.08);transition:transform .22s ease,filter .22s}
.techs img:hover{transform:translateY(-6px);filter:grayscale(0)}
.center{display:flex;align-items:center;justify-content:center}
.bio{line-height:1.5;color:var(--muted);}
.fade-in{animation:fade .9s ease both}
@keyframes fade{from{opacity:0;transform:translateY(6px)} to{opacity:1;transform:none}}
.contact a{margin:6px;display:inline-block}
.small-muted{font-size:13px;color:var(--muted)}
.repo-cards{display:flex;gap:12px;flex-wrap:wrap;justify-content:center}
.repo-card{min-width:190px;max-width:260px}
</style>

<div class="readme-grid">
  <div class="card fade-in">
    <h3 style="margin:0 0 8px">Sobre</h3>
    <p class="bio" style="margin:0">Sou desenvolvedor full‑stack em formação, com foco em interfaces funcionais, experiência do usuário e aprendizado contínuo. Gosto de construir coisas simples e úteis, e explorar novas ferramentas para entregar soluções elegantes.</p>
  </div>

  <div class="card fade-in">
    <h3 style="margin:0 0 8px">Tecnologias</h3>
    <div class="techs" style="margin-top:8px">
      <img alt="HTML5" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
      <img alt="CSS3" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" />
      <img alt="JavaScript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
      <img alt="TypeScript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" />
      <img alt="React" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
      <img alt="Python" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
      <img alt="Node.js" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
      <img alt="Git" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
      <img alt="Docker" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
    </div>
  </div>

  <div class="card fade-in center">
    <div style="text-align:center;">
      <h3 style="margin:0 0 8px">Estatísticas</h3>
      <div style="display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-top:10px">
        <img alt="GitHub stats" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=victorcaito&theme=default" style="width:220px;border-radius:8px" />
        <img alt="Linguagens" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=victorcaito&theme=default&langs_count=6" style="width:220px;border-radius:8px" />
      </div>
    </div>
  </div>
</div>

<div style="margin-top:8px" class="card fade-in">
  <h3 style="margin:0 0 12px;text-align:center">Contribuições</h3>
  <div class="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg?user=victorcaito&repo=victorcaito&color_snake=orange" />
      <img alt="Contribuições" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg?user=victorcaito&repo=victorcaito&color_snake=orange" style="max-width:100%;height:auto;border-radius:10px;" />
    </picture>
  </div>
  <p class="small-muted center" style="margin-top:8px">Snake das contribuições — versão corrigida (clique para ver o repositório)</p>
</div>

<div class="card fade-in">
  <h3 style="margin:0 0 8px">Projetos em destaque</h3>
  <div class="repo-cards" style="margin-top:8px">
    <a class="repo-card" href="https://github.com/victorcaito" target="_blank" rel="noopener">
      <div style="padding:12px;border-radius:10px;background:linear-gradient(90deg,rgba(255,122,24,0.06),rgba(106,17,203,0.04));">
        <strong>Meu GitHub</strong>
        <div class="small-muted">Repositórios, experimentos e projetos pessoais</div>
      </div>
    </a>
    <!-- Adicione cards de projetos específicos se quiser -->
  </div>
</div>

<div class="card fade-in contact center" style="margin-top:14px;padding:14px">
  <div>
    <div style="margin-bottom:10px;text-align:center"><strong>Contato</strong></div>
    <div style="display:flex;gap:8px;align-items:center;justify-content:center;flex-wrap:wrap">
      <a href="https://www.linkedin.com/in/victorleonardoz/" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
      </a>
      <a href="mailto:victorvarjao.18@gmail.com">
        <img src="https://img.shields.io/badge/E-mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail">
      </a>
      <a href="https://github.com/victorcaito" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </a>
    </div>
  </div>
</div>

<p style="text-align:center;margin-top:14px;font-style:italic;color:var(--muted)">"Construir coisas simples e úteis é a melhor forma de aprender."</p>

<p style="text-align:center;margin-top:6px;color:var(--muted);font-size:12px">Versão limpa e premium — tema automático claro/escuro. Posso ajustar tipografia, animações ou adicionar cards de projetos — diga o que prefere.</p>
