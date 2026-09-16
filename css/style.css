/* ============ VARIÁVEIS (PALETA TERROSA) ============ */
:root {
  --off-white: #F7F3EC;
  --white: #FFFFFF;
  --beige: #E9DCC6;
  --beige-soft: #F2EADB;
  --brown: #6F5138;
  --brown-dark: #4E3A29;
  --terracotta: #C07A56;
  --terracotta-soft: #D9A583;
  --text: #3E332B;
  --text-muted: #857767;
  --border: #E4D9C7;
  --shadow: 0 24px 60px -34px rgba(78, 58, 41, 0.45);
  --radius: 20px;
  --maxw: 1160px;
  --serif: 'Cormorant Garamond', serif;
  --sans: 'Jost', sans-serif;
}

* { margin: 0; padding: 0; box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  font-family: var(--sans);
  background: var(--off-white);
  color: var(--text);
  line-height: 1.7;
  font-weight: 300;
  -webkit-font-smoothing: antialiased;
}

img { display: block; max-width: 100%; }
a { color: inherit; text-decoration: none; }

.container { width: 100%; max-width: var(--maxw); margin: 0 auto; padding: 0 24px; }

/* ============ TIPOGRAFIA / ETIQUETAS ============ */
.eyebrow {
  display: inline-block;
  font-size: 0.78rem;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  font-weight: 500;
}
.eyebrow--center { text-align: center; }

.section { padding: 96px 0; }
.section__title {
  font-family: var(--serif);
  font-weight: 600;
  font-size: clamp(2rem, 4vw, 3rem);
  color: var(--brown-dark);
  line-height: 1.15;
  margin: 14px 0 18px;
}

/* ============ BOTÕES ============ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  padding: 15px 30px;
  border-radius: 999px;
  font-family: var(--sans);
  font-size: 0.95rem;
  font-weight: 500;
  letter-spacing: 0.02em;
  cursor: pointer;
  border: 1px solid transparent;
  transition: transform .25s ease, box-shadow .25s ease, background .25s ease, color .25s ease;
}
.btn:hover { transform: translateY(-2px); }
.btn--primary {
  background: var(--brown);
  color: var(--white);
  box-shadow: 0 16px 30px -18px rgba(78,58,41,.7);
}
.btn--primary:hover { background: var(--brown-dark); }
.btn--whatsapp {
  background: var(--white);
  color: var(--brown);
  border-color: var(--border);
}
.btn--whatsapp:hover { border-color: var(--terracotta); color: var(--terracotta); }
.btn--block { width: 100%; }

/* ============ NAVEGAÇÃO ============ */
.nav {
  position: sticky; top: 0; z-index: 50;
  background: rgba(247, 243, 236, 0.85);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid var(--border);
}
.nav__inner { display: flex; align-items: center; justify-content: space-between; height: 72px; }
.nav__brand { font-family: var(--serif); font-size: 1.5rem; font-weight: 600; color: var(--brown-dark); }
.nav__links { display: flex; align-items: center; gap: 30px; }
.nav__links a { font-size: 0.95rem; color: var(--text); transition: color .2s; }
.nav__links a:hover { color: var(--terracotta); }
.nav__cta {
  background: var(--brown); color: var(--white);
  padding: 10px 22px; border-radius: 999px; font-weight: 500;
}
.nav__cta:hover { background: var(--brown-dark); color: var(--white); }

/* ============ HERO ============ */
.hero { padding: 70px 0 90px; }
.hero__inner {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 60px;
  align-items: center;
}
.hero__photo {
  position: relative;
  border-radius: 240px 240px var(--radius) var(--radius);
  overflow: hidden;
  background: var(--beige);
  box-shadow: var(--shadow);
  aspect-ratio: 4 / 5;
}
.hero__photo::after {
  content: "";
  position: absolute; inset: 0;
  border-radius: inherit;
  box-shadow: inset 0 0 0 1px rgba(255,255,255,.4);
}
.hero__photo img { width: 100%; height: 100%; object-fit: cover; }
.hero__name {
  font-family: var(--serif);
  font-size: clamp(2.6rem, 6vw, 4rem);
  font-weight: 600;
  color: var(--brown-dark);
  line-height: 1.05;
  margin: 10px 0 18px;
}
.hero__phrase {
  font-family: var(--serif);
  font-size: clamp(1.25rem, 2.4vw, 1.7rem);
  color: var(--terracotta);
  font-weight: 500;
  margin-bottom: 16px;
}
.hero__text { color: var(--text-muted); font-size: 1.05rem; margin-bottom: 30px; max-width: 46ch; }
.hero__actions { display: flex; flex-wrap: wrap; gap: 16px; }

/* ============ SOBRE ============ */
.sobre { background: var(--white); }
.sobre__inner { max-width: 820px; margin: 0 auto; text-align: center; }
.sobre__text { margin-top: 28px; }
.sobre__text p { color: var(--text); margin-bottom: 18px; font-size: 1.08rem; }
.sobre__destaque {
  font-family: var(--serif);
  font-size: 1.5rem;
  color: var(--brown);
  font-weight: 600;
  margin-top: 26px;
}

/* ============ CARDS (COMO POSSO TE AJUDAR) ============ */
.ajuda { background: var(--off-white); }
.ajuda .section__title { text-align: center; }
.ajuda__grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 24px;
  margin-top: 48px;
}
.card {
  background: var(--white);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 34px 28px;
  transition: transform .3s ease, box-shadow .3s ease, border-color .3s ease;
}
.card:hover { transform: translateY(-6px); box-shadow: var(--shadow); border-color: var(--terracotta-soft); }
.card__icon {
  width: 54px; height: 54px;
  display: grid; place-items: center;
  border-radius: 16px;
  background: var(--beige-soft);
  color: var(--terracotta);
  margin-bottom: 20px;
}
.card__icon svg { width: 28px; height: 28px; }
.card h3 { font-family: var(--serif); font-size: 1.45rem; font-weight: 600; color: var(--brown-dark); margin-bottom: 10px; }
.card p { color: var(--text-muted); font-size: 0.98rem; }

/* ============ COMO FUNCIONA ============ */
.funciona { background: var(--white); }
.funciona .section__title { text-align: center; }
.funciona__steps {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 24px;
  margin-top: 52px;
}
.step { text-align: center; padding: 0 10px; position: relative; }
.step__num {
  display: inline-grid; place-items: center;
  width: 56px; height: 56px;
  border-radius: 50%;
  background: var(--brown);
  color: var(--white);
  font-family: var(--serif);
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 18px;
}
.step h3 { font-family: var(--serif); font-size: 1.3rem; font-weight: 600; color: var(--brown-dark); margin-bottom: 8px; }
.step p { color: var(--text-muted); font-size: 0.95rem; }

/* ============ AGENDAMENTO ============ */
.agendamento { background: var(--beige-soft); }
.agendamento__intro { text-align: center; margin-bottom: 40px; }
.agendamento__lead { color: var(--text-muted); font-size: 1.1rem; }
.agendamento__panel {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 28px;
  background: var(--white);
  border: 1px solid var(--border);
  border-radius: 26px;
  padding: 34px;
  box-shadow: var(--shadow);
}

/* Calendário */
.cal { border: 1px solid var(--border); border-radius: var(--radius); padding: 22px; }
.cal__head { display: flex; align-items: center; justify-content: space-between; margin-bottom: 16px; }
.cal__month { font-family: var(--serif); font-size: 1.3rem; font-weight: 600; color: var(--brown-dark); text-transform: capitalize; }
.cal__nav {
  width: 38px; height: 38px; border-radius: 50%;
  border: 1px solid var(--border); background: var(--off-white);
  font-size: 1.2rem; color: var(--brown); cursor: pointer; transition: all .2s;
}
.cal__nav:hover { background: var(--brown); color: var(--white); border-color: var(--brown); }
.cal__week, .cal__grid { display: grid; grid-template-columns: repeat(7, 1fr); gap: 6px; }
.cal__week span { text-align: center; font-size: 0.72rem; color: var(--text-muted); padding-bottom: 8px; }
.cal__day {
  aspect-ratio: 1;
  display: grid; place-items: center;
  border-radius: 12px;
  font-size: 0.92rem;
  color: var(--text);
  cursor: pointer;
  border: 1px solid transparent;
  transition: all .18s ease;
}
.cal__day:hover:not(.is-off) { background: var(--beige-soft); }
.cal__day.is-off { color: #cbbfae; cursor: not-allowed; }
.cal__day.is-today { border-color: var(--terracotta-soft); }
.cal__day.is-selected { background: var(--brown); color: var(--white); }
.cal__hint { margin-top: 14px; font-size: 0.85rem; color: var(--text-muted); text-align: center; }

/* Formulário */
.booking__label { display: block; font-size: 0.85rem; font-weight: 500; color: var(--brown); margin: 18px 0 8px; letter-spacing: 0.02em; }
.booking input {
  width: 100%;
  padding: 14px 16px;
  border: 1px solid var(--border);
  border-radius: 12px;
  background: var(--off-white);
  font-family: var(--sans);
  font-size: 0.98rem;
  color: var(--text);
  transition: border-color .2s, background .2s;
}
.booking input:focus { outline: none; border-color: var(--terracotta); background: var(--white); }
.booking__times { display: flex; flex-wrap: wrap; gap: 10px; }
.booking__time {
  padding: 10px 16px;
  border: 1px solid var(--border);
  border-radius: 999px;
  font-size: 0.9rem;
  cursor: pointer;
  background: var(--off-white);
  transition: all .18s;
}
.booking__time:hover { border-color: var(--terracotta); }
.booking__time.is-selected { background: var(--brown); color: var(--white); border-color: var(--brown); }
.booking .btn--primary { margin-top: 26px; }
.booking__msg { margin-top: 14px; font-size: 0.92rem; color: var(--terracotta); min-height: 1.2em; }
.booking__divider { display: flex; align-items: center; gap: 14px; margin: 26px 0 14px; color: var(--text-muted); font-size: 0.85rem; }
.booking__divider::before, .booking__divider::after { content: ""; height: 1px; background: var(--border); flex: 1; }
.booking__alt { text-align: center; color: var(--text); margin-bottom: 14px; }

/* ============ RODAPÉ ============ */
.footer { background: var(--brown-dark); color: var(--beige); }
.footer__inner {
  display: flex; align-items: center; justify-content: space-between;
  gap: 30px; padding: 60px 24px;
}
.footer__name { font-family: var(--serif); font-size: 1.8rem; font-weight: 600; color: var(--white); }
.footer__role { font-size: 0.95rem; color: var(--terracotta-soft); margin-top: 4px; }
.footer__desc { margin-top: 14px; max-width: 40ch; color: #d8c9b6; }
.footer__phone { margin-top: 8px; font-size: 0.95rem; }
.footer .btn--primary { background: var(--terracotta); }
.footer .btn--primary:hover { background: var(--terracotta-soft); color: var(--brown-dark); }
.footer__copy { border-top: 1px solid rgba(255,255,255,.12); padding: 18px 0; font-size: 0.85rem; color: #c9b8a3; text-align: center; }

/* ============ RESPONSIVO ============ */
@media (max-width: 900px) {
  .hero__inner { grid-template-columns: 1fr; gap: 40px; text-align: center; }
  .hero__media { order: -1; max-width: 380px; margin: 0 auto; }
  .hero__actions { justify-content: center; }
  .hero__text { margin-left: auto; margin-right: auto; }
  .funciona__steps { grid-template-columns: repeat(2, 1fr); gap: 36px 20px; }
  .agendamento__panel { grid-template-columns: 1fr; padding: 24px; }
  .footer__inner { flex-direction: column; text-align: center; }
}
@media (max-width: 560px) {
  .section { padding: 70px 0; }
  .nav__links a:not(.nav__cta) { display: none; }
  .funciona__steps { grid-template-columns: 1fr; }
  .hero__actions .btn { width: 100%; }
}
