<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nicole Alexandra Galdós Champi</title>
  <style>
    :root {
      --color-principal: #6a5acd;
      --color-secundario: #e6e6fa;
      --color-fondo: #fdfdff;
      --color-texto: #333;
      --color-boton: #4b0082;
      --color-hover: #7b68ee;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--color-fondo);
      color: var(--color-texto);
    }

    header {
      background: linear-gradient(to right, var(--color-principal), var(--color-hover));
      color: white;
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    section {
      background-color: white;
      margin: 20px auto;
      padding: 20px;
      max-width: 850px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: var(--color-principal);
      margin-top: 0;
    }

    ul {
      padding-left: 20px;
    }

    a {
      color: var(--color-boton);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
      color: var(--color-hover);
    }

    .gmail-button, .linkedin-button {
      display: inline-flex;
      align-items: center;
      background-color: var(--color-boton);
      color: white;
      padding: 10px 15px;
      margin: 10px 10px 0 0;
      border-radius: 8px;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .gmail-button:hover, .linkedin-button:hover {
      background-color: var(--color-hover);
    }

    svg {
      margin-right: 8px;
    }

    @media (max-width: 600px) {
      body {
        font-size: 16px;
      }

      section {
        margin: 10px;
        padding: 15px;
      }

      .gmail-button, .linkedin-button {
        flex-direction: row;
        width: 100%;
        justify-content: center;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Nicole Alexandra Galdós Champi</h1>
</header>

<section id="sobre-mi">
  <h2>Sobre mí</h2>
  <p>
    Tengo <strong>20 años</strong> y estudio la carrera de Contabilidad en la
    <a href="https://ucsp.edu.pe/" target="_blank">Universidad Católica San Pablo</a>. Me considero una persona creativa, responsable y con ganas de aprender cosas nuevas.
  </p>
</section>

<section id="cursos">
  <h2>Cursos que llevé</h2>
  <ul>
    <li>Matemática básica</li>
    <li>Comunicación</li>
    <li>Contabilidad básica</li>
    <li>Contabilidad intermedia</li>
    <li>Contabilidad superior</li>
    <li>IVU</li>
    <li>Economía</li>
    <li>Legislación laboral</li>
    <li>Pensamiento Crítico e Innovación</li>
    <li>Álgebra</li>
    <li>Cálculo</li>
    <li>Microeconomía</li>
    <li>Música</li>
    <li>Apreciación Literaria</li>
    <li>
      Pensamiento Computacional con el profesor 
      <a href="https://www.linkedin.com/in/ecuadrosv" target="_blank">
        Ernesto Cuadros Vargas
      </a>
    </li>
  </ul>
</section>

<section id="compañeros">
  <h2>Mis compañeros de grupo</h2>
  <ul>
    <li><a href="https://ruthmerybg.github.io/RuthMeryBarrigaVera/" target="_blank">Ruth Meri Barriga Vera</a></li>
    <li><a href="https://betsy0702.github.io/Betsy-Leyla-Diaz-Quispe/" target="_blank">Betsy Leyla Díaz Quispe</a></li>
    <li><a href="https://mariaelena.neocities.org/" target="_blank">Maria Elena Machuca Ramos</a></li>
    <li><a href="https://franklinhilarion.github.io/franklinhilarion/" target="_blank">Jesús Franklin Hilarión Gallegos</a></li>
    <li><a href="https://mariafernandaapazameza.github.io/Maria-Fernanda-Apaza-Meza/" target="_blank">Maria Fernanda Apaza Meza</a></li>
  </ul>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <a class="gmail-button" href="mailto:nicole.galdos@ucsp.edu.pe" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" height="20" viewBox="0 0 512 512" fill="white">
      <path d="M502.3 190.8c6.6 5.2 9.7 13.6 7.8 21.7l-65.7 296.3c-1.9 8.1-9.4 13.2-17.5 12.5-7.1-.6-13.6-4.8-16.4-11.2L288 320 103.5 509.1c-5.7 6.3-14.5 7.6-21.7 3.1-7.2-4.6-10.4-13.6-7.4-21.4L140 320 14.4 212.5c-7.2-6.4-8.7-17-3.2-24.9 5.6-8 15.8-10.7 24.2-6.3L256 288l224.8-106.7c7.7-3.7 17.1-1.3 21.5 5.5z"/>
    </svg>
    nicole.galdos@ucsp.edu.pe
  </a>

  <a class="linkedin-button" href="https://www.linkedin.com/in/nicolealexandragaldoschampi-568387326" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" height="20" viewBox="0 0 448 512" fill="white">
      <path d="M100.28 448H7.4V148.9h92.88zm-46.44-338A53.66 53.66 0 1 1 107.5 56.34 53.66 53.66 0 0 1 53.84 110zM447.9 448h-92.4V302.4c0-34.7-.7-79.3-48.3-79.3-48.3 0-55.7 37.7-55.7 76.6V448h-92.4V148.9h88.7v40.8h1.3c12.4-23.5 42.7-48.3 87.9-48.3 94 0 111.3 61.9 111.3 142.3V448z"/>
    </svg>
    Mi LinkedIn
  </a>
</section>

</body>
</html>
