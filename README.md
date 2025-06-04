<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GINZA Shield</title>
  
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Playfair+Display:wght@500;700&display=swap" rel="stylesheet">
  <style>
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
    }
    body, p, ul, input, textarea, button {
      font-family: 'Inter', sans-serif;
    }

    * {
      box-sizing: border-box;
    }
    body {
      font-family: Verdana, Geneva, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
      color: #1a1a1a;
      text-align: center;
      scroll-behavior: smooth;
    }
    header {
      background-color: #004d40;
      color: #004d40;
      padding: 40px 20px;
    }
    header h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
    }
    .tagline {
      color: #e53935;
      font-size: 1.2em;
    }
    .cta {
      padding: 40px 20px;
      background: #e0f2f1;
    }
    .cta h2 {
      font-size: 2em;
      margin-bottom: 0.5em;
    }
    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background-color: #004d40;
      color: #004d40;
      border-radius: 12px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }
    .button:hover {
      background-color: #00695c;
    }
    .contact {
      background: #f9f9f9;
      padding: 40px 20px;
    }
    .contact h2 {
      font-size: 1.8em;
      margin-bottom: 20px;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: 0 auto;
    }
    input, textarea {
      margin: 10px 0;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    button {
      background-color: #004d40;
      color: #004d40;
      border: none;
      padding: 12px;
      border-radius: 8px;
      cursor: pointer;
    }
    button:hover {
      background-color: #00695c;
    }
    .footer {
      background-color: #004d40;
      color: #004d40;
      padding: 30px 20px;
      text-align: center;
      font-size: 0.9em;
    }
    .footer a {
      color: #e0f2f1;
      margin: 0 10px;
      text-decoration: none;
    }
    .footer a:hover {
      text-decoration: underline;
    }
    .legal-info {
      display: none;
      padding: 20px;
      background: #f4f4f4;
      color: #333;
      font-size: 0.95em;
      max-width: 800px;
      margin: 0 auto;
      text-align: left;
    }
    .description {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      text-align: left;
    }
    .description h2 {
      font-size: 1.8em;
      margin-bottom: 16px;
      color: #004d40;
    }
    .description p {
      font-size: 1.1em;
      line-height: 1.6em;
    }
    ul {
      list-style-position: inside;
      padding: 0;
      max-width: 600px;
      margin: auto;
      text-align: left;
    }
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2em;
      }
      .tagline {
        font-size: 1em;
      }
      .cta h2, .description h2, .contact h2 {
        font-size: 1.5em;
      }
      .description, .cta, .contact {
        padding: 20px 10px;
      }
      .button {
        padding: 10px 18px;
        font-size: 0.95em;
      }
      input, textarea {
        font-size: 1em;
      }
    }
  </style>
  <script>
    function toggleLegal(id) {
      const el = document.getElementById(id);
      el.style.display = el.style.display === 'none' ? 'block' : 'none';
    }
  </script>
</head>
<body>
  
  <header>
  <div style="position: fixed; top: 10px; right: 10px; z-index: 1000;">
    <a href="https://zenith-landing.onrender.com/" target="_blank"
       style="background-color: #e53935; color: #004d40; padding: 10px 15px; border-radius: 8px;
       font-family: 'Inter', sans-serif; text-decoration: none; font-weight: 600; font-size: 0.85em;">
       Grupo The Ginza Protocol - Otros servicios jurídicos
    </a>
  </div>

  <h1>GINZA Shield</h1>
  <p class="tagline">el escudo normativo para tu inteligencia artificial</p>
</header>

  <section class="cta">
    <h2>Empieza a construir IA con garantías legales</h2>
    <p>Evalúa, documenta y mejora el cumplimiento de tu sistema de IA desde el primer momento.</p>
    <a href="#ventajas" class="button">Ventajas de contratar el servicio</a>
  </section>

  <section class="description">
    <h2>¿Qué es GINZA Shield?</h2>
    <p>
      GINZA Shield es una herramienta de evaluación legal y ética para sistemas de inteligencia artificial. 
      Ayuda a empresas, desarrolladores y entidades públicas a cumplir con el Reglamento Europeo de Inteligencia Artificial (AI Act) 
      desde la fase de diseño hasta la comercialización. La herramienta realiza una clasificación automática del nivel de riesgo, 
      sugiere medidas de mitigación, y genera un informe editable de conformidad normativa.
    </p>
    <p>
      Además, proporciona orientación sobre aspectos clave como la supervisión humana, la transparencia algorítmica y la protección de derechos fundamentales. 
      GINZA Shield es el aliado perfecto para cualquier organización que desee innovar con responsabilidad jurídica.
    </p>
  </section>

  <section id="ventajas" class="cta">
    <h2>Ventajas de contratar GINZA Shield</h2>
    <ul>
      <li>Clasificación automática del nivel de riesgo según el AI Act</li>
      <li>Informe de cumplimiento personalizado y exportable</li>
      <li>Recomendaciones prácticas para ajustar tu sistema de IA</li>
      <li>Validación profesional por expertos en regulación tecnológica</li>
      <li>Confianza jurídica frente a inversores, socios y autoridades</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Formulario de contacto</h2>
    <form action="mailto:info@theginzaprotocol.com" method="POST" enctype="text/plain">
      <input type="text" name="name" placeholder="Tu nombre" required />
      <input type="email" name="email" placeholder="Tu correo electrónico" required />
      <textarea name="message" placeholder="Cuéntanos sobre tu herramienta de IA" required></textarea>
      <button type="submit">Enviar por correo</button>
    </form>
  </section>

  <footer class="footer">
    <p>&copy; 2025 The Ginza Protocol. Todos los derechos reservados.</p>
    <div>
      <a href="https://zenith-landing.onrender.com/" target="_blank">Página principal</a> |
      <a href="javascript:void(0);" onclick="toggleLegal('aviso')">Aviso Legal</a> |
      <a href="javascript:void(0);" onclick="toggleLegal('privacidad')">Política de Privacidad</a>
    </div>
  </footer>

  <div id="aviso" class="legal-info">
    <h3>Aviso Legal</h3>
    <p>Esta web es titularidad de The Ginza Protocol. El uso de esta página implica la aceptación de nuestras condiciones generales. Para más información, puede contactarnos en info@theginzaprotocol.com.</p>
  </div>

  <div id="privacidad" class="legal-info">
    <h3>Política de Privacidad</h3>
    <p>Los datos personales recabados a través del formulario de contacto serán tratados con la finalidad de gestionar su solicitud. No se cederán datos a terceros, salvo obligación legal. Puede ejercer sus derechos en info@theginzaprotocol.com.</p>
  </div>
</body>
</html>

