/* style.css */
:root {
  --slate-900: #0f172a;
  --slate-800: #1e293b;
  --slate-700: #334155;
  --white-soft: #f8fafc;
  --white: #ffffff;
  --accent: #2dd4bf; /* teal */
  --accent-dark: #14b8a6;
  --text-muted: #64748b;
  --radius: 12px;
  --max-width: 1100px;
}

* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  font-family: 'Inter', sans-serif;
  background: var(--white-soft);
  color: var(--slate-800);
  scroll-behavior: smooth;
  line-height: 1.6;
}

.accent { color: var(--accent-dark); }

/* Navbar */
#navbar {
  position: sticky;
  top: 0;
  width: 100%;
  background: rgba(15, 23, 42, 0.95);
  backdrop-filter: blur(6px);
  z-index: 1000;
  transition: box-shadow 0.3s ease;
}
#navbar.scrolled { box-shadow: 0 4px 20px rgba(0,0,0,0.15); }

.nav-container {
  max-width: var(--max-width);
  margin: 0 auto;
  padding: 16px 24px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo { color: var(--white); font-weight: 700; font-size: 1.2rem; }

.nav-links {
  list-style: none;
  display: flex;
  gap: 28px;
}

.nav-links a {
  color: var(--white-soft);
  text-decoration: none;
  font-weight: 500;
  font-size: 0.95rem;
  position: relative;
  transition: color 0.2s ease;
}
.nav-links a::after {
  content: '';
  position: absolute;
  bottom: -4px; left: 0;
  width: 0; height: 2px;
  background: var(--accent);
  transition: width 0.25s ease;
}
.nav-links a:hover { color: var(--accent); }
.nav-links a:hover::after { width: 100%; }

/* Hero */
.hero {
  background: linear-gradient(135deg, var(--slate-900), var(--slate-700));
  color: var(--white);
  padding: 120px 24px;
  text-align: center;
}
.hero-content { max-width: 700px; margin: 0 auto; }
.hero-eyebrow {
  text-transform: uppercase;
  letter-spacing: 2px;
  font-size: 0.85rem;
  color: var(--accent);
  font-weight: 600;
  margin-bottom: 12px;
}
.hero h1 { font-size: 2.75rem; font-weight: 800; margin-bottom: 18px; }
.hero-tagline { font-size: 1.1rem; color: #cbd5e1; margin-bottom: 32px; }

.btn-primary {
  display: inline-block;
  background: var(--accent);
  color: var(--slate-900);
  padding: 14px 32px;
  border-radius: var(--radius);
  text-decoration: none;
  font-weight: 700;
  transition: transform 0.2s ease, background 0.2s ease;
}
.btn-primary:hover { background: var(--accent-dark); transform: translateY(-2px); }

.btn-secondary {
  display: inline-block;
  border: 2px solid var(--slate-800);
  color: var(--slate-800);
  padding: 12px 28px;
  border-radius: var(--radius);
  text-decoration: none;
  font-weight: 600;
  transition: all 0.2s ease;
}
.btn-secondary:hover { background: var(--slate-800); color: var(--white); }

/* Sections */
.section { padding: 90px 24px; }
.section-alt { background: var(--white); }
.section-container { max-width: var(--max-width); margin: 0 auto; }
.section-title {
  font-size: 2rem;
  font-weight: 700;
  margin-bottom: 40px;
  position: relative;
  display: inline-block;
}
.section-title::after {
  content: '';
  position: absolute;
  bottom: -10px; left: 0;
  width: 50px; height: 4px;
  background: var(--accent);
  border-radius: 2px;
}

.about-text { max-width: 700px; font-size: 1.05rem; color: var(--slate-700); }

/* Skills */
.skills-grid { display: flex; flex-wrap: wrap; gap: 12px; }
.skill-tag {
  background: var(--slate-900);
  color: var(--white);
  padding: 10px 18px;
  border-radius: 999px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: transform 0.2s ease, background 0.2s ease;
}
.skill-tag:hover { background: var(--accent-dark); transform: translateY(-3px); }

/* Timeline */
.timeline { position: relative; padding-left: 30px; border-left: 2px solid #e2e8f0; }
.timeline-item { position: relative; margin-bottom: 40px; }
.timeline-item:last-child { margin-bottom: 0; }
.timeline-dot {
  position: absolute;
  left: -37px; top: 4px;
  width: 14px; height: 14px;
  background: var(--accent);
  border-radius: 50%;
  border: 3px solid var(--white-soft);
}
.timeline-content h3 { font-size: 1.1rem; margin-bottom: 4px; }
.timeline-meta { display: block; font-size: 0.85rem; color: var(--text-muted); margin-bottom: 8px; }
.timeline-content p { color: var(--slate-700); font-size: 0.97rem; }

/* Projects */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 24px;
}
.project-card {
  background: var(--white-soft);
  border: 1px dashed #cbd5e1;
  border-radius: var(--radius);
  padding: 28px;
  transition: transform 0.2s ease, border-color 0.2s ease;
}
.project-card:hover { transform: translateY(-4px); border-color: var(--accent); }
.project-card h3 { margin-bottom: 8px; color: var(--slate-800); }
.project-card p { color: var(--text-muted); font-size: 0.92rem; }

/* Contact */
.contact-container { text-align: center; }
.contact-text { color: var(--text-muted); margin-bottom: 28px; }
.contact-links { display: flex; gap: 16px; justify-content: center; }

footer {
  background: var(--slate-900);
  color: #94a3b8;
  text-align: center;
  padding: 24px;
  font-size: 0.85rem;
}

/* Mobile-first responsive tweaks */
@media (max-width: 640px) {
  .nav-links { gap: 14px; }
  .nav-links a { font-size: 0.85rem; }
  .hero { padding: 90px 20px; }
  .hero h1 { font-size: 2rem; }
  .section { padding: 60px 20px; }
  .contact-links { flex-direction: column; align-items: center; }
}
