---
layout: default
title: Sobre Mí
permalink: /about/
---

<!-- Estilos específicos para esta página (Estilo Periodístico) -->
<style>
  /* Contenedor principal estilo columna */
  .columnist-container {
    max-width: 800px;
    margin: 0 auto;
    padding: 40px 20px;
    font-family: inherit; /* Hereda tus fuentes actuales */
  }

  /* Cabecera tipo "Masthead" de periódico */
  .masthead {
    display: flex;
    align-items: center;
    border-bottom: 2px solid var(--green-h);
    padding-bottom: 30px;
    margin-bottom: 30px;
    gap: 30px;
  }

  .masthead-img {
    flex-shrink: 0;
    width: 180px;
    height: 180px;
  }

  .masthead-img img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 5px; /* Menos redondo, más foto de perfil de diario */
    border: 1px solid var(--text-color); /* Borde fino y elegante */
    box-shadow: 5px 5px 0px var(--green-h); /* Detalle de diseño moderno */
    filter: grayscale(20%); /* Un toque sobrio */
    transition: all 0.3s ease;
  }

  .masthead-img img:hover {
    filter: grayscale(0%);
    box-shadow: 2px 2px 0px var(--green-h);
    transform: translate(3px, 3px);
  }

  .masthead-info {
    flex-grow: 1;
  }

  .masthead-title {
    font-size: 3.5rem;
    line-height: 1;
    margin: 0 0 10px 0;
    font-weight: 700;
    letter-spacing: -1px;
  }

  .masthead-meta {
    font-size: 1.1rem;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--green-h);
    font-weight: bold;
    border-top: 1px solid #ccc;
    border-bottom: 1px solid #ccc;
    padding: 5px 0;
    display: inline-block;
    width: 100%;
  }

  /* Cuerpo del texto */
  .article-body {
    font-size: 1.25rem;
    line-height: 1.8;
    text-align: justify; /* Justificado como columna */
  }

  /* Letra Capital (Drop Cap) para persuación visual */
  .drop-cap::first-letter {
    font-size: 4.5rem;
    float: left;
    margin-top: -10px;
    margin-right: 10px;
    line-height: 0.8;
    color: var(--green-h);
    font-weight: bold;
  }

  /* Subtítulos estilo sección de diario */
  .section-header {
    font-size: 1.8rem;
    margin-top: 50px;
    margin-bottom: 20px;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    border-left: 5px solid var(--green-h);
    padding-left: 15px;
  }

  /* Listas limpias */
  .styled-list {
    list-style: none;
    padding: 0;
  }
  .styled-list li {
    margin-bottom: 15px;
    padding-bottom: 15px;
    border-bottom: 1px dotted #ccc;
  }
  .styled-list strong {
    color: var(--green-h);
  }

  /* Botón estilo "Call to Action" sobrio */
  .cta-box {
    margin-top: 60px;
    padding: 30px;
    border: 2px solid var(--text-color);
    text-align: center;
    background-color: transparent;
    transition: 0.3s;
  }
  
  .cta-box:hover {
    background-color: rgba(0,0,0,0.02);
  }

  .cta-btn {
    text-decoration: none;
    color: var(--text-color);
    font-weight: 900;
    text-transform: uppercase;
    letter-spacing: 2px;
    border-bottom: 2px solid var(--green-h);
    padding-bottom: 2px;
    transition: color 0.3s;
  }
  
  .cta-btn:hover {
    color: var(--green-h);
  }

  /* Responsive para móviles */
  @media (max-width: 768px) {
    .masthead {
      flex-direction: column;
      text-align: center;
      gap: 15px;
    }
    .masthead-title {
      font-size: 2.8rem;
    }
    .masthead-img {
      width: 150px;
      height: 150px;
    }
    .drop-cap::first-letter {
      font-size: 3.5rem;
    }
    .article-body {
        text-align: left; /* Justificado a veces falla en móviles */
    }
  }
</style>

<section class="columnist-container">
    
    <!-- Encabezado Estilo Periódico -->
    <div class="masthead">
      <div class="masthead-img">
        <img src="{{ site.data.authors.cristhian.avatar }}" alt="Cristhian Moreno">
      </div>
      <div class="masthead-info">
        <h1 class="masthead-title">Crist<span style="color: var(--green-h);">h</span>ian Moreno</h1>
        <div class="masthead-meta">
          Derecho &middot; Opinión &middot; Ciudadanía
        </div>
        <p style="margin-top: 15px; font-style: italic; opacity: 0.8;">
          "Lorem ipsum dolor sit amet"
        </p>
      </div>
    </div>

    <!-- Cuerpo del Texto -->
    <div class="article-body">
      <!-- Párrafo con Letra Capital -->
      <p class="drop-cap">
        Mi nombre es <strong>Cristhian Moreno</strong> y este blog nace de una convicción epistemológica: las instituciones deben servir a las personas, y no al revés. Mi objetivo no está encaminado en una línea recta, sino una constante búsqueda de respuestas. Como estudiante de Derecho, he decidido ponerle especial lupa a las desigualdades producto del desconocimiento jurídico.
      </p>
      
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>

      <h3 class="section-header">Visión Política</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>

      <h3 class="section-header">Hoja de Ruta</h3>
      <ul class="styled-list">
        <li>
            <strong>Formación Jurídica</strong><br>
            Estudiante de Derecho de la Universidad del Valle (En curso).
        </li>
        <li>
            <strong>Cursos</strong><br>
            Especialización en Recocha
        </li>
        <li>
            <strong>Pensamiento Escrito</strong><br>
            Inconformista
        </li>
      </ul>

      <!-- Footer / CTA -->
      <div class="cta-box">
        <p style="margin-bottom: 15px; font-size: 0.9rem; font-style: italic;">¿Interesado en el perfil profesional completo?</p>
        <a href="#" class="cta-btn">
          Descargar Curriculum Vitae
        </a>
      </div>

    </div>
</section>