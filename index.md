---
layout: default
---

<!-- ============ HERO ============ -->
<section class="hero">
  <div class="container hero-content">
    <div class="hero-text">
      <span class="hero-badge"><span class="status-dot"></span> Available for opportunities</span>
      <h1 class="hero-title">
        <span class="line">Mohammed Amine</span>
        <span class="line gradient-text">Izem</span>
      </h1>
      <p class="hero-subtitle" id="typed" data-roles='["Full-Stack Developer","Real-time Systems Engineer","1337 / 42 Student","Systems &amp; Low-level Enthusiast"]'>&gt;&nbsp;<span class="txt"></span><span class="cursor">_</span></p>
      <p class="hero-about">
        Developer from <strong>Morocco</strong> building <strong>functional, high-performance applications</strong>.
        Trained at <strong>1337 / 42 Network</strong> to solve complex problems, understand systems deeply,
        and ship <strong>clean, maintainable code</strong>.
      </p>
      <div class="hero-buttons">
        <a href="#projects" class="btn btn-primary">View my work →</a>
        <a href="{{ '/assets/Mohammed_Amine_Izem_CV.pdf' | relative_url }}" class="btn btn-ghost" download>↓ Download CV</a>
        <a href="#contact" class="btn btn-ghost">Get in touch</a>
      </div>
      <div class="hero-stats">
        <div class="hero-stat"><div class="num"><span data-count="3" data-suffix="+">0</span></div><div class="label">Major Projects</div></div>
        <div class="hero-stat"><div class="num"><span data-count="5" data-suffix="+">0</span></div><div class="label">Languages</div></div>
        <div class="hero-stat"><div class="num"><span data-count="1337">0</span></div><div class="label">@ School</div></div>
      </div>
    </div>
    <div class="hero-image">
      <div class="frame">
        <img src="images/mizem.png" alt="Mohammed Amine Izem" class="profile-photo">
      </div>
      <div class="hero-float a"><span class="tag">const</span> role = <span class="tag">"dev"</span></div>
      <div class="hero-float b">⚡ real-time &amp; systems</div>
    </div>
  </div>
  <a href="#skills" class="scroll-hint"><span class="mouse"></span>scroll</a>
</section>

<!-- ============ ABOUT ============ -->
<section class="about" id="about">
  <div class="container">
    <div class="section-head reveal">
      <span class="section-kicker">01 — Who I Am</span>
      <h2 class="section-title">About <span class="gradient-text">Me</span></h2>
    </div>
    <div class="about-grid">
      <div class="about-text reveal">
        <p>
          I'm <strong>Mohammed Amine Izem</strong>, a software engineering student at
          <strong>1337 (42 Network)</strong> based in Tetouan, Morocco. I fell for programming through
          the peer-learning, project-driven grind of 42 — where you learn by <em>building</em>, breaking
          things, and rebuilding them better.
        </p>
        <p>
          My sweet spot is <strong>full-stack and real-time systems</strong>: from low-level C and Unix
          internals up to modern TypeScript back-ends and React front-ends. I care about clean
          architecture, performance, and code that's a pleasure to maintain.
        </p>
        <p>
          When I'm not shipping features, I'm digging into how things work under the hood — networking,
          concurrency, containers, and the systems that make software fast and reliable.
        </p>
      </div>
      <div class="about-panel card reveal">
        <ul class="about-facts">
          <li><span class="k">// focus</span><span class="v">Full-Stack &amp; Real-time Systems</span></li>
          <li><span class="k">// school</span><span class="v">1337 — 42 Network</span></li>
          <li><span class="k">// based</span><span class="v">Tetouan, Morocco</span></li>
          <li><span class="k">// learning</span><span class="v">Systems, Networking, DevOps</span></li>
          <li><span class="k">// status</span><span class="v"><span class="status-dot"></span> Open to opportunities</span></li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ============ SKILLS ============ -->
<section class="skills" id="skills">
  <div class="container">
    <div class="section-head reveal">
      <span class="section-kicker">02 — Toolbox</span>
      <h2 class="section-title">Tech <span class="gradient-text">Stack</span></h2>
    </div>
    <div class="skills-grid">
      <div class="card skill-category reveal">
        <h3><span class="ico">💻</span> Languages</h3>
        <div class="skill-tags">
          <span class="skill-tag">C</span><span class="skill-tag">C++</span>
          <span class="skill-tag">TypeScript</span><span class="skill-tag">JavaScript</span>
        </div>
      </div>
      <div class="card skill-category reveal">
        <h3><span class="ico">⚙️</span> Backend</h3>
        <div class="skill-tags">
          <span class="skill-tag">Node.js</span><span class="skill-tag">NestJS</span>
          <span class="skill-tag">Express</span><span class="skill-tag">Socket.io</span>
        </div>
      </div>
      <div class="card skill-category reveal">
        <h3><span class="ico">🎨</span> Frontend</h3>
        <div class="skill-tags">
          <span class="skill-tag">React</span><span class="skill-tag">Next.js</span>
          <span class="skill-tag">TailwindCSS</span>
        </div>
      </div>
      <div class="card skill-category reveal">
        <h3><span class="ico">🚀</span> DevOps</h3>
        <div class="skill-tags">
          <span class="skill-tag">Docker</span><span class="skill-tag">Nginx</span>
          <span class="skill-tag">Linux</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ PROJECTS ============ -->
<section class="projects" id="projects">
  <div class="container">
    <div class="section-head reveal">
      <span class="section-kicker">03 — Selected Work</span>
      <h2 class="section-title">Featured <span class="gradient-text">Projects</span></h2>
    </div>
    <div class="card project-spotlight tilt reveal">
      <div class="spotlight-head">
        <span class="spotlight-badge">★ Latest</span>
        <span class="project-index">01</span>
      </div>
      <div class="spotlight-image">
        <img src="images/vixora.png?v=3" alt="MyVixora platform">
      </div>
      <div class="spotlight-body">
        <div class="spotlight-main">
          <h3>MyVixora</h3>
          <p class="project-subtitle">SEO-Driven Subscription Platform</p>
          <p class="project-description">
            A production subscription platform for the UK market, built on Next.js App Router and deployed
            on Vercel. Genuinely full-stack: a commerce backend with orders, payments, and an authenticated
            admin dashboard — plus technical SEO, performance, content architecture, and growth features.
          </p>
          <h4 class="side-label group-label">// backend &amp; commerce</h4>
          <div class="project-features">
            <span class="feature">PostgreSQL + Prisma data layer with an Order model tracking plans, payment status, and renewals</span>
            <span class="feature">API routes for orders, payment sync, and contact — request validation with Zod schemas at the API boundary</span>
            <span class="feature">Authenticated admin dashboard (bcrypt login) with protected order-management and renewal endpoints</span>
            <span class="feature">Rate limiting on API routes via Upstash Redis + @upstash/ratelimit</span>
            <span class="feature">Transactional email with Resend for order and contact notifications</span>
            <span class="feature">Checkout flow wired end-to-end into the orders / payment-sync API</span>
          </div>
          <h4 class="side-label group-label">// seo &amp; growth</h4>
          <div class="project-features">
            <span class="feature">Technical SEO audits (crawlability, indexation, Core Web Vitals) — including diagnosing and fixing an LCP regression</span>
            <span class="feature">JSON-LD structured data: Organization, Service, FAQPage, Breadcrumb, Article</span>
            <span class="feature">File-based MDX blog engine — dynamic routing, metadata, auto-discovered sitemap</span>
            <span class="feature">Long-tail keyword strategy with fact-checked articles and topic-cluster internal linking</span>
            <span class="feature">Referral promo bar with live countdown — SSR-safe state via useSyncExternalStore</span>
          </div>
        </div>
        <div class="spotlight-side">
          <h4 class="side-label">// stack</h4>
          <div class="project-tech">
            <span class="tech-badge">Next.js 16</span><span class="tech-badge">React 19</span>
            <span class="tech-badge">TypeScript</span><span class="tech-badge">Tailwind CSS 4</span>
            <span class="tech-badge">MDX</span><span class="tech-badge">Prisma</span>
            <span class="tech-badge">PostgreSQL</span><span class="tech-badge">Vercel</span>
          </div>
          <h4 class="side-label">// backend</h4>
          <div class="project-tech">
            <span class="tech-badge">Upstash Redis</span><span class="tech-badge">Resend</span>
            <span class="tech-badge">Zod</span><span class="tech-badge">bcrypt</span>
          </div>
          <h4 class="side-label">// tooling</h4>
          <div class="project-tech">
            <span class="tech-badge">Search Console API</span><span class="tech-badge">GA4</span>
            <span class="tech-badge">Schema.org JSON-LD</span><span class="tech-badge">Vercel Analytics</span>
          </div>
          <h4 class="side-label">// skills</h4>
          <div class="project-tech">
            <span class="tech-badge">Full-Stack Architecture</span><span class="tech-badge">API &amp; Auth Design</span>
            <span class="tech-badge">Technical SEO</span><span class="tech-badge">Core Web Vitals</span>
            <span class="tech-badge">SSR-safe React</span><span class="tech-badge">Content Strategy</span>
          </div>
        </div>
      </div>
    </div>

    <div class="projects-grid">
      <div class="card project-card tilt reveal">
        <div class="project-image">
          <span class="project-index">02</span>
          <img src="images/trans.png" alt="ft_transcendence">
        </div>
        <div class="project-content">
          <h3>ft_transcendence</h3>
          <p class="project-subtitle">Real-Time Multiplayer Soccer Game</p>
          <p class="project-description">
            A real-time multiplayer soccer game built with modern full-stack tech. Engineered the core
            real-time infrastructure with a server-side physics engine and collision detection.
          </p>
          <div class="project-tech">
            <span class="tech-badge">NestJS</span><span class="tech-badge">React</span>
            <span class="tech-badge">Socket.io</span><span class="tech-badge">TypeScript</span>
          </div>
          <div class="project-features">
            <span class="feature">Real-time multiplayer gameplay</span>
            <span class="feature">Server-side physics engine</span>
            <span class="feature">Live state synchronization</span>
          </div>
          <div class="project-links">
            <a href="https://github.com/Mizemm/ft_transcendence" target="_blank" rel="noopener" class="project-link">&lt;/&gt; Code</a>
          </div>
        </div>
      </div>

      <div class="card project-card tilt reveal">
        <div class="project-image">
          <span class="project-index">03</span>
          <img src="images/minish.png" alt="Minishell">
        </div>
        <div class="project-content">
          <h3>Minishell</h3>
          <p class="project-subtitle">Custom Bash-Like Shell</p>
          <p class="project-description">
            A Unix shell written in C that replicates many behaviors of Bash — a deep dive into Unix
            internals and system calls.
          </p>
          <div class="project-tech">
            <span class="tech-badge">C</span><span class="tech-badge">Unix</span>
            <span class="tech-badge">System Calls</span>
          </div>
          <div class="project-features">
            <span class="feature">Process creation &amp; execution</span>
            <span class="feature">Pipes and redirections</span>
            <span class="feature">Signal handling</span>
          </div>
          <div class="project-links">
            <a href="https://github.com/Mizemm/minishell" target="_blank" rel="noopener" class="project-link">&lt;/&gt; Code</a>
          </div>
        </div>
      </div>

      <div class="card project-card tilt reveal">
        <div class="project-image">
          <span class="project-index">04</span>
          <img src="images/inception.png" alt="Inception">
        </div>
        <div class="project-content">
          <h3>Inception</h3>
          <p class="project-subtitle">Docker Infrastructure Project</p>
          <p class="project-description">
            A complete containerized infrastructure built with Docker — real-world DevOps with service
            orchestration and reverse-proxy configuration.
          </p>
          <div class="project-tech">
            <span class="tech-badge">Docker</span><span class="tech-badge">Nginx</span>
            <span class="tech-badge">WordPress</span><span class="tech-badge">MariaDB</span>
          </div>
          <div class="project-features">
            <span class="feature">Service orchestration</span>
            <span class="feature">Reverse proxy</span>
            <span class="feature">Production-ready setup</span>
          </div>
          <div class="project-links">
            <a href="https://github.com/Mizemm/Inception" target="_blank" rel="noopener" class="project-link">&lt;/&gt; Code</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ CONTACT ============ -->
<section class="contact" id="contact">
  <div class="container">
    <div class="section-head reveal">
      <span class="section-kicker">04 — Say Hello</span>
      <h2 class="section-title">Get In <span class="gradient-text">Touch</span></h2>
    </div>
    <div class="contact-shell reveal">
      <div class="contact-content">
        <div class="contact-info">
          <div class="contact-item">
            <span class="contact-icon">📧</span>
            <div><h4>Email</h4><a href="mailto:amineshady6@gmail.com">amineshady6@gmail.com</a></div>
          </div>
          <div class="contact-item">
            <span class="contact-icon">📍</span>
            <div><h4>Location</h4><p>Tetouan, Morocco</p></div>
          </div>
          <div class="contact-item">
            <span class="contact-icon">💼</span>
            <div><h4>LinkedIn</h4><a href="https://www.linkedin.com/in/mizemm/" target="_blank" rel="noopener">linkedin.com/in/mizemm</a></div>
          </div>
        </div>
        <div class="contact-actions">
          <h3>Let's build something.</h3>
          <p>Interested in working together? Let's connect and discuss how I can contribute to your team or project.</p>
          <div class="social-links">
            <a href="https://github.com/Mizemm" target="_blank" rel="noopener" class="btn btn-primary">GitHub Profile ↗</a>
            <a href="https://www.linkedin.com/in/mizemm/" target="_blank" rel="noopener" class="btn btn-ghost">LinkedIn ↗</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
