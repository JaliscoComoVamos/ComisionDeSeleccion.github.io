---
title: ""
feature_text: |
  # COMUNICADOS 2024
---

<style>
  :root{
    --bg-dark:#333333;
    --bg-light:#f0f0f0;
    --text-dark:#333;
    --border:#696969;
    --accent:#ffa500;
    --radius:12px;
    --gap:14px;
  }
  /* Contenedor general */
  .com-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(320px, 1fr));
    gap:var(--gap);
    margin: 0 0 2rem 0;
  }
  /* Tarjeta (dos columnas internas para mantener tu layout original) */
  .com-card{
    display:grid;
    grid-template-columns: 1.1fr 1fr;
    background:transparent;
    gap:var(--gap);
  }
  @media (max-width: 720px){
    .com-card{ grid-template-columns: 1fr; }
  }

  /* Columna izquierda (título y link principal oscuro) */
  .com-left{
    padding:1rem;
    background:var(--bg-dark);
    color:#fff;
    border:2px solid var(--bg-dark);
    border-radius:var(--radius);
  }
  .com-link{
    display:inline-flex;
    align-items:center;
    gap:10px;
    color:#fff;
    text-decoration:none;
  }
  .com-link:hover{ color:var(--accent); }
  .com-title{
    text-decoration:underline;
    font-size:0.95rem;
    line-height:1.25rem;
    text-shadow:0.1rem 0 var(--bg-dark), 0.15rem 0 var(--bg-dark);
    font-weight:700;
  }

  /* Columna derecha (resumen claro) */
  .com-right{
    padding:1rem;
    background:var(--bg-light);
    color:var(--text-dark);
    border:2px solid var(--border);
    border-radius:var(--radius);
    line-height:1.5rem;
  }
  .com-right a.inline-icon{
    display:inline-flex; align-items:center;
  }
  .com-right img{
    max-width:30px; vertical-align:middle;
  }
  .com-date{
    display:block;
    margin-top:.3rem;
    font-style:italic;
    color:#d8ad89;
  }

  /* Icono SVG reutilizable */
  .com-icon{ width:23px; height:23px; flex:0 0 23px; }
</style>

<!-- Sprite SVG (icono documento) -->
<svg aria-hidden="true" style="position:absolute; width:0; height:0; overflow:hidden;">
  <symbol id="doc-icon" viewBox="0 0 24 24">
    <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8zM14 2v6h6" fill="none" stroke="currentColor" stroke-width="2" stroke-linejoin="round" stroke-linecap="round"/>
    <path d="M8 13h8M8 17h8M8 9h4" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
  </symbol>
</svg>

<section class="com-grid" role="list" aria-label="Comunicados 2024">

  <!-- 1 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/documentos/Lista_expedientes_Publicar%202024.pdf" target="_blank" rel="noopener noreferrer" title="Abrir PDF">
        <svg class="com-icon" role="img" aria-label="Documento"><use href="#doc-icon"/></svg>
        <span class="com-title">LISTA DE EXPEDIENTES RECIBIDOS EN FORMA FÍSICA Y POR CORREO ELECTRÓNICO EN EL PLAZO ESTABLECIDO...</span>
      </a>
    </div>
    <div class="com-right">
      Lista de los aspirantes para elegir a un integrante del Comité de Participación Social del Sistema Estatal Anticorrupción de Jalisco.<br>
      <a class="inline-icon" href="/documentos/Lista_expedientes_Publicar%202024.pdf" target="_blank" rel="noopener noreferrer" title="Descargar PDF: Lista de aspirantes 2024">
        <img src="/favicons/icon_pdf.png" alt="PDF Lista de aspirantes 2024">
      </a>
      <time class="com-date" datetime="2024-09-30">Publicado 30/09/2024</time>
    </div>
  </article>

  <!-- 2 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/documentos/metodologia_evaluacion_documental_curricular_2024.pdf" target="_blank" rel="noopener noreferrer" title="Abrir PDF">
        <svg class="com-icon" role="img" aria-label="Documento"><use href="#doc-icon"/></svg>
        <span class="com-title">METODOLOGÍA PARA LA EVALUACIÓN DOCUMENTAL Y CURRICULAR DE LOS EXPEDIENTES...</span>
      </a>
    </div>
    <div class="com-right">
      I. Antecedentes y marco normativo. II. Procedimientos e instrumentos de verificación de registro...<br>
      <a class="inline-icon" href="/documentos/metodologia_evaluacion_documental_curricular_2024.pdf" target="_blank" rel="noopener noreferrer" title="Descargar PDF: Metodología de evaluación curricular 2024">
        <img src="/favicons/icon_pdf.png" alt="PDF Metodología de evaluación curricular 2024">
      </a>
      <time class="com-date" datetime="2024-10-01">Publicado 01/10/2024</time>
    </div>
  </article>

  <!-- 3 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/documentos/3.AcuerdoConcursantes2024.pdf" target="_blank" rel="noopener noreferrer" title="Abrir PDF">
        <svg class="com-icon" role="img" aria-label="Documento"><use href="#doc-icon"/></svg>
        <span class="com-title">ACUERDO DE LA COMISIÓN DE SELECCIÓN POR EL CUAL SE PUBLICAN LOS NOMBRES DE LAS Y LOS CANDIDATOS...</span>
      </a>
    </div>
    <div class="com-right">
      Con fundamento en los artículos 17, 18 y 34 de la Ley del Sistema Anticorrupción del Estado de Jalisco y conforme a lo establecido en la Convocatoria...<br>
      <a class="inline-icon" href="/documentos/3.AcuerdoConcursantes2024.pdf" target="_blank" rel="noopener noreferrer" title="Descargar PDF: Acuerdo Comisión de Selección 2024">
        <img src="/favicons/icon_pdf.png" alt="PDF Acuerdo Comisión de Selección 2024">
      </a>
      <time class="com-date" datetime="2024-10-04">Publicado 04/10/2024</time>
    </div>
  </article>

  <!-- 4 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/CVs2024/cv-2024" target="_blank" rel="noopener noreferrer" title="Abrir listado">
        <svg class="com-icon" role="img" aria-label="Enlace"><use href="#doc-icon"/></svg>
        <span class="com-title">VERSIÓN PÚBLICA DE LOS EXPEDIENTES QUE PRESENTARON LAS Y LOS CANDIDATOS QUE CUMPLEN LOS REQUISITOS...</span>
      </a>
    </div>
    <div class="com-right">
      Lista de las y los candidatos que presentaron expedientes completos y cumplieron con los requisitos conforme a la convocatoria...<br>
      <a class="inline-icon" href="/CVs2024/cv-2024" target="_blank" rel="noopener noreferrer" title="Abrir versión pública de expedientes 2024">
        <img src="/favicons/link-icon.jpg" alt="Abrir listado 2024">
      </a>
      <time class="com-date" datetime="2024-10-09">Publicado 09/10/2024</time>
    </div>
  </article>

  <!-- 5 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/documentos/5.%20Din%C3%A1mica%20para%20entrevistas%20-.pdf" target="_blank" rel="noopener noreferrer" title="Abrir PDF">
        <svg class="com-icon" role="img" aria-label="Documento"><use href="#doc-icon"/></svg>
        <span class="com-title">ACUERDO DE LA COMISIÓN DE SELECCIÓN: DINÁMICA PARA EL DESARROLLO DE LAS ENTREVISTAS...</span>
      </a>
    </div>
    <div class="com-right">
      Acuerdo por el cual se publica la dinámica para el desarrollo de las entrevistas a las y los candidatos seleccionados conforme a la convocatoria...<br>
      <a class="inline-icon" href="/documentos/5.%20Din%C3%A1mica%20para%20entrevistas%20-.pdf" target="_blank" rel="noopener noreferrer" title="Descargar PDF: Dinámica para entrevistas">
        <img src="/favicons/icon_pdf.png" alt="PDF Dinámica para entrevistas">
      </a>
      <time class="com-date" datetime="2024-10-11">Publicado 11/10/2024</time>
    </div>
  </article>

  <!-- 6 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/documentos/4.%20Mejores%20perfiles%20y%20cronograma%20entrevistas.pdf" target="_blank" rel="noopener noreferrer" title="Abrir PDF">
        <svg class="com-icon" role="img" aria-label="Documento"><use href="#doc-icon"/></svg>
        <span class="com-title">ACUERDO: FECHA Y HORA PARA ENTREVISTAS A LOS 10 MEJORES PERFILES...</span>
      </a>
    </div>
    <div class="com-right">
      Publicación de fecha y hora para realizar las entrevistas a las y los candidatos seleccionados como los 10 mejores perfiles...<br>
      <a class="inline-icon" href="/documentos/4.%20Mejores%20perfiles%20y%20cronograma%20entrevistas.pdf" target="_blank" rel="noopener noreferrer" title="Descargar PDF: Cronograma de entrevistas">
        <img src="/favicons/icon_pdf.png" alt="PDF Cronograma de entrevistas">
      </a>
      <time class="com-date" datetime="2024-10-11">Publicado 11/10/2024</time>
    </div>
  </article>

  <!-- 7 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/cedula-2024" target="_blank" rel="noopener noreferrer" title="Abrir evaluaciones">
        <svg class="com-icon" role="img" aria-label="Enlace"><use href="#doc-icon"/></svg>
        <span class="com-title">VERSIÓN PÚBLICA DE LAS EVALUACIONES CURRICULARES...</span>
      </a>
    </div>
    <div class="com-right">
      Versión pública de las evaluaciones curriculares, suma de puntajes y promedio obtenido por quienes llegaron a esta fase...<br>
      <a class="inline-icon" href="/cedula-2024" target="_blank" rel="noopener noreferrer" title="Abrir evaluaciones curriculares 2024">
        <img src="/favicons/link-icon.jpg" alt="Abrir evaluaciones 2024">
      </a>
      <time class="com-date" datetime="2024-10-11">Publicado 11/10/2024</time>
    </div>
  </article>

  <!-- 8 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/documentos/Acuerdo%20designaci%C3%B3n%20integrante%20CPSoct2024.pdf" target="_blank" rel="noopener noreferrer" title="Abrir PDF">
        <svg class="com-icon" role="img" aria-label="Documento"><use href="#doc-icon"/></svg>
        <span class="com-title">ACUERDO DE NOMBRAMIENTO</span>
      </a>
    </div>
    <div class="com-right">
      Se otorga el nombramiento al nuevo integrante del Comité de Participación Social del Sistema Anticorrupción del Estado de Jalisco...<br>
      <a class="inline-icon" href="/documentos/Acuerdo%20designaci%C3%B3n%20integrante%20CPSoct2024.pdf" target="_blank" rel="noopener noreferrer" title="Descargar PDF: Acuerdo de nombramiento">
        <img src="/favicons/icon_pdf.png" alt="PDF Acuerdo de nombramiento">
      </a>
      <time class="com-date" datetime="2024-10-28">Publicado 28/10/2024</time>
    </div>
  </article>

  <!-- 9 -->
  <article class="com-card" role="listitem">
    <div class="com-left">
      <a class="com-link" href="/declaraciones-2024" target="_blank" rel="noopener noreferrer" title="Abrir declaraciones">
        <svg class="com-icon" role="img" aria-label="Enlace"><use href="#doc-icon"/></svg>
        <span class="com-title">DECLARACIONES DEL NUEVO INTEGRANTE DEL COMITÉ DE PARTICIPACIÓN SOCIAL</span>
      </a>
    </div>
    <div class="com-right">
      Declaraciones de intereses, patrimonial y fiscal de Arturo Antonio Ríos Bojórquez, conforme a la Ley del Sistema Anticorrupción del Estado de Jalisco...<br>
      <a class="inline-icon" href="/declaraciones-2024" target="_blank" rel="noopener noreferrer" title="Abrir declaraciones 2024">
        <img src="/favicons/link-icon.jpg" alt="Abrir declaraciones 2024">
      </a>
      <time class="com-date" datetime="2024-10-28">Publicado 28/10/2024</time>
    </div>
  </article>

</section>

<h4>Consulta los comunicados de los años anteriores:</h4>
<h4>
  <a href="https://comisionsaejalisco.org/comunicados-2021">2021</a>,
  <a href="https://comisionsaejalisco.org/comunicados-2020">2020</a>,
  <a href="https://comisionsaejalisco.org/comunicados-2019">2019</a>,
  <a href="https://comisionsaejalisco.org/comunicados-2018">2018</a>,
  <a href="https://comisionsaejalisco.org/comunicados-2017">2017</a>,
  <a href="https://comisionsaejalisco.org/comunicados-2022">2022</a>,
  <a href="https://comisionsaejalisco.org/comunicados-2023">2023</a>
</h4>
