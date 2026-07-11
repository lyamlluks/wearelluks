/* LLUKS — single-page website */

:root {
  --bone: #eee9df;
  --paper: #f7f4ee;
  --ink: #151513;
  --muted: #76736c;
  --line: rgba(21, 21, 19, 0.15);
  --warm: #ad6f4f;
  --sage: #798173;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  background: var(--paper);
  color: var(--ink);
  font-family: "DM Sans", sans-serif;
  line-height: 1.6;
  overflow-x: hidden;
}

a {
  color: inherit;
  text-decoration: none;
}

.grain {
  position: fixed;
  inset: 0;
  pointer-events: none;
  opacity: 0.055;
  z-index: 999;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 220 220' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='.7'/%3E%3C/svg%3E");
}

.site-header {
  height: 92px;
  padding: 0 clamp(24px, 5vw, 80px);
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 1px solid var(--line);
  position: relative;
  z-index: 50;
}

.logo {
  font-family: "Manrope", sans-serif;
  font-size: 1.45rem;
  font-weight: 700;
  letter-spacing: 0.12em;
}

.site-nav {
  display: flex;
  align-items: center;
  gap: 34px;
  font-size: 0.9rem;
}

.site-nav a {
  transition: opacity 0.25s ease;
}

.site-nav a:hover {
  opacity: 0.55;
}

.nav-cta {
  border: 1px solid var(--ink);
  padding: 11px 18px;
}

.menu-toggle {
  display: none;
  border: 0;
  background: transparent;
}

.hero {
  min-height: calc(100vh - 92px);
  display: grid;
  grid-template-columns: 1.06fr 0.94fr;
  gap: 6vw;
  padding: clamp(70px, 9vw, 130px) clamp(24px, 5vw, 80px);
  align-items: center;
}

.eyebrow {
  font-size: 0.72rem;
  letter-spacing: 0.19em;
  font-weight: 600;
  margin-bottom: 24px;
}

.hero h1,
h2 {
  font-family: "Manrope", sans-serif;
  font-weight: 600;
  line-height: 1.04;
  letter-spacing: -0.045em;
}

.hero h1 {
  font-size: clamp(3.3rem, 7.4vw, 7rem);
  max-width: 920px;
}

.hero h1 em {
  color: var(--warm);
  font-style: normal;
}

.hero-text {
  max-width: 580px;
  margin-top: 32px;
  color: var(--muted);
  font-size: clamp(1rem, 1.4vw, 1.15rem);
}

.hero-actions {
  display: flex;
  align-items: center;
  gap: 32px;
  margin-top: 42px;
}

.button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 15px 23px;
  font-size: 0.9rem;
  transition: transform 0.25s ease, opacity 0.25s ease;
}

.button:hover {
  transform: translateY(-2px);
}

.button-dark {
  background: var(--ink);
  color: var(--bone);
}

.text-link {
  font-size: 0.9rem;
}

.text-link span {
  margin-left: 7px;
}

.hero-visual {
  position: relative;
  min-height: 585px;
}

.image-panel {
  height: 100%;
  min-height: 585px;
  position: relative;
  overflow: hidden;
  background:
    linear-gradient(145deg, rgba(21,21,19,.12), rgba(21,21,19,.45)),
    url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1600&q=85") center/cover;
}

.image-panel::after {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(to top, rgba(13,13,12,.6), transparent 55%);
}

.image-panel p {
  color: white;
  position: absolute;
  left: 32px;
  bottom: 30px;
  font-family: "Manrope", sans-serif;
  font-size: clamp(1.1rem, 2.2vw, 2rem);
  line-height: 1.1;
  letter-spacing: 0.08em;
  z-index: 2;
}

.floating-note {
  position: absolute;
  right: -28px;
  bottom: 55px;
  width: 220px;
  background: var(--bone);
  padding: 24px;
  box-shadow: 0 18px 60px rgba(0,0,0,.12);
}

.floating-note span {
  color: var(--warm);
  font-size: 0.78rem;
}

.floating-note p {
  margin-top: 28px;
  font-family: "Manrope", sans-serif;
  line-height: 1.3;
}

.statement {
  padding: 130px clamp(24px, 5vw, 80px);
  display: grid;
  grid-template-columns: 0.35fr 1.65fr;
  gap: 50px;
  border-top: 1px solid var(--line);
}

.section-number {
  font-size: 0.72rem;
  letter-spacing: 0.14em;
  color: var(--muted);
}

.statement-content h2 {
  font-size: clamp(2.4rem, 5vw, 5rem);
  max-width: 1100px;
}

.statement-grid {
  margin-top: 56px;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 60px;
  max-width: 960px;
  color: var(--muted);
}

.manifesto {
  background: var(--ink);
  color: var(--bone);
  overflow: hidden;
  padding: 25px 0;
}

.manifesto-track {
  width: max-content;
  display: flex;
  gap: 34px;
  align-items: center;
  font-family: "Manrope", sans-serif;
  font-size: clamp(1rem, 2.2vw, 1.7rem);
  letter-spacing: 0.08em;
  animation: marquee 20s linear infinite;
}

.manifesto-track i {
  color: var(--warm);
  font-style: normal;
}

@keyframes marquee {
  from { transform: translateX(0); }
  to { transform: translateX(-33.333%); }
}

.section-shell {
  padding: 130px clamp(24px, 5vw, 80px);
}

.section-heading {
  display: grid;
  grid-template-columns: 1.2fr .8fr;
  gap: 80px;
  align-items: end;
  margin-bottom: 70px;
}

.section-heading h2,
.approach h2,
.contact h2 {
  font-size: clamp(2.6rem, 5vw, 5.2rem);
}

.section-heading > p {
  color: var(--muted);
  max-width: 480px;
}

.service-list {
  border-top: 1px solid var(--line);
}

.service-card {
  display: grid;
  grid-template-columns: 90px 1fr auto;
  gap: 30px;
  align-items: start;
  padding: 38px 0;
  border-bottom: 1px solid var(--line);
  transition: padding 0.25s ease;
}

.service-card:hover {
  padding-left: 14px;
}

.service-number {
  color: var(--warm);
  font-size: 0.8rem;
}

.service-card h3 {
  font-family: "Manrope", sans-serif;
  font-size: clamp(1.35rem, 2.4vw, 2.15rem);
  margin-bottom: 10px;
}

.service-card p {
  color: var(--muted);
  max-width: 700px;
}

.service-arrow {
  font-size: 1.4rem;
}

.approach {
  background: var(--bone);
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 10vw;
}

.approach-copy > p:last-child {
  color: var(--muted);
  max-width: 540px;
  margin-top: 34px;
}

.process-step {
  padding: 28px 0 36px;
  border-top: 1px solid var(--line);
  display: grid;
  grid-template-columns: 52px 150px 1fr;
  gap: 20px;
}

.process-step span {
  color: var(--warm);
  font-size: 0.8rem;
}

.process-step h3 {
  font-family: "Manrope", sans-serif;
  font-size: 1.3rem;
}

.process-step p {
  color: var(--muted);
}

.quote-section {
  min-height: 70vh;
  padding: 120px clamp(24px, 9vw, 150px);
  display: flex;
  align-items: center;
  justify-content: center;
  background:
    linear-gradient(rgba(16,16,15,.55), rgba(16,16,15,.55)),
    url("https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=1800&q=85") center/cover fixed;
}

.quote-section blockquote {
  color: white;
  max-width: 1100px;
  text-align: center;
  font-family: "Manrope", sans-serif;
  font-size: clamp(2rem, 4.6vw, 5rem);
  line-height: 1.12;
  letter-spacing: -0.035em;
}

.contact-card {
  background: var(--ink);
  color: var(--bone);
  padding: clamp(38px, 6vw, 88px);
  display: flex;
  justify-content: space-between;
  gap: 80px;
  align-items: flex-end;
}

.button-light {
  background: var(--bone);
  color: var(--ink);
  white-space: nowrap;
}

.contact-actions p {
  color: rgba(238,233,223,.62);
  font-size: 0.85rem;
  margin-top: 18px;
}

footer {
  min-height: 150px;
  padding: 30px clamp(24px, 5vw, 80px);
  border-top: 1px solid var(--line);
  display: grid;
  grid-template-columns: 1fr auto 1fr auto;
  align-items: center;
  gap: 30px;
  font-size: 0.77rem;
  letter-spacing: 0.09em;
}

.footer-links {
  display: flex;
  gap: 22px;
  justify-self: end;
}

.copyright {
  color: var(--muted);
}

.reveal {
  opacity: 0;
  transform: translateY(28px);
  transition: opacity 0.8s ease, transform 0.8s ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@media (max-width: 920px) {
  .site-nav {
    position: absolute;
    top: 92px;
    left: 0;
    right: 0;
    background: var(--paper);
    border-bottom: 1px solid var(--line);
    padding: 28px;
    flex-direction: column;
    align-items: flex-start;
    display: none;
  }

  .site-nav.open {
    display: flex;
  }

  .menu-toggle {
    display: grid;
    gap: 7px;
    cursor: pointer;
  }

  .menu-toggle span {
    width: 27px;
    height: 1px;
    background: var(--ink);
  }

  .hero,
  .statement,
  .approach {
    grid-template-columns: 1fr;
  }

  .hero {
    padding-top: 80px;
  }

  .hero-visual {
    min-height: 520px;
  }

  .floating-note {
    right: 18px;
  }

  .statement-grid,
  .section-heading {
    grid-template-columns: 1fr;
    gap: 30px;
  }

  .process-step {
    grid-template-columns: 42px 120px 1fr;
  }

  .contact-card {
    align-items: flex-start;
    flex-direction: column;
  }

  footer {
    grid-template-columns: 1fr 1fr;
  }

  .footer-links {
    justify-self: start;
  }
}

@media (max-width: 620px) {
  .site-header {
    height: 76px;
  }

  .site-nav {
    top: 76px;
  }

  .hero {
    min-height: auto;
  }

  .hero h1 {
    font-size: clamp(3rem, 15vw, 4.6rem);
  }

  .hero-actions {
    align-items: flex-start;
    flex-direction: column;
    gap: 22px;
  }

  .hero-visual,
  .image-panel {
    min-height: 430px;
  }

  .statement,
  .section-shell {
    padding-top: 92px;
    padding-bottom: 92px;
  }

  .statement-grid {
    grid-template-columns: 1fr;
  }

  .service-card {
    grid-template-columns: 46px 1fr;
  }

  .service-arrow {
    display: none;
  }

  .process-step {
    grid-template-columns: 35px 1fr;
  }

  .process-step p {
    grid-column: 2;
  }

  .quote-section {
    background-attachment: scroll;
  }

  .button-light {
    white-space: normal;
  }

  footer {
    grid-template-columns: 1fr;
  }

  .footer-links {
    justify-self: start;
  }
}
