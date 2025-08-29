<div align="center">
  
  <!-- PORTADA NEÓN -->
  <img src="https://i.postimg.cc/zD2SXd46/Neon-Photo-Editor-20250828-223612454.png" alt="Portada BerMatModZ" width="100%" style="border-radius: 12px; border: 3px solid #00ffaa; box-shadow: 0 0 20px rgba(0, 255, 170, 0.4);"/>

  <br>

  <!-- FECHA COMPLETA: ej. jueves 28 de agosto de 2025 -->
  <div style="background: #000; color: #00ffaa; font-family: 'Courier New', monospace; font-size: 17px; font-weight: bold; padding: 12px 18px; border-radius: 10px; border: 2px solid #00ffaa; box-shadow: 0 0 15px rgba(0, 255, 170, 0.3); width: fit-content; margin: 15px auto;">
    <span id="fecha-completa" style="color: #00ffff; letter-spacing: 1px;">Cargando fecha...</span>
  </div>

  <!-- RELOJ EN TIEMPO REAL CON SEGUNDOS -->
  <div style="background: #001111; color: #00ffff; font-family: 'Courier New', monospace; font-size: 19px; font-weight: bold; padding: 8px 16px; border-radius: 8px; border: 1px solid #00ffff; box-shadow: 0 0 12px rgba(0, 255, 255, 0.2); width: fit-content; margin: 5px auto;">
    <span id="reloj-actual" style="letter-spacing: 3px;">00:00:00</span>
  </div>

  <script>
    // Actualizar fecha completa: jueves 28 de agosto de 2025 (sin duplicar el año)
    function actualizarFecha() {
      const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
      const fecha = new Date().toLocaleDateString('es-ES', options);
      // Capitalizar primera letra y evitar "del del"
      const fechaFormateada = fecha.charAt(0).toUpperCase() + fecha.slice(1);
      document.getElementById('fecha-completa').textContent = fechaFormateada;
    }

    // Actualizar reloj HH:MM:SS
    function actualizarReloj() {
      const now = new Date();
      const h = String(now.getHours()).padStart(2, '0');
      const m = String(now.getMinutes()).padStart(2, '0');
      const s = String(now.getSeconds()).padStart(2, '0');
      document.getElementById('reloj-actual').textContent = `${h}:${m}:${s}`;
    }

    // Actualizar cada segundo
    setInterval(() => { actualizarFecha(); actualizarReloj(); }, 1000);
    actualizarFecha(); // Iniciar ahora
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
    📍 <strong style="color: #00ffff;">Ubicación:</strong> Perú 🇵🇪<br>
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

<!-- ANIMACIÓN DE EMOJIS -->
<style>
  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-6px); }
  }
</style>
