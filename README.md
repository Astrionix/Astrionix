<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Padala L M Ramachandra Reddy — Full Stack Developer crafting elegant, scalable web solutions with passion and precision." />
  <meta name="keywords" content="Full Stack Developer, Web Developer, React, Node.js, Portfolio, Padala Ramachandra Reddy" />
  <meta name="author" content="Padala L M Ramachandra Reddy" />
  <title>Padala Ramachandra Reddy | Full Stack Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800;900&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Custom Cursor -->
  <div id="cursor" class="cursor"></div>
  <div id="cursor-follower" class="cursor-follower"></div>

  <!-- Navigation -->
  <nav id="navbar" class="navbar">
    <div class="nav-container">
      <a href="#home" class="nav-logo" id="nav-logo">
        <span class="logo-bracket">&lt;</span>PLR<span class="logo-bracket">/&gt;</span>
      </a>
      <ul class="nav-links" id="nav-links">
        <li><a href="#home" class="nav-link active" data-section="home">Home</a></li>
        <li><a href="#about" class="nav-link" data-section="about">About</a></li>
        <li><a href="#skills" class="nav-link" data-section="skills">Skills</a></li>
        <li><a href="#projects" class="nav-link" data-section="projects">Projects</a></li>
        <li><a href="#experience" class="nav-link" data-section="experience">Experience</a></li>
        <li><a href="#contact" class="nav-link" data-section="contact">Contact</a></li>
      </ul>
      <button class="hamburger" id="hamburger" aria-label="Toggle menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <canvas id="particle-canvas"></canvas>
    <div class="hero-bg-gradient"></div>
    <div class="floating-orbs">
      <div class="orb orb-1"></div>
      <div class="orb orb-2"></div>
      <div class="orb orb-3"></div>
    </div>
    <div class="hero-content">
      <div class="hero-badge animate-fade-up" style="animation-delay:0.2s">
        <span class="badge-dot"></span>
        <span>Available for opportunities</span>
      </div>
      <p class="hero-greeting animate-fade-up" style="animation-delay:0.4s">Hello, I'm</p>
      <h1 class="hero-name animate-fade-up" style="animation-delay:0.6s">
        Padala<br/>
        <span class="name-highlight">Ramachandra</span><br/>
        Reddy
      </h1>
      <div class="hero-role animate-fade-up" style="animation-delay:0.8s">
        <span class="role-prefix">I build</span>
        <span class="typewriter-wrapper">
          <span id="typewriter" class="typewriter-text"></span>
          <span class="typewriter-cursor">|</span>
        </span>
      </div>
      <p class="hero-desc animate-fade-up" style="animation-delay:1s">
        Crafting elegant, high-performance web applications that bridge<br class="hide-mobile"/>
        beautiful design with powerful engineering.
      </p>
      <div class="hero-actions animate-fade-up" style="animation-delay:1.2s">
        <a href="#projects" class="btn btn-primary" id="view-work-btn">
          <span>View My Work</span>
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
        </a>
        <a href="#contact" class="btn btn-ghost" id="contact-btn">
          <span>Get In Touch</span>
        </a>
      </div>
      <div class="hero-stats animate-fade-up" style="animation-delay:1.4s">
        <div class="stat-item">
          <span class="stat-number" data-target="5">0</span><span class="stat-plus">+</span>
          <span class="stat-label">Years Exp.</span>
        </div>
        <div class="stat-divider"></div>
        <div class="stat-item">
          <span class="stat-number" data-target="50">0</span><span class="stat-plus">+</span>
          <span class="stat-label">Projects</span>
        </div>
        <div class="stat-divider"></div>
        <div class="stat-item">
          <span class="stat-number" data-target="30">0</span><span class="stat-plus">+</span>
          <span class="stat-label">Clients</span>
        </div>
      </div>
    </div>
    <div class="hero-visual animate-fade-left" style="animation-delay:0.8s">
      <div class="hero-avatar-ring">
        <div class="avatar-ring-outer">
          <div class="avatar-ring-inner">
            <div class="avatar-image">
              <div class="avatar-initials">PLR</div>
            </div>
          </div>
        </div>
        <div class="floating-badge badge-react">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="20" height="20" />
          React
        </div>
        <div class="floating-badge badge-node">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" width="20" height="20" />
          Node.js
        </div>
        <div class="floating-badge badge-python">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="20" height="20" />
          Python
        </div>
      </div>
    </div>
    <div class="scroll-indicator animate-fade-up" style="animation-delay:1.8s">
      <div class="scroll-text">Scroll to explore</div>
      <div class="scroll-arrow">
        <div class="scroll-line"></div>
        <div class="scroll-chevron"></div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section about-section">
    <div class="container">
      <div class="section-tag reveal">About Me</div>
      <h2 class="section-title reveal">Passionate Developer,<br/><span class="gradient-text">Problem Solver</span></h2>
      <div class="about-grid">
        <div class="about-card reveal">
          <div class="about-card-inner">
            <div class="about-icon">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M16 18l6-6-6-6M8 6l-6 6 6 6"/>
              </svg>
            </div>
            <h3>Who I Am</h3>
            <p>I'm <strong>Padala L M Ramachandra Reddy</strong>, a Full Stack Developer with a deep love for building digital experiences that are both beautiful and blazing fast. I specialize in turning complex requirements into elegant, maintainable code.</p>
            <p>My journey in tech started with curiosity about how websites work, and grew into a passion for crafting end-to-end solutions — from pixel-perfect UIs to robust backend systems.</p>
          </div>
        </div>
        <div class="about-card reveal" style="animation-delay:0.15s">
          <div class="about-card-inner">
            <div class="about-icon">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/>
              </svg>
            </div>
            <h3>What I Do</h3>
            <p>I architect and build scalable web applications, RESTful APIs, and cloud-native solutions. From React frontends with silky animations to microservices backends with clean architecture — I own the entire stack.</p>
            <p>I thrive in environments where I can lead technical decisions, mentor peers, and deliver products that users love.</p>
          </div>
        </div>
        <div class="about-card reveal" style="animation-delay:0.3s">
          <div class="about-card-inner">
            <div class="about-icon">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                <path d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"/>
              </svg>
            </div>
            <h3>What Drives Me</h3>
            <p>I'm driven by impact — seeing real users interact with something I built from scratch is incredibly rewarding. I love learning new technologies, contributing to open source, and pushing the boundaries of what's possible on the web.</p>
            <p>Outside of code, I enjoy exploring system design, cloud architecture, and the fascinating world of AI/ML integrations.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="section skills-section">
    <div class="container">
      <div class="section-tag reveal">Tech Stack</div>
      <h2 class="section-title reveal">Tools & <span class="gradient-text">Technologies</span></h2>
      <p class="section-subtitle reveal">A curated collection of technologies I work with daily to ship production-ready products.</p>

      <div class="skills-tabs reveal">
        <button class="skills-tab active" data-tab="frontend" id="tab-frontend">Frontend</button>
        <button class="skills-tab" data-tab="backend" id="tab-backend">Backend</button>
        <button class="skills-tab" data-tab="database" id="tab-database">Database</button>
        <button class="skills-tab" data-tab="devops" id="tab-devops">DevOps & Cloud</button>
        <button class="skills-tab" data-tab="tools" id="tab-tools">Tools</button>
      </div>

      <div class="skills-panels">
        <div class="skills-panel active" data-panel="frontend">
          <div class="skills-grid">
            <div class="skill-card reveal" data-level="95">
              <div class="skill-icon-wrap" style="--icon-color:#61DAFB">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" />
              </div>
              <div class="skill-info">
                <span class="skill-name">React.js</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:95%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="88" style="animation-delay:0.05s">
              <div class="skill-icon-wrap" style="--icon-color:#000">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Next.js</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:88%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="92" style="animation-delay:0.1s">
              <div class="skill-icon-wrap" style="--icon-color:#3178C6">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" />
              </div>
              <div class="skill-info">
                <span class="skill-name">TypeScript</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:92%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="90" style="animation-delay:0.15s">
              <div class="skill-icon-wrap" style="--icon-color:#F7DF1E">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" />
              </div>
              <div class="skill-info">
                <span class="skill-name">JavaScript</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:90%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="85" style="animation-delay:0.2s">
              <div class="skill-icon-wrap" style="--icon-color:#E34F26">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" />
              </div>
              <div class="skill-info">
                <span class="skill-name">HTML5</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:85%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="83" style="animation-delay:0.25s">
              <div class="skill-icon-wrap" style="--icon-color:#1572B6">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" />
              </div>
              <div class="skill-info">
                <span class="skill-name">CSS3</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:83%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="80" style="animation-delay:0.3s">
              <div class="skill-icon-wrap" style="--icon-color:#0EA5E9">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" alt="Tailwind CSS" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Tailwind CSS</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:80%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="78" style="animation-delay:0.35s">
              <div class="skill-icon-wrap" style="--icon-color:#764ABC">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redux/redux-original.svg" alt="Redux" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Redux</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:78%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
          </div>
        </div>

        <div class="skills-panel" data-panel="backend">
          <div class="skills-grid">
            <div class="skill-card reveal" data-level="93">
              <div class="skill-icon-wrap" style="--icon-color:#339933">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Node.js</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:93%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="87" style="animation-delay:0.05s">
              <div class="skill-icon-wrap" style="--icon-color:#000000">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express.js" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Express.js</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:87%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="85" style="animation-delay:0.1s">
              <div class="skill-icon-wrap" style="--icon-color:#3776AB">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Python</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:85%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="78" style="animation-delay:0.15s">
              <div class="skill-icon-wrap" style="--icon-color:#009688">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" />
              </div>
              <div class="skill-info">
                <span class="skill-name">FastAPI</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:78%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="75" style="animation-delay:0.2s">
              <div class="skill-icon-wrap" style="--icon-color:#6DB33F">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Spring Boot</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:75%"></div></div>
                <span class="skill-level">Proficient</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="80" style="animation-delay:0.25s">
              <div class="skill-icon-wrap" style="--icon-color:#E10098">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" alt="GraphQL" />
              </div>
              <div class="skill-info">
                <span class="skill-name">GraphQL</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:80%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
          </div>
        </div>

        <div class="skills-panel" data-panel="database">
          <div class="skills-grid">
            <div class="skill-card reveal" data-level="90">
              <div class="skill-icon-wrap" style="--icon-color:#47A248">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" />
              </div>
              <div class="skill-info">
                <span class="skill-name">MongoDB</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:90%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="85" style="animation-delay:0.05s">
              <div class="skill-icon-wrap" style="--icon-color:#336791">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" />
              </div>
              <div class="skill-info">
                <span class="skill-name">PostgreSQL</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:85%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="82" style="animation-delay:0.1s">
              <div class="skill-icon-wrap" style="--icon-color:#4479A1">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" />
              </div>
              <div class="skill-info">
                <span class="skill-name">MySQL</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:82%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="75" style="animation-delay:0.15s">
              <div class="skill-icon-wrap" style="--icon-color:#DC382D">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" alt="Redis" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Redis</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:75%"></div></div>
                <span class="skill-level">Proficient</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="70" style="animation-delay:0.2s">
              <div class="skill-icon-wrap" style="--icon-color:#FF9900">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" alt="DynamoDB" />
              </div>
              <div class="skill-info">
                <span class="skill-name">DynamoDB</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:70%"></div></div>
                <span class="skill-level">Proficient</span>
              </div>
            </div>
          </div>
        </div>

        <div class="skills-panel" data-panel="devops">
          <div class="skills-grid">
            <div class="skill-card reveal" data-level="85">
              <div class="skill-icon-wrap" style="--icon-color:#2496ED">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Docker</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:85%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="75" style="animation-delay:0.05s">
              <div class="skill-icon-wrap" style="--icon-color:#326CE5">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Kubernetes</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:75%"></div></div>
                <span class="skill-level">Proficient</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="88" style="animation-delay:0.1s">
              <div class="skill-icon-wrap" style="--icon-color:#FF9900">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS" />
              </div>
              <div class="skill-info">
                <span class="skill-name">AWS</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:88%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="82" style="animation-delay:0.15s">
              <div class="skill-icon-wrap" style="--icon-color:#F05032">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Git & CI/CD</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:82%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="78" style="animation-delay:0.2s">
              <div class="skill-icon-wrap" style="--icon-color:#4285F4">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" alt="GCP" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Google Cloud</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:78%"></div></div>
                <span class="skill-level">Proficient</span>
              </div>
            </div>
          </div>
        </div>

        <div class="skills-panel" data-panel="tools">
          <div class="skills-grid">
            <div class="skill-card reveal" data-level="92">
              <div class="skill-icon-wrap" style="--icon-color:#181717">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" />
              </div>
              <div class="skill-info">
                <span class="skill-name">GitHub</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:92%"></div></div>
                <span class="skill-level">Expert</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="85" style="animation-delay:0.05s">
              <div class="skill-icon-wrap" style="--icon-color:#007ACC">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" />
              </div>
              <div class="skill-info">
                <span class="skill-name">VS Code</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:85%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="80" style="animation-delay:0.1s">
              <div class="skill-icon-wrap" style="--icon-color:#FF7262">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Figma" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Figma</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:80%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
            <div class="skill-card reveal" data-level="78" style="animation-delay:0.15s">
              <div class="skill-icon-wrap" style="--icon-color:#FF6C37">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" alt="Postman" />
              </div>
              <div class="skill-info">
                <span class="skill-name">Postman</span>
                <div class="skill-bar"><div class="skill-fill" style="--target:78%"></div></div>
                <span class="skill-level">Advanced</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="section projects-section">
    <div class="container">
      <div class="section-tag reveal">Portfolio</div>
      <h2 class="section-title reveal">Featured <span class="gradient-text">Projects</span></h2>
      <p class="section-subtitle reveal">A selection of real-world applications I've designed, built, and shipped.</p>

      <div class="projects-grid">
        <div class="project-card featured reveal" id="project-ecommerce">
          <div class="project-image" style="background: linear-gradient(135deg, #FF6B35, #FF4081)">
            <div class="project-image-content">
              <div class="project-mockup">
                <div class="mockup-bar"></div>
                <div class="mockup-content">
                  <div class="mockup-line long"></div>
                  <div class="mockup-line medium"></div>
                  <div class="mockup-grid">
                    <div class="mockup-card"></div>
                    <div class="mockup-card"></div>
                    <div class="mockup-card"></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="project-overlay">
              <a href="#" class="project-link-btn" aria-label="View Project">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6M15 3h6v6M10 14L21 3"/></svg>
              </a>
              <a href="#" class="project-link-btn" aria-label="View Code">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 00-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0020 4.77 5.07 5.07 0 0019.91 1S18.73.65 16 2.48a13.38 13.38 0 00-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 005 4.77a5.44 5.44 0 00-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 009 18.13V22"/></svg>
              </a>
            </div>
          </div>
          <div class="project-info">
            <div class="project-meta">
              <span class="project-badge">Featured</span>
              <span class="project-year">2024</span>
            </div>
            <h3 class="project-title">E-Commerce Platform</h3>
            <p class="project-desc">A full-featured e-commerce solution with real-time inventory, AI-powered recommendations, and seamless payment integration. Handles 10k+ concurrent users.</p>
            <div class="project-tags">
              <span>React</span><span>Node.js</span><span>MongoDB</span><span>Redis</span><span>AWS</span>
            </div>
          </div>
        </div>

        <div class="project-card reveal" id="project-analytics" style="animation-delay:0.1s">
          <div class="project-image" style="background: linear-gradient(135deg, #FFD700, #FF6B35)">
            <div class="project-image-content">
              <div class="project-mockup">
                <div class="mockup-bar"></div>
                <div class="mockup-content">
                  <div class="mockup-chart">
                    <div class="chart-bar" style="height:60%"></div>
                    <div class="chart-bar" style="height:80%"></div>
                    <div class="chart-bar" style="height:45%"></div>
                    <div class="chart-bar" style="height:90%"></div>
                    <div class="chart-bar" style="height:70%"></div>
                    <div class="chart-bar" style="height:55%"></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="project-overlay">
              <a href="#" class="project-link-btn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6M15 3h6v6M10 14L21 3"/></svg></a>
              <a href="#" class="project-link-btn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 00-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0020 4.77 5.07 5.07 0 0019.91 1S18.73.65 16 2.48a13.38 13.38 0 00-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 005 4.77a5.44 5.44 0 00-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 009 18.13V22"/></svg></a>
            </div>
          </div>
          <div class="project-info">
            <div class="project-meta">
              <span class="project-year">2024</span>
            </div>
            <h3 class="project-title">Analytics Dashboard</h3>
            <p class="project-desc">Real-time analytics platform with interactive charts, custom reporting, and ML-powered insights for business intelligence.</p>
            <div class="project-tags">
              <span>Next.js</span><span>Python</span><span>PostgreSQL</span><span>D3.js</span>
            </div>
          </div>
        </div>

        <div class="project-card reveal" id="project-chat" style="animation-delay:0.2s">
          <div class="project-image" style="background: linear-gradient(135deg, #FF4081, #FFD700)">
            <div class="project-image-content">
              <div class="project-mockup">
                <div class="mockup-bar"></div>
                <div class="mockup-content">
                  <div class="mockup-chat">
                    <div class="chat-bubble left"></div>
                    <div class="chat-bubble right"></div>
                    <div class="chat-bubble left short"></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="project-overlay">
              <a href="#" class="project-link-btn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6M15 3h6v6M10 14L21 3"/></svg></a>
              <a href="#" class="project-link-btn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 00-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0020 4.77 5.07 5.07 0 0019.91 1S18.73.65 16 2.48a13.38 13.38 0 00-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 005 4.77a5.44 5.44 0 00-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 009 18.13V22"/></svg></a>
            </div>
          </div>
          <div class="project-info">
            <div class="project-meta">
              <span class="project-year">2023</span>
            </div>
            <h3 class="project-title">Real-Time Chat App</h3>
            <p class="project-desc">Scalable messaging platform with WebSocket connections, end-to-end encryption, and file sharing capabilities.</p>
            <div class="project-tags">
              <span>React</span><span>Socket.io</span><span>Node.js</span><span>MongoDB</span>
            </div>
          </div>
        </div>

        <div class="project-card reveal" id="project-api" style="animation-delay:0.3s">
          <div class="project-image" style="background: linear-gradient(135deg, #FF9A3C, #FF4081)">
            <div class="project-image-content">
              <div class="project-mockup">
                <div class="mockup-bar"></div>
                <div class="mockup-content">
                  <div class="mockup-code">
                    <div class="code-line"><span class="code-keyword">POST</span> /api/users</div>
                    <div class="code-line"><span class="code-string">"status"</span>: 201</div>
                    <div class="code-line"><span class="code-keyword">GET</span> /api/data</div>
                    <div class="code-line"><span class="code-string">"items"</span>: [...]</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="project-overlay">
              <a href="#" class="project-link-btn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6M15 3h6v6M10 14L21 3"/></svg></a>
              <a href="#" class="project-link-btn"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 00-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0020 4.77 5.07 5.07 0 0019.91 1S18.73.65 16 2.48a13.38 13.38 0 00-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 005 4.77a5.44 5.44 0 00-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 009 18.13V22"/></svg></a>
            </div>
          </div>
          <div class="project-info">
            <div class="project-meta">
              <span class="project-year">2023</span>
            </div>
            <h3 class="project-title">RESTful API Platform</h3>
            <p class="project-desc">Microservices-based REST API with rate limiting, authentication, comprehensive docs, and 99.9% uptime SLA.</p>
            <div class="project-tags">
              <span>FastAPI</span><span>Docker</span><span>PostgreSQL</span><span>Redis</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="section experience-section">
    <div class="container">
      <div class="section-tag reveal">Career</div>
      <h2 class="section-title reveal">Work <span class="gradient-text">Experience</span></h2>
      <div class="timeline">
        <div class="timeline-item reveal" id="exp-1">
          <div class="timeline-marker">
            <div class="timeline-dot"></div>
            <div class="timeline-line"></div>
          </div>
          <div class="timeline-content">
            <div class="timeline-header">
              <div>
                <h3 class="timeline-role">Senior Full Stack Developer</h3>
                <span class="timeline-company">TechCorp Solutions Pvt. Ltd.</span>
              </div>
              <span class="timeline-date">2022 — Present</span>
            </div>
            <p class="timeline-desc">Lead end-to-end development of enterprise SaaS products serving 50K+ users. Architected scalable microservices reducing latency by 60%. Mentor junior developers and drive code reviews.</p>
            <div class="timeline-tags">
              <span>React</span><span>Node.js</span><span>AWS</span><span>Docker</span><span>PostgreSQL</span>
            </div>
          </div>
        </div>

        <div class="timeline-item reveal" id="exp-2" style="animation-delay:0.15s">
          <div class="timeline-marker">
            <div class="timeline-dot"></div>
            <div class="timeline-line"></div>
          </div>
          <div class="timeline-content">
            <div class="timeline-header">
              <div>
                <h3 class="timeline-role">Full Stack Developer</h3>
                <span class="timeline-company">InnovateLabs Technologies</span>
              </div>
              <span class="timeline-date">2020 — 2022</span>
            </div>
            <p class="timeline-desc">Built and maintained web applications from scratch. Integrated third-party APIs, implemented CI/CD pipelines, and improved system performance by 40%.</p>
            <div class="timeline-tags">
              <span>Vue.js</span><span>Python</span><span>FastAPI</span><span>MongoDB</span>
            </div>
          </div>
        </div>

        <div class="timeline-item reveal" id="exp-3" style="animation-delay:0.3s">
          <div class="timeline-marker">
            <div class="timeline-dot"></div>
          </div>
          <div class="timeline-content">
            <div class="timeline-header">
              <div>
                <h3 class="timeline-role">Junior Web Developer</h3>
                <span class="timeline-company">StartupHub India</span>
              </div>
              <span class="timeline-date">2019 — 2020</span>
            </div>
            <p class="timeline-desc">Developed responsive web interfaces and integrated backend APIs. Contributed to agile sprints and improved UI/UX for client-facing dashboards.</p>
            <div class="timeline-tags">
              <span>JavaScript</span><span>HTML/CSS</span><span>React</span><span>Node.js</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact-section">
    <div class="container">
      <div class="section-tag reveal">Let's Talk</div>
      <h2 class="section-title reveal">Get In <span class="gradient-text">Touch</span></h2>
      <p class="section-subtitle reveal">Have a project in mind or want to discuss opportunities? I'd love to hear from you.</p>

      <div class="contact-grid">
        <div class="contact-info reveal">
          <div class="contact-info-card">
            <div class="contact-item" id="contact-email">
              <div class="contact-icon">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                  <path d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                </svg>
              </div>
              <div>
                <span class="contact-label">Email</span>
                <a href="mailto:plmramachandra@gmail.com" class="contact-value">plmramachandra@gmail.com</a>
              </div>
            </div>
            <div class="contact-item" id="contact-location">
              <div class="contact-icon">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                  <path d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                </svg>
              </div>
              <div>
                <span class="contact-label">Location</span>
                <span class="contact-value">Andhra Pradesh, India</span>
              </div>
            </div>
            <div class="contact-item" id="contact-availability">
              <div class="contact-icon">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
                  <path d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"/>
                </svg>
              </div>
              <div>
                <span class="contact-label">Availability</span>
                <span class="contact-value available">Open to opportunities</span>
              </div>
            </div>

            <div class="social-links">
              <a href="#" class="social-link" id="social-github" aria-label="GitHub">
                <svg viewBox="0 0 24 24" fill="currentColor"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 00-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0020 4.77 5.07 5.07 0 0019.91 1S18.73.65 16 2.48a13.38 13.38 0 00-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 005 4.77a5.44 5.44 0 00-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 009 18.13V22"/></svg>
              </a>
              <a href="#" class="social-link" id="social-linkedin" aria-label="LinkedIn">
                <svg viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"/><circle cx="4" cy="4" r="2"/></svg>
              </a>
              <a href="#" class="social-link" id="social-twitter" aria-label="Twitter/X">
                <svg viewBox="0 0 24 24" fill="currentColor"><path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"/></svg>
              </a>
            </div>
          </div>
        </div>

        <div class="contact-form-wrap reveal" style="animation-delay:0.2s">
          <form class="contact-form" id="contact-form" novalidate>
            <div class="form-group">
              <label for="name" class="form-label">Your Name</label>
              <input type="text" id="name" name="name" class="form-input" placeholder="John Doe" required />
            </div>
            <div class="form-group">
              <label for="email" class="form-label">Your Email</label>
              <input type="email" id="email" name="email" class="form-input" placeholder="john@example.com" required />
            </div>
            <div class="form-group">
              <label for="subject" class="form-label">Subject</label>
              <input type="text" id="subject" name="subject" class="form-input" placeholder="Project Collaboration" required />
            </div>
            <div class="form-group">
              <label for="message" class="form-label">Message</label>
              <textarea id="message" name="message" class="form-input form-textarea" placeholder="Tell me about your project..." required rows="5"></textarea>
            </div>
            <button type="submit" class="btn btn-primary btn-full" id="submit-btn">
              <span>Send Message</span>
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 2L11 13M22 2l-7 20-4-9-9-4 20-7z"/></svg>
            </button>
            <div id="form-success" class="form-success" style="display:none">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 11.08V12a10 10 0 11-5.93-9.14M22 4L12 14.01l-3-3"/></svg>
              Message sent! I'll get back to you soon.
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <div class="footer-inner">
        <div class="footer-logo">
          <span class="logo-bracket">&lt;</span>PLR<span class="logo-bracket">/&gt;</span>
        </div>
        <p class="footer-text">
          Designed & Built with <span class="heart">♥</span> by <strong>Padala L M Ramachandra Reddy</strong>
        </p>
        <p class="footer-copy">© 2026 All rights reserved.</p>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
