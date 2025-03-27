<!--
  Archivo: README.md
  Descripción: Ejemplo con texto "neón" y animaciones en HTML/CSS embebido en Markdown.
-->

<!-- Para que este tipo de efectos funcione, el visualizador de Markdown debe permitir HTML y estilos internos. -->

<div style="width: 100%; background: black; padding: 20px; font-family: 'Courier New', Courier, monospace;">
  
  <!-- Encabezado con efecto "neón" -->
  <h1 style="
      color: #00FF00; 
      text-align: center;
      animation: neonFlicker 1.5s infinite alternate;
      font-size: 3em;
      margin: 0 0 20px 0;
  ">
    Neutronbomb23
  </h1>
  
  <!-- Texto parpadeante con efecto translúcido -->
  <p style="
      color: #00FF00;
      text-align: center;
      animation: blink 2s infinite;
      font-size: 1.2em;
      margin: 0 0 30px 0;
  ">
    Welcome to my GitHub profile.
  </p>

  <!-- Subtítulo con efecto de resplandor continuo -->
  <h2 style="
      color: #00FF00; 
      text-align: left;
      animation: glow 2s ease-in-out infinite alternate;
      font-size: 2em;
      margin: 20px 0 10px 0;
  ">
    Technical Expertise
  </h2>

  <ul style="color: #00FF00; margin-left: 20px;">
    <li><strong>Programming Languages:</strong> JavaScript, C++, C#, Java, HTML, CSS</li>
    <li><strong>Tools and Frameworks:</strong>
      <ul>
        <li><strong>Frameworks:</strong> openFrameworks, Phaser3</li>
        <li><strong>Game Engines:</strong> Unity</li>
        <li><strong>Libraries:</strong> SDL</li>
        <li><strong>Audio Engines:</strong> Audacity, FMOD</li>
        <li><strong>3D Design Tools:</strong> Blender</li>
        <li><strong>Mobile Development:</strong> Android Studio</li>
      </ul>
    </li>
  </ul>

  <h2 style="
      color: #00FF00; 
      animation: glow 2s ease-in-out infinite alternate;
      font-size: 2em;
      margin: 20px 0 10px 0;
  ">
    Contact
  </h2>

  <p style="color: #00FF00;">
    If you are interested in discussing potential collaborations or have any questions, feel free to reach out to me:
  </p>
  <ul style="color: #00FF00; margin-left: 20px;">
    <li><strong>Email:</strong> dorjeehb23@proton.me</li>
  </ul>

  <p style="
      color: #00FF00; 
      text-align: center;
      margin: 30px 0 0 0;
      font-style: italic;
      animation: glitch 3s infinite;
  ">
    Thank you for visiting my profile.
  </p>

</div>

<!-- Estilos CSS para las animaciones -->
<style>
  @keyframes neonFlicker {
    0% {
      text-shadow: 
        0 0 5px #00ff00, 
        0 0 10px #00ff00, 
        0 0 20px #00ff00;
    }
    50% {
      text-shadow: 
        0 0 10px #00ff00,
        0 0 20px #00ff00,
        0 0 30px #00ff00;
    }
    100% {
      text-shadow: 
        0 0 2px #00ff00, 
        0 0 4px #00ff00;
    }
  }

  @keyframes blink {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0.2;
    }
  }

  @keyframes glow {
    0% {
      text-shadow: 
        0 0 5px #00ff00,
        0 0 10px #00ff00,
        0 0 20px #00ff00;
    }
    100% {
      text-shadow: 
        0 0 20px #00ff00,
        0 0 40px #00ff00,
        0 0 60px #00ff00;
    }
  }

  /* Efecto de "glitch" sencillo */
  @keyframes glitch {
    0% {
      text-shadow: 
        2px 0 red,
        -2px 0 blue;
    }
    20% {
      text-shadow: 
        -2px 0 red,
        2px 0 blue;
    }
    40% {
      text-shadow: 
        2px 0 red,
        -2px 0 blue;
    }
    60% {
      text-shadow: 
        -2px 0 red,
        2px 0 blue;
    }
    80% {
      text-shadow: 
        2px 0 red,
        -2px 0 blue;
    }
    100% {
      text-shadow: 
        -2px 0 red,
        2px 0 blue;
    }
  }
</style>
