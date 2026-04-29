<style>
  body { margin: 0; background: #080808; color: #f8f4ea; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif; }
  .lesajek-page { min-height: 100vh; padding: 32px 20px 56px; background: radial-gradient(circle at 20% 10%, rgba(212,175,55,.22), transparent 28%), linear-gradient(180deg, #080808, #151107); }
  .lesajek-wrap { max-width: 1080px; margin: 0 auto; }
  .lesajek-brand { display: flex; align-items: center; gap: 14px; margin-bottom: 32px; }
  .lesajek-brand img { width: 64px; height: 64px; border-radius: 18px; background: #fff; object-fit: cover; }
  .lesajek-brand strong { display: block; font-size: 22px; letter-spacing: .12em; text-transform: uppercase; }
  .lesajek-brand span { color: #f5d36c; font-size: 12px; font-weight: 800; letter-spacing: .16em; text-transform: uppercase; }
  .lesajek-hero { border: 1px solid rgba(212,175,55,.28); border-radius: 34px; padding: clamp(28px, 6vw, 64px); background: linear-gradient(135deg, rgba(255,255,255,.10), rgba(255,255,255,.035)); box-shadow: 0 30px 90px rgba(0,0,0,.42); display: grid; grid-template-columns: 1.1fr .9fr; gap: 32px; align-items: center; }
  .lesajek-kicker { display: inline-block; color: #f5d36c; font-size: 12px; font-weight: 900; letter-spacing: .14em; text-transform: uppercase; margin-bottom: 18px; }
  .lesajek-title { margin: 0; font-size: clamp(42px, 7vw, 82px); line-height: .95; letter-spacing: -.06em; }
  .lesajek-gold { color: #d4af37; }
  .lesajek-lead { max-width: 650px; color: #cfc5b3; font-size: clamp(17px, 2vw, 21px); line-height: 1.55; margin: 22px 0 0; }
  .lesajek-actions { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 30px; }
  .lesajek-btn { display: inline-flex; align-items: center; justify-content: center; min-height: 52px; padding: 14px 18px; border-radius: 15px; border: 1px solid rgba(255,255,255,.14); color: #f8f4ea !important; text-decoration: none !important; font-weight: 900; }
  .lesajek-btn-primary { background: linear-gradient(135deg, #f5d36c, #d4af37); color: #16100a !important; border: 0; }
  .lesajek-logo-card { width: min(340px, 82%); margin: 0 auto; border-radius: 36px; padding: 18px; background: rgba(255,255,255,.94); box-shadow: 0 34px 90px rgba(0,0,0,.44); transform: rotate(-2deg); }
  .lesajek-logo-card img { width: 100%; border-radius: 26px; }
  .lesajek-apps { padding-top: 72px; }
  .lesajek-apps h2 { font-size: clamp(32px, 5vw, 52px); line-height: 1; letter-spacing: -.045em; margin: 0 0 14px; }
  .lesajek-apps p { color: #cfc5b3; font-size: 18px; }
  .lesajek-grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 18px; margin-top: 28px; }
  .lesajek-card { border: 1px solid rgba(212,175,55,.28); border-radius: 24px; background: rgba(255,255,255,.06); padding: 24px; }
  .lesajek-card img { width: 78px; height: 78px; border-radius: 22px; background: #fff; object-fit: cover; }
  .lesajek-card h3 { font-size: 30px; margin: 22px 0 10px; }
  .lesajek-footer { padding-top: 34px; color: #9f9687; font-size: 14px; }
  @media (max-width: 850px) { .lesajek-hero, .lesajek-grid { grid-template-columns: 1fr; } .lesajek-actions { flex-direction: column; } .lesajek-btn { width: 100%; } }
</style>

<div class="lesajek-page">
  <div class="lesajek-wrap">
    <div class="lesajek-brand">
      <img src="/LOGO%20LESAJEK.png" alt="Logo de Lesajek">
      <div><strong>Lesajek</strong><span>Game Apps</span></div>
    </div>

    <section class="lesajek-hero">
      <div>
        <div class="lesajek-kicker">Apps para juegos clásicos</div>
        <h1 class="lesajek-title">Creamos apps simples para <span class="lesajek-gold">jugar mejor.</span></h1>
        <p class="lesajek-lead">Lesajek desarrolla aplicaciones modernas, claras y fáciles de usar para juegos de cartas y juegos clásicos: desde anotadores digitales hasta experiencias completas para jugar desde el celular.</p>
        <div class="lesajek-actions">
          <a class="lesajek-btn lesajek-btn-primary" href="#apps">Ver nuestras apps →</a>
          <a class="lesajek-btn" href="https://lesajek.com/anotador_de_bazas/support/">Soporte Anotador de Bazas</a>
        </div>
      </div>
      <div class="lesajek-logo-card"><img src="/LOGO%20LESAJEK.png" alt="Logo de Lesajek"></div>
    </section>

    <section class="lesajek-apps" id="apps">
      <h2>Un ecosistema para juegos clásicos.</h2>
      <p>Empezamos por las bazas y vamos a seguir construyendo herramientas para jugar, anotar, competir y disfrutar partidas de forma más cómoda.</p>
      <div class="lesajek-grid">
        <article class="lesajek-card">
          <img src="/anotador_de_bazas/assets/icon.png" alt="Anotador de Bazas">
          <h3>Anotador de Bazas</h3>
          <p>Una app pensada para anotar partidas presenciales de bazas de manera rápida, clara y sin errores.</p>
          <div class="lesajek-actions"><a class="lesajek-btn lesajek-btn-primary" href="https://lesajek.com/anotador_de_bazas/support/">Abrir soporte →</a></div>
        </article>
        <article class="lesajek-card">
          <img src="/LOGO%20LESAJEK.png" alt="Lesajek">
          <h3>Juego de Bazas</h3>
          <p>Próximamente: una app para jugar bazas directamente desde el celular, con una experiencia visual simple y clara.</p>
        </article>
      </div>
    </section>

    <div class="lesajek-footer">© 2026 Lesajek. Todos los derechos reservados.</div>
  </div>
</div>
