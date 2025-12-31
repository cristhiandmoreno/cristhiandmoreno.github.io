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
          "La muerte es cada día en que uno no se es fiel a sí mismo"
        </p>
      </div>
    </div>


    <!-- Cuerpo del Texto -->
    <div class="article-body">
      <!-- Párrafo con Letra Capital -->
      <p class="drop-cap">
        “Al artista le dicen méndigo, y al bandido le dicen firma”. Se lo escuché a un rapero en el mío de Cali. Y eso funciona muy bien en nuestra sociedad: nos importa más quién dice las cosas que qué es lo que se está diciendo.
      </p>
      
      <p>
       Vivimos en la era de la conveniencia. Una opinión se vuelve dogma, una acusación en un tweet se vuelve un hecho, y una discusión de fondo se pierde si no encaja con lo que se quiere hablar.
      </p>

      <p>
      CristhianMoreno.com nace para ir en contra de esa corriente. Esto no es un espacio de verdades absolutas ni soluciones mágicas. Es un rincón para ciudadanos curiosos que prefieren una duda fundamentada sobre una respuesta somera, o lo que es lo mismo:  para los que no se conforman con las respuestas obvias.
      </p>
      <p>
       Aquí comparto guías prácticas para explorar lo cotidiano y reflexiones críticas sobre derecho, política y sociedad. Mi nombre es <strong>Cristhian Moreno</strong>, y soy un méndigo más, en una sociedad plagada de firmas.
      </p>
<!--

            <h3 class="section-header">Hoja de Ruta</h3>
      <ul class="styled-list">
        <li>
            <strong>Formación</strong><br>
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
      -->


      <!-- Footer / CTA -->
      <div class="cta-box">
        <p style="margin-bottom: 15px; font-size: 0.9rem; font-style: italic;">¿Interesado en el perfil profesional completo?</p>
        <a href="#" class="cta-btn">
          Descargar Curriculum Vitae
        </a>
      </div>

    </div>
</section>