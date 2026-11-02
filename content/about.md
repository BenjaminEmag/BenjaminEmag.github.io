---
title: "About"
description: ""
---

<!-- ─── Section 1: Intro ─────────────────────────── -->
<div class="about-intro">
  <img src="/img/headshot.jpg" alt="Benjamin Emag" class="about-headshot">
  <div class="about-intro-text">
    <h2>Hey, I'm Ben</h2>
    <p>I'm a software engineer with a game programming background. I graduated from Champlain College in May 2026 with a B.S. in Game Programming and a minor in Computer Science. I love architecting new systems, optimizing existing ones, and learning new things.</p>
  </div>
</div>

<!-- ─── Section 2: What I Do ─────────────────────── -->
<div class="about-section">
  <h2>What I Do</h2>
  <p>I specialize in gameplay systems, performance optimization, and building the foundational systems that make everyone's jobs easier. I've worked on everything from incremental OS simulators to flight sims with ML-powered autopilots to echolocation shaders for horror games.</p>
</div>

<!-- ─── Section 3: Background ─────────────────────── -->
<div class="about-section">
  <h2>Background</h2>
  <div class="about-cards">
    <div class="about-card">
      <h3>Experience</h3>
      <p>I interned at the Leahy Center for Digital Forensics &amp; Cybersecurity, building .NET tools for government clients. It gave me a solid foundation in software engineering practices that I carry into every project.</p>
    </div>
    <div class="about-card">
      <h3>Currently</h3>
      <p>Looking for software engineering and IT roles in the Burlington, VT area. Most recently I worked on <strong>FincrementalOS</strong>, my capstone: an incremental game where you manage a simulated OS to shoot fish and become as rich as possible.</p>
    </div>
  </div>
</div>

<style>
/* ── Section 1: Intro ── */
.about-intro {
  display: flex;
  align-items: flex-start;
  gap: 2.5rem;
  padding-bottom: 2.5rem;
  border-bottom: 1px solid rgba(128,128,128,0.18);
  margin-bottom: 2.5rem;
}

.about-headshot {
  width: 180px;
  border-radius: 12px;
  flex-shrink: 0;
  display: block;
}

.about-intro-text h2 {
  margin-top: 0;
  font-size: 1.6rem;
}

.about-intro-text p {
  margin: 0;
  opacity: 0.85;
  line-height: 1.7;
}

/* ── Section 2 & 3: generic ── */
.about-section {
  padding-bottom: 2.5rem;
  border-bottom: 1px solid rgba(128,128,128,0.18);
  margin-bottom: 2.5rem;
}

.about-section:last-child {
  border-bottom: none;
  margin-bottom: 0;
  padding-bottom: 0;
}

.about-section h2 {
  margin-top: 0;
}

.about-section > p {
  opacity: 0.85;
  line-height: 1.7;
  max-width: 680px;
}

/* ── Section 3: two-card row ── */
.about-cards {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.25rem;
}

.about-card {
  background: var(--alt-bg, #1a1a1a);
  border: 1px solid rgba(128,128,128,0.15);
  border-radius: 10px;
  padding: 1.25rem 1.4rem;
}

.about-card h3 {
  margin: 0 0 0.5rem;
  font-size: 1rem;
  color: var(--accent, #1f676b);
  text-transform: uppercase;
  letter-spacing: 0.06em;
  font-size: 0.8rem;
}

.about-card p {
  margin: 0;
  opacity: 0.82;
  font-size: 0.93rem;
  line-height: 1.65;
}

/* ── Mobile ── */
@media (max-width: 580px) {
  .about-intro {
    flex-direction: column;
    gap: 1.25rem;
  }

  .about-headshot {
    width: 130px;
  }

  .about-cards {
    grid-template-columns: 1fr;
  }
}
</style>
