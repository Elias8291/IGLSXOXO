<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>El Calvario — El precio de tu libertad</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons+Outlined" rel="stylesheet"/>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            bg: "#ffffff",
            surface: "#f8fafc",
            ink: "#0f172a",
            muted: "#64748b",
            accent: "#2563eb",
            accent2: "#3b82f6",
            glow: "#60a5fa",
            light: "#dbeafe",
          },
          fontFamily: {
            heading: ["Sora", "system-ui", "sans-serif"],
            body: ["Space Grotesk", "system-ui", "sans-serif"],
          },
        },
      },
    };
  </script>
  <style>
    * { -webkit-tap-highlight-color: transparent; }

    /* Gradient animation */
    @keyframes gradient-shift {
      0%, 100% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
    }
    .gradient-bg {
      background: linear-gradient(-45deg, #eff6ff, #dbeafe, #f0f9ff, #e0f2fe);
      background-size: 400% 400%;
      animation: gradient-shift 12s ease infinite;
    }

    /* Floating orbs */
    @keyframes float-1 {
      0%, 100% { transform: translate(0, 0) scale(1); }
      33% { transform: translate(30px, -40px) scale(1.1); }
      66% { transform: translate(-20px, 20px) scale(0.9); }
    }
    @keyframes float-2 {
      0%, 100% { transform: translate(0, 0) scale(1); }
      33% { transform: translate(-40px, 30px) scale(0.95); }
      66% { transform: translate(25px, -25px) scale(1.05); }
    }
    .orb-1 { animation: float-1 8s ease-in-out infinite; }
    .orb-2 { animation: float-2 10s ease-in-out infinite; }

    /* Fade-in on scroll */
    .reveal {
      opacity: 0;
      transform: translateY(40px);
      transition: opacity 0.8s cubic-bezier(0.16, 1, 0.3, 1), transform 0.8s cubic-bezier(0.16, 1, 0.3, 1);
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* Stagger children */
    .reveal-stagger > * { opacity: 0; transform: translateY(30px); transition: opacity 0.6s ease, transform 0.6s ease; }
    .reveal-stagger.visible > *:nth-child(1) { transition-delay: 0.05s; opacity: 1; transform: translateY(0); }
    .reveal-stagger.visible > *:nth-child(2) { transition-delay: 0.15s; opacity: 1; transform: translateY(0); }
    .reveal-stagger.visible > *:nth-child(3) { transition-delay: 0.25s; opacity: 1; transform: translateY(0); }
    .reveal-stagger.visible > *:nth-child(4) { transition-delay: 0.35s; opacity: 1; transform: translateY(0); }

    /* Pulse glow */
    @keyframes pulse-glow {
      0%, 100% { box-shadow: 0 0 20px rgba(37,99,235,0.25); }
      50% { box-shadow: 0 0 40px rgba(37,99,235,0.4); }
    }
    .glow-pulse { animation: pulse-glow 3s ease-in-out infinite; }

    /* Marquee */
    @keyframes marquee {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }
    .marquee-track { animation: marquee 20s linear infinite; }

    /* Card hover */
    .card-hover {
      transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.4s ease;
    }
    .card-hover:hover {
      transform: translateY(-6px);
      box-shadow: 0 20px 60px rgba(37,99,235,0.1);
    }

    /* Glass light */
    .glass {
      background: rgba(255,255,255,0.7);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
      border: 1px solid rgba(15,23,42,0.06);
    }

    /* Splash inicial */
    #splash-inicial {
      position: fixed;
      inset: 0;
      z-index: 9999;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background: linear-gradient(180deg, #1e40af 0%, #2563eb 50%, #3b82f6 100%);
      transition: opacity 0.6s ease, visibility 0.6s ease;
      cursor: pointer;
      padding: 2rem;
    }
    #splash-inicial.is-hidden {
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
    }
    #splash-inicial .splash-logo {
      width: clamp(100px, 28vw, 160px);
      height: auto;
      margin-bottom: 1.5rem;
      filter: brightness(0) invert(1);
    }
    #splash-inicial .splash-text {
      font-family: Sora, system-ui, sans-serif;
      font-weight: 700;
      font-size: clamp(1rem, 3.5vw, 1.35rem);
      letter-spacing: 0.15em;
      color: #fff;
      text-align: center;
      line-height: 1.5;
      text-transform: uppercase;
    }
    #splash-inicial .splash-dios {
      font-size: clamp(1.5rem, 6vw, 2.5rem);
      margin-bottom: 0.5rem;
      letter-spacing: 0.15em;
      font-weight: 800;
      text-shadow: 0 2px 20px rgba(0,0,0,0.2);
    }
    #splash-inicial .splash-verso {
      font-size: clamp(0.85rem, 2.8vw, 1.05rem);
      color: rgba(255,255,255,0.95);
      text-align: center;
      line-height: 1.5;
      margin-bottom: 1.25rem;
      max-width: 320px;
      font-style: italic;
    }
    #splash-inicial .splash-verso cite {
      font-style: normal;
      font-weight: 600;
      letter-spacing: 0.05em;
      margin-top: 0.35rem;
      display: block;
    }
    #splash-inicial .splash-sub {
      font-size: clamp(0.75rem, 2.5vw, 0.95rem);
      letter-spacing: 0.2em;
      margin-top: 0.5rem;
      opacity: 0.95;
    }

    /* Modal fotos */
    #fotos-modal { transition: opacity 0.3s ease; opacity: 0; pointer-events: none; }
    #fotos-modal.is-open { opacity: 1; pointer-events: auto; }

    /* Smooth scroll */
    html { scroll-behavior: smooth; }
    body.modal-open { overflow: hidden; }

    /* Scrollbar */
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: #fff; }
    ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 3px; }
  </style>
</head>
<body class="bg-bg text-ink font-body antialiased overflow-x-hidden">

  <!-- ===================== SPLASH INICIAL ===================== -->
  <div id="splash-inicial" role="dialog" aria-label="Bienvenida El Calvario">
    <img src="logocalvario.png" alt="" class="splash-logo" aria-hidden="true"/>
    <p class="splash-text splash-dios">DIOS SIEMPRE ES BUENO</p>
    <p class="splash-verso">"Busquen al Señor mientras puede ser hallado, llámenlo en tanto que está cercano."<br><cite>— Isaías 55:6</cite></p>
  </div>

  <!-- ===================== HEADER ===================== -->
  <header class="fixed top-0 w-full z-50 glass shadow-sm">
    <div class="max-w-5xl mx-auto px-5 h-16 flex items-center justify-between">
      <a href="#" class="flex items-center gap-3">
        <img src="logocalvario.png" alt="" class="h-12 w-auto object-contain" aria-hidden="true"/>
        <span class="font-heading font-bold text-lg tracking-tight"><span class="text-accent">El</span> Calvario</span>
      </a>
      <nav class="hidden sm:flex items-center gap-8 text-sm text-muted">
        <a href="#cultos" class="hover:text-ink transition-colors">Cultos</a>
        <a href="#testimonios" class="hover:text-ink transition-colors">Testimonios</a>
        <a href="#ubicacion" class="hover:text-ink transition-colors">Ubicación</a>
      </nav>
      <button type="button" class="sm:hidden p-2" aria-label="Menú">
        <span class="material-icons-outlined text-2xl text-ink">menu</span>
      </button>
    </div>
  </header>

  <!-- ===================== HERO ===================== -->
  <section class="gradient-bg relative min-h-screen flex items-center justify-center text-center px-5 overflow-hidden">
    <!-- Orbs -->
    <div class="orb-1 absolute w-72 h-72 rounded-full bg-accent/10 blur-[100px] top-20 -left-20 pointer-events-none"></div>
    <div class="orb-2 absolute w-96 h-96 rounded-full bg-glow/15 blur-[120px] bottom-10 -right-20 pointer-events-none"></div>

    <div class="relative z-10 max-w-2xl mx-auto">
      <p class="text-xs sm:text-sm font-medium tracking-[0.3em] uppercase text-accent mb-6 reveal">Iglesia El Calvario</p>
      <h1 class="font-heading text-4xl sm:text-6xl md:text-7xl font-extrabold leading-[0.95] tracking-tight text-ink reveal">
        El precio de<br>
        <span class="bg-gradient-to-r from-accent via-accent2 to-glow bg-clip-text text-transparent">tu libertad</span>
      </h1>
      <p class="mt-6 text-base sm:text-lg text-muted max-w-md mx-auto leading-relaxed reveal">
        Santa Cruz Xoxocotlán — Unidos en la fe, guiados por Dios, creciendo en su presencia.
      </p>
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mt-10 reveal">
        <a href="#cultos" class="px-8 py-3.5 bg-accent hover:bg-accent/90 text-white font-heading font-semibold text-sm tracking-wide rounded-full transition-all glow-pulse">
          Nuestros cultos
        </a>
        <a href="https://maps.app.goo.gl/FGp9ZFsvoCd7BZkh8" target="_blank" rel="noopener noreferrer" class="px-8 py-3.5 border border-ink/15 hover:border-ink/30 text-ink font-heading font-medium text-sm tracking-wide rounded-full transition-all hover:bg-ink/5 inline-flex items-center gap-2">
          <span class="material-icons-outlined text-lg">directions</span>
          Cómo llegar
        </a>
        <a href="#testimonios" class="px-8 py-3.5 border border-ink/15 hover:border-ink/30 text-ink font-heading font-medium text-sm tracking-wide rounded-full transition-all hover:bg-ink/5">
          Testimonios
        </a>
      </div>
    </div>

    <!-- Scroll indicator -->
    <div class="absolute bottom-8 left-1/2 -translate-x-1/2 flex flex-col items-center gap-2 text-muted/50 animate-bounce">
      <span class="material-icons-outlined text-xl">expand_more</span>
    </div>
  </section>

  <!-- ===================== MARQUEE ===================== -->
  <div class="bg-accent text-white py-3 overflow-hidden">
    <div class="marquee-track flex whitespace-nowrap">
      <span class="mx-8 text-xs font-medium tracking-[0.2em] uppercase">Domingos 4:00 PM — Reunión General</span>
      <span class="mx-8 text-xs opacity-40">+</span>
      <span class="mx-8 text-xs font-medium tracking-[0.2em] uppercase">Domingos 2:30 PM — Reuniones de Jóvenes</span>
      <span class="mx-8 text-xs opacity-40">+</span>
      <span class="mx-8 text-xs font-medium tracking-[0.2em] uppercase">El precio de tu libertad</span>
      <span class="mx-8 text-xs opacity-40">+</span>
      <span class="mx-8 text-xs font-medium tracking-[0.2em] uppercase">Domingos 4:00 PM — Reunión General</span>
      <span class="mx-8 text-xs opacity-40">+</span>
      <span class="mx-8 text-xs font-medium tracking-[0.2em] uppercase">Domingos 2:30 PM — Reuniones de Jóvenes</span>
      <span class="mx-8 text-xs opacity-40">+</span>
      <span class="mx-8 text-xs font-medium tracking-[0.2em] uppercase">El precio de tu libertad</span>
      <span class="mx-8 text-xs opacity-40">+</span>
    </div>
  </div>

  <!-- ===================== CULTOS ===================== -->
  <section id="cultos" class="py-24 px-5 bg-bg">
    <div class="max-w-4xl mx-auto">
      <div class="text-center mb-14 reveal">
        <span class="text-xs font-medium tracking-[0.3em] uppercase text-accent">Horarios</span>
        <h2 class="font-heading text-3xl sm:text-4xl font-bold mt-3 tracking-tight text-ink">Nuestros cultos</h2>
        <p class="text-muted text-sm mt-2">Toca un servicio para ver fotos</p>
      </div>
      <div class="grid sm:grid-cols-2 gap-5 reveal-stagger">
        <div class="bg-surface border border-ink/5 rounded-2xl p-8 card-hover group cursor-pointer" role="button" tabindex="0" onclick="openFotosModal('general')" onkeydown="if(event.key==='Enter')openFotosModal('general')" data-service="general">
          <div class="flex items-center gap-3 mb-4">
            <div class="w-12 h-12 rounded-xl bg-accent/10 flex items-center justify-center group-hover:bg-accent/20 transition-colors">
              <span class="material-icons-outlined text-accent text-2xl">groups</span>
            </div>
            <span class="text-xs font-medium tracking-[0.2em] uppercase text-muted">Domingo</span>
          </div>
          <h3 class="font-heading text-2xl font-bold text-ink">Reunión General</h3>
          <p class="mt-4 font-heading text-2xl font-extrabold bg-gradient-to-r from-accent to-glow bg-clip-text text-transparent">4:00 PM</p>
          <ul class="mt-5 space-y-2 text-sm text-ink/90">
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent text-base">check_circle</span> Adoración y alabanza</li>
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent text-base">check_circle</span> Predicación de la Palabra</li>
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent text-base">check_circle</span> Oración</li>
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent text-base">check_circle</span> Enseñanza bíblica</li>
          </ul>
          <p class="mt-6 pt-4 border-t border-ink/5 flex items-center justify-center gap-2 text-accent text-sm font-medium group-hover:gap-3 transition-all">
            <span class="material-icons-outlined text-lg">photo_library</span>
            Ver fotos del culto
          </p>
        </div>
        <div class="bg-surface border border-ink/5 rounded-2xl p-8 card-hover group cursor-pointer" role="button" tabindex="0" onclick="openFotosModal('jovenes')" onkeydown="if(event.key==='Enter')openFotosModal('jovenes')" data-service="jovenes">
          <div class="flex items-center gap-3 mb-4">
            <div class="w-12 h-12 rounded-xl bg-accent2/10 flex items-center justify-center group-hover:bg-accent2/20 transition-colors">
              <span class="material-icons-outlined text-accent2 text-2xl">bolt</span>
            </div>
            <span class="text-xs font-medium tracking-[0.2em] uppercase text-muted">Domingo</span>
          </div>
          <h3 class="font-heading text-2xl font-bold text-ink">Reuniones de Jóvenes</h3>
          <p class="text-muted text-sm mt-2 leading-relaxed">Actividades del Culto de Jóvenes.</p>
          <p class="mt-4 font-heading text-2xl font-extrabold bg-gradient-to-r from-accent2 to-accent bg-clip-text text-transparent">2:30 PM</p>
          <ul class="mt-5 space-y-2 text-sm text-ink/90">
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent2 text-base">check_circle</span> Reuniones dinámicas y constantes</li>
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent2 text-base">check_circle</span> Espacios de adoración y alabanza</li>
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent2 text-base">check_circle</span> Tardes de convivencia y recreación</li>
            <li class="flex items-center gap-2"><span class="material-icons-outlined text-accent2 text-base">check_circle</span> Estudio y enseñanza de la Palabra de Dios</li>
          </ul>
          <p class="mt-6 pt-4 border-t border-ink/5 flex items-center justify-center gap-2 text-accent2 text-sm font-medium group-hover:gap-3 transition-all">
            <span class="material-icons-outlined text-lg">photo_library</span>
            Ver fotos del culto
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================== MODAL FOTOS (carousel) ===================== -->
  <div id="fotos-modal" class="fixed inset-0 z-[100] flex items-center justify-center p-4 bg-ink/90" aria-modal="true" aria-label="Galería de fotos">
    <div class="relative w-full max-w-2xl">
      <button type="button" onclick="closeFotosModal()" class="absolute -top-12 right-0 w-10 h-10 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center text-white z-10" aria-label="Cerrar">
        <span class="material-icons-outlined">close</span>
      </button>
      <p id="fotos-modal-title" class="absolute -top-12 left-0 text-white font-heading font-bold text-lg z-10">Fotos</p>
      <div class="relative rounded-2xl overflow-hidden bg-ink shadow-2xl">
        <div id="fotos-viewport" class="overflow-hidden touch-pan-y">
          <div id="fotos-track" class="flex transition-transform duration-300 ease-out"></div>
        </div>
        <button type="button" onclick="fotosPrev()" class="absolute left-2 top-1/2 -translate-y-1/2 w-10 h-10 rounded-full bg-white/90 hover:bg-white flex items-center justify-center text-ink shadow-lg z-10" aria-label="Anterior">
          <span class="material-icons-outlined">chevron_left</span>
        </button>
        <button type="button" onclick="fotosNext()" class="absolute right-2 top-1/2 -translate-y-1/2 w-10 h-10 rounded-full bg-white/90 hover:bg-white flex items-center justify-center text-ink shadow-lg z-10" aria-label="Siguiente">
          <span class="material-icons-outlined">chevron_right</span>
        </button>
        <div class="absolute bottom-3 left-0 right-0 flex justify-center gap-2" id="fotos-dots"></div>
      </div>
    </div>
  </div>

  <!-- ===================== TESTIMONIOS ===================== -->
  <section id="testimonios" class="py-24 px-5 bg-surface relative overflow-hidden">
    <div class="orb-1 absolute w-64 h-64 rounded-full bg-glow/10 blur-[80px] -top-10 left-10 pointer-events-none"></div>
    <div class="max-w-4xl mx-auto relative z-10">
      <div class="text-center mb-14 reveal">
        <span class="text-xs font-medium tracking-[0.3em] uppercase text-accent">Vidas transformadas</span>
        <h2 class="font-heading text-3xl sm:text-4xl font-bold mt-3 tracking-tight text-ink">Testimonios</h2>
      </div>
      <div class="grid sm:grid-cols-2 gap-5 reveal-stagger">
        <blockquote class="bg-surface border border-ink/5 rounded-2xl p-7 card-hover relative">
          <span class="material-icons-outlined text-accent/15 text-5xl absolute top-5 right-5">format_quote</span>
          <p class="text-ink text-sm leading-relaxed relative z-10">"Dios siempre ha estado conmigo a pesar de todas las dificultades. Siempre ha sido fiel, nunca me ha dejado solo."</p>
          <footer class="mt-6 flex items-center gap-3 relative z-10">
            <div class="w-10 h-10 rounded-full bg-gradient-to-br from-accent to-accent2 flex items-center justify-center font-heading font-bold text-sm text-white">E</div>
            <div>
              <p class="text-sm font-semibold text-ink">Elias J.</p>
              <p class="text-xs text-muted">Miembro de la iglesia</p>
            </div>
          </footer>
        </blockquote>
        <blockquote class="bg-surface border border-ink/5 rounded-2xl p-7 card-hover relative">
          <span class="material-icons-outlined text-accent/15 text-5xl absolute top-5 right-5">format_quote</span>
          <p class="text-ink text-sm leading-relaxed relative z-10">"Gracias, Dios, por rescatarme cuando mis fuerzas no alcanzaban. Mi vida es hoy un regalo de Tu misericordia."</p>
          <footer class="mt-6 flex items-center gap-3 relative z-10">
            <div class="w-10 h-10 rounded-full bg-gradient-to-br from-accent2 to-glow flex items-center justify-center font-heading font-bold text-sm text-white">A</div>
            <div>
              <p class="text-sm font-semibold text-ink">Abisai J.</p>
              <p class="text-xs text-muted">Miembro de la iglesia</p>
            </div>
          </footer>
        </blockquote>
      </div>
    </div>
  </section>

  <!-- ===================== UBICACIÓN ===================== -->
  <section id="ubicacion" class="py-24 px-5 bg-bg relative">
    <div class="max-w-4xl mx-auto">
      <div class="bg-surface border border-ink/5 rounded-2xl p-8 sm:p-12 text-center reveal">
        <div class="w-16 h-16 rounded-full bg-accent/10 flex items-center justify-center mx-auto mb-6">
          <span class="material-icons-outlined text-accent text-3xl">place</span>
        </div>
        <span class="text-xs font-medium tracking-[0.3em] uppercase text-accent">Visítanos</span>
        <h2 class="font-heading text-2xl sm:text-3xl font-bold mt-3 tracking-tight text-ink">2da de Camino Antiguo</h2>
        <p class="text-muted mt-2 text-sm">71233 Los Ángeles, Oax.</p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mt-8">
          <a href="https://maps.app.goo.gl/FGp9ZFsvoCd7BZkh8" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-6 py-3 bg-accent/10 hover:bg-accent/15 text-accent rounded-full text-sm font-medium transition-colors">
            <span class="material-icons-outlined text-lg">map</span>
            Ver en Google Maps
          </a>
          <a href="https://maps.app.goo.gl/FGp9ZFsvoCd7BZkh8" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-6 py-3 border border-ink/10 hover:border-ink/20 text-ink rounded-full text-sm font-medium transition-colors">
            <span class="material-icons-outlined text-lg">directions</span>
            Cómo llegar
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================== FOOTER ===================== -->
  <footer class="border-t border-ink/5 py-10 pb-28 px-5 bg-bg">
    <div class="max-w-4xl mx-auto text-center">
      <p class="font-heading font-bold text-lg text-ink"><span class="text-accent">El</span> Calvario</p>
      <p class="text-muted text-xs mt-1">El precio de tu libertad</p>
      <p class="mt-5 text-xs text-muted/60">© 2025 Iglesia El Calvario — Santa Cruz Xoxocotlán, Oaxaca</p>
    </div>
  </footer>

  <!-- ===================== BOTTOM NAV (Mobile) ===================== -->
  <nav class="fixed bottom-0 left-0 right-0 glass bg-bg/95 shadow-[0_-1px_10px_rgba(0,0,0,0.05)] flex justify-around py-3 z-50 sm:hidden" aria-label="Navegación">
    <a href="#" class="flex flex-col items-center text-muted hover:text-accent transition-colors">
      <span class="material-icons-outlined text-[22px]">home</span>
      <span class="text-[9px] mt-1 font-medium">Inicio</span>
    </a>
    <a href="#cultos" class="flex flex-col items-center text-accent">
      <span class="material-icons-outlined text-[22px]">church</span>
      <span class="text-[9px] mt-1 font-semibold">Cultos</span>
    </a>
    <a href="#testimonios" class="flex flex-col items-center text-muted hover:text-accent transition-colors">
      <span class="material-icons-outlined text-[22px]">forum</span>
      <span class="text-[9px] mt-1 font-medium">Testimonios</span>
    </a>
    <a href="#ubicacion" class="flex flex-col items-center text-muted hover:text-accent transition-colors">
      <span class="material-icons-outlined text-[22px]">place</span>
      <span class="text-[9px] mt-1 font-medium">Ubicación</span>
    </a>
  </nav>

  <!-- ===================== SCRIPTS ===================== -->
  <script>
    (function () {
      var splash = document.getElementById('splash-inicial');
      if (!splash) return;
      function hideSplash() {
        splash.classList.add('is-hidden');
      }
      splash.addEventListener('click', hideSplash);
      splash.addEventListener('touchstart', hideSplash, { passive: true });
      setTimeout(hideSplash, 2500);
    })();

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) entry.target.classList.add('visible');
      });
    }, { threshold: 0.15 });
    document.querySelectorAll('.reveal, .reveal-stagger').forEach(el => observer.observe(el));

    const FOTOS_SETS = {
      general: [
        { src: 'ReunionG.jpg', alt: 'Reunión General — El Calvario' },
        { src: 'ReunionG2.jpg', alt: 'Reunión General — El Calvario' }
      ],
      jovenes: [
        { src: 'Jovenes2.jpg', alt: 'Reuniones de Jóvenes — El Calvario' },
        { src: 'jovenes1.jpg', alt: 'Reuniones de Jóvenes — El Calvario' }
      ]
    };

    let fotosTotal = 2;
    let fotosIndex = 0;
    const fotosTrack = document.getElementById('fotos-track');
    const fotosModal = document.getElementById('fotos-modal');
    const fotosTitle = document.getElementById('fotos-modal-title');
    const fotosDots = document.getElementById('fotos-dots');

    function updateFotosCarousel() {
      if (!fotosTrack) return;
      fotosTrack.style.transform = `translateX(-${fotosIndex * 100}%)`;
      fotosDots.querySelectorAll('button').forEach((btn, i) => {
        btn.className = i === fotosIndex ? 'w-8 h-2 rounded-full bg-accent' : 'w-2.5 h-2.5 rounded-full bg-white/40 hover:bg-white/60';
      });
    }

    function openFotosModal(service) {
      const set = FOTOS_SETS[service] || FOTOS_SETS.general;
      fotosTotal = set.length;
      fotosTitle.textContent = service === 'jovenes' ? 'Reuniones de Jóvenes — Fotos' : 'Reunión General — Fotos';

      fotosTrack.innerHTML = set.map(function (f) {
        return '<div class="w-full shrink-0 aspect-[4/3] bg-surface"><img src="' + f.src + '" alt="' + (f.alt || '') + '" class="w-full h-full object-cover"/></div>';
      }).join('');

      fotosDots.innerHTML = '';
      for (let i = 0; i < fotosTotal; i++) {
        const btn = document.createElement('button');
        btn.type = 'button';
        btn.className = i === 0 ? 'w-8 h-2 rounded-full bg-accent' : 'w-2.5 h-2.5 rounded-full bg-white/40 hover:bg-white/60';
        btn.setAttribute('aria-label', 'Ir a foto ' + (i + 1));
        btn.onclick = function () { fotosIndex = i; updateFotosCarousel(); };
        fotosDots.appendChild(btn);
      }

      fotosIndex = 0;
      updateFotosCarousel();
      fotosModal.classList.add('is-open');
      document.body.classList.add('modal-open');
    }

    function closeFotosModal() {
      fotosModal.classList.remove('is-open');
      document.body.classList.remove('modal-open');
    }

    function fotosPrev() { fotosIndex = (fotosIndex - 1 + fotosTotal) % fotosTotal; updateFotosCarousel(); }
    function fotosNext() { fotosIndex = (fotosIndex + 1) % fotosTotal; updateFotosCarousel(); }

    fotosModal.addEventListener('click', function (e) { if (e.target === fotosModal) closeFotosModal(); });
    document.addEventListener('keydown', function (e) { if (e.key === 'Escape' && fotosModal.classList.contains('is-open')) closeFotosModal(); });

    let touchStartX = 0;
    document.getElementById('fotos-viewport').addEventListener('touchstart', function (e) { touchStartX = e.touches[0].clientX; }, { passive: true });
    document.getElementById('fotos-viewport').addEventListener('touchend', function (e) {
      var diff = touchStartX - e.changedTouches[0].clientX;
      if (Math.abs(diff) > 50) diff > 0 ? fotosNext() : fotosPrev();
    }, { passive: true });
  </script>
</body>
</html>
