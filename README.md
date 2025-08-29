<div align="center">
  
  <!-- PORTADA NEÓN -->
  <img src="https://i.postimg.cc/zD2SXd46/Neon-Photo-Editor-20250828-223612454.png" alt="Portada BerMatModZ" width="100%" style="border-radius: 12px; border: 3px solid #00ffaa; box-shadow: 0 0 20px rgba(0, 255, 170, 0.4);"/>

  <br>

  <!-- FECHA COMPLETA (ej: jueves 28 de agosto) -->
  <div style="background: #000; color: #00ffaa; font-family: 'Courier New', monospace; font-size: 17px; font-weight: bold; padding: 12px; border-radius: 10px; border: 2px solid #00ffaa; box-shadow: 0 0 15px rgba(0, 255, 170, 0.3); width: fit-content; margin: 15px auto; text-align: center;">
    <strong>📅</strong> <span id="fecha-completa" style="color: #00ffff; letter-spacing: 1px;">Cargando fecha...</span>
  </div>

  <!-- RELOJ CON SEGUNDOS (HH:MM:SS) -->
  <div style="background: #001111; color: #00ffaa; font-family: 'Courier New', monospace; font-size: 19px; font-weight: bold; padding: 10px 18px; border-radius: 8px; border: 1px solid #00ffff; box-shadow: 0 0 12px rgba(0, 255, 255, 0.2); width: fit-content; margin: 5px auto;">
    ⏰ <span id="reloj-actual" style="color: #00ffff; letter-spacing: 3px;">00:00:00</span>
  </div>

  <script>
    // Actualizar fecha completa: ej. jueves 28 de agosto
    function actualizarFecha() {
      const options = { 
        weekday: 'long', 
        year: 'numeric', 
        month: 'long', 
        day: 'numeric' 
      };
      const fecha = new Date().toLocaleDateString('es-ES', options);
      document.getElementById('fecha-completa').textContent = fecha.charAt(0).toUpperCase() + fecha.slice(1) + ' del ' + new Date().getFullYear();
    }

    // Actualizar reloj con segundos: HH:MM:SS
    function actualizarReloj() {
      const now = new Date();
      const horas = String(now.getHours()).padStart(2, '0');
      const minutos = String(now.getMinutes()).padStart(2, '0');
      const segundos = String(now.getSeconds()).padStart(2, '0');
      document.getElementById('reloj-actual').textContent = `${horas}:${minutos}:${segundos}`;
    }

    // Ejecutar inmediatamente y actualizar cada segundo
    setInterval(() => {
      actualizarFecha();
      actualizarReloj();
    }, 1000);

    // Iniciar al cargar
    actualizarFecha();
    actualizarReloj();
  </script>

  <br>

  <!-- TÍTULO PRINCIPAL -->
  <h1 style="color: #00ffff; text-shadow: 0 0 10px #00ffaa, 0 0 20px #00ffff; font-family: 'Courier New', monospace; font-weight: bold;">
    ╔════════════════════════════╗<br>
    👋 ¡HOLA, MUNDO! SOY <strong>Anth'Zz Berrocal</strong><br>
    <span style="color: #ff00ff;">⚡BerMatModZ🔥</span><br>
    ╚════════════════════════════╝
  </h1>

  <!-- EMOJIS MÓVILES -->
  <p style="font-size: 26px;">
    <span style="animation: float 3s ease-in-out infinite;">🤖</span>
    <span style="animation: float 4s ease-in-out infinite;">👽</span>
    <span style="animation: float 5s ease-in-out infinite;">🧑‍💻</span>
    <span style="animation: float 3.8s ease-in-out infinite;">⚡</span>
    <span style="animation: float 4.2s ease-in-out infinite;">🔥</span>
  </p>

  <!-- BIENVENIDA CON GIF -->
  <p style="font-family: 'Courier New', monospace; font-size: 16px; color: #00ffaa;">
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40"/> 
    <strong>Bienvenid@ al sistema de código infinito y mente hacker</strong>
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40"/>
  </p>

  <!-- INFO TERMINAL -->
  <div style="background: #000; color: #00ffaa; padding: 20px; border-radius: 10px; font-family: 'Courier New', monospace; font-size: 15px; width: 95%; max-width: 750px; border: 2px solid #00ffaa; box-shadow: 0 0 15px rgba(0, 255, 170, 0.2);">
    <strong>╔════════════════════════════════════════════════╗</strong><br>
    🧠 <strong style="color: #00ffff;">Desarrollador Full Stack</strong> | 100% autodidacta 📚<br>
    🛠️ <strong style="color: #00ffff;">Proyectos:</strong> Bots, Hacking ético, IA, Web 🤖<br>
    🧰 <strong style="color: #00ffff;">Herramientas:</strong> Termux, AIDE, GitHub, APIs, JS, Python 🐍<br>
    🖥️ <strong style="color: #00ffff;">Lenguajes:</strong> Java ☕, JavaScript, Python, HTML/CSS, Bash 🐧<br>
    🌐 <strong style="color: #00ffff;">Ciberseguridad:</strong> Análisis, Ethical Hacking, Forensics 🔍<br>
    📍 <strong style="color: #00ffff;">Ubicación:</strong> Perú 🇵🇪 | Zona Horaria: -5 UTC<br>
    <strong>╚════════════════════════════════════════════════╝</strong>
  </div>
</div>

---

<!-- REDES SOCIALES -->
<h2 align="center" style="color: #00ffaa;">╔═══════🔗 REDES SOCIALES 🔗═══════╗</h2>

<div align="center">
  <a href="https://github.com/BerMatMods" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-BerMatMods-black?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://t.me/BerMatMods" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-BerMatMods-blue?style=for-the-badge&logo=telegram"/>
  </a>
  <a href="https://wa.me/51937556459" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-937556459-25D366?style=for-the-badge&logo=whatsapp"/>
  </a>
  <a href="https://www.facebook.com/anthzzberrocal" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-AnthZz_Berrocal-1877F2?style=for-the-badge&logo=facebook"/>
  </a>
</div>

---

<!-- PROYECTOS DESTACADOS -->
<h2 align="center" style="color: #00ffaa;">╔═══════🚀 PROYECTOS DESTACADOS 🚀═══════╗</h2>

<ul align="center" style="font-family: 'Courier New', monospace;">
  <li><strong>⚡BerMat-Bot MD🔥</strong> - Bot de WhatsApp avanzado con IA, juegos y comandos de administración</li>
  <li><strong>BerMat_Mods</strong> - Repositorio con scripts, herramientas y exploits educativos</li>
  <li><strong>Clon de WhatsApp</strong> - Proyecto educativo en ciberseguridad y análisis de mensajería</li>
  <li><strong>Interfaz Hacking Anonymous</strong> - Terminal interactiva con efectos visuales estilo hacker</li>
  <li><strong>Página Web Profesional</strong> - Diseño ciberpunk con dark mode y animaciones sutiles</li>
</ul>

---

<!-- FRASE PERSONAL -->
<h2 align="center" style="color: #00ffff;">╔═════💡 FRASE PERSONAL 💡═════╗</h2>

<p align="center" style="font-style: italic; color: #00ffaa; font-family: 'Courier New', monospace; font-size: 16px;">
  🧠 “No nací para ser uno más del montón. Vine a sobresalir, a dejar huella y a demostrar que el conocimiento es poder.”
</p>
<p align="center" style="color: #aaa;">
  — <strong>Anth'Zz Berrocal ⚡BerMatModZ🔥</strong>
</p>

---

<!-- SOBRE MÍ -->
<h2 align="center" style="color: #00ffaa;">╔═════════👨‍💻 SOBRE MÍ 👨‍💻═════════╗</h2>

<p align="center" style="font-family: 'Courier New', monospace;">
  🔰 <strong>Alias:</strong> ⚡BerMatModZ🔥<br>
  🎓 <strong>Formación:</strong> 100% autodidacta<br>
  🧪 <strong>Experiencia:</strong> Bots, ciberseguridad, desarrollo web<br>
  💪 <strong>Mentalidad:</strong> Mente hacker, corazón de guerrero<br>
  🤖 <strong>Misión:</strong> Crear, innovar y dominar el código
</p>

---

<!-- CONTADOR DE VISITAS -->
<div align="center">
  <img src="https://profile-counter.glitch.me/BerMatMods/count.svg" alt="Contador de visitas" style="width: 300px; border-radius: 8px; margin: 10px; box-shadow: 0 0 10px rgba(0, 255, 255, 0.3);"/>
</div>

---

<!-- WHATSAPP INFO -->
<h2 align="center" style="color: #25D366;">╔════════💬 CHAT EN WHATSAPP 💬════════╗</h2>

<div align="center" style="background: #121212; padding: 15px; border-radius: 10px; border: 1px solid #25D366; font-family: 'Courier New', monospace; color: #e0f8ff; max-width: 600px; margin: 0 auto;">
  <p><strong>Chat on WhatsApp with:</strong> <span style="color: #25D366;">+51 937 556 459</span></p>
  <hr style="border: 1px dashed #25D366; width: 80%;">
  <p style="font-size: 13px; line-height: 1.6;">
    🔐 End-to-end encryption and privacy controls.<br>
    🌐 Message and call for free* around the world.<br>
    👥 Group messaging made easy.<br>
    🎉 Say it with stickers, voice, GIFs and more.<br>
    🛡️ Layers of protection to help you stay safe.<br>
    📸 Share photos, videos, voice notes on Status.<br>
    🔔 Stay updated on topics you care about.<br>
    ❓ Get help with anything.
  </p>
  <a href="https://wa.me/51937556459" target="_blank">
    <button style="background: #25D366; color: white; border: none; padding: 10px 20px; border-radius: 25px; font-weight: bold; cursor: pointer;">
      📱 CHATEAR AHORA
    </button>
  </a>
</div>

---

<!-- TELEGRAM INFO -->
<h2 align="center" style="color: #0088cc;">╔════════📩 CHAT EN TELEGRAM 📩════════╗</h2>

<div align="center" style="background: #0a1a2a; padding: 15px; border-radius: 10px; border: 1px solid #0088cc; font-family: 'Courier New', monospace; color: #cceeff; max-width: 600px; margin: 0 auto;">
  <p><strong>Conéctate con:</strong> <span style="color: #0088cc;">@BerMatMods</span></p>
  <hr style="border: 1px dashed #0088cc; width: 80%;">
  <p style="font-size: 13px; line-height: 1.6;">
    📥 Chat directo en Telegram<br>
    📦 Descarga disponible para Mac, Android, iOS<br>
    🔒 Cifrado de extremo a extremo<br>
    🤖 Ideal para desarrolladores y comunidades<br>
    📢 Actualizaciones en tiempo real<br>
    🧩 Soporte técnico y colaboraciones
  </p>
  <a href="https://t.me/BerMatMods" target="_blank">
    <button style="background: #0088cc; color: white; border: none; padding: 10px 20px; border-radius: 25px; font-weight: bold; cursor: pointer;">
      📬 ENVIAR MENSAJE
    </button>
  </a>
</div>

---

<!-- MENSAJE FINAL -->
<h2 align="center" style="color: #00ffff;">
  ╔══════════════════════════════════╗<br>
  👽 ¡Gracias por visitar mi perfil!<br>
  👨‍💻 Sigue mis proyectos y únete al movimiento<br>
  🚀 <strong>F.A.M.A</strong> - Fuerza Anónima de Mentes Avanzadas<br>
  ╚══════════════════════════════════╝
</h2>

<h3 align="center" style="color: #aaa; font-style: italic;">
  ═══════ By: BerMat_MD ═══════
</h3>

<!-- ANIMACIONES -->
<style>
  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-6px); }
  }
</style>
