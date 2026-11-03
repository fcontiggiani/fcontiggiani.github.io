---
layout: default
title: "Inicio"
description: "Perfil académico de Federico E. Contiggiani — economía aplicada, políticas públicas y ciencia de datos (UNRN)."
image: /assets/img/foto-perfil-cuadrada.jpg
---

<section class="hero-modern" aria-labelledby="hero-heading">
  <div class="hero-text">
    <p class="eyebrow">Profesor Adjunto · Investigador</p>

    <h1 id="hero-heading">Federico E. <span class="accent">Contiggiani</span></h1>

    <p class="affiliation">
      <strong>Instituto de Investigación en Políticas Públicas y Gobierno (IIPPyG)</strong><br>
      Universidad Nacional de Río Negro · Sede Atlántica · Argentina
    </p>

    <p class="bio">
      Trabajo en la intersección entre la economía aplicada, las políticas públicas
      y la ciencia de datos. Me interesa cómo los métodos cuantitativos y la
      inteligencia artificial pueden mejorar la toma de decisiones públicas,
      con especial atención a la región de la Norpatagonia.
    </p>

    <ul class="topic-tags" aria-label="Áreas de interés">
      <li>Economía aplicada</li>
      <li>Políticas públicas</li>
      <li>Ciencia de datos</li>
      <li>Inteligencia artificial</li>
      <li>Teoría de la decisión</li>
    </ul>

    <div class="hero-actions">
      <a class="btn btn-primary" href="{{ '/pages/research.html' | relative_url }}">
        Ver investigación
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M5 12h14M13 6l6 6-6 6"/></svg>
      </a>
      <a class="btn btn-ghost" href="mailto:{{ site.email }}">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="m3 7 9 6 9-6"/></svg>
        Escribirme
      </a>
    </div>
  </div>

  <figure class="hero-photo">
    <picture>
      <source srcset="{{ '/assets/img/foto-perfil-retrato.webp' | relative_url }}" type="image/webp">
      <img src="{{ '/assets/img/foto-perfil-retrato.jpg' | relative_url }}"
           alt="Retrato de Federico E. Contiggiani"
           width="720" height="900" fetchpriority="high">
    </picture>
    <figcaption>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 21s-7-6.2-7-11.5A7 7 0 0 1 19 9.5C19 14.8 12 21 12 21z"/><circle cx="12" cy="9.5" r="2.5"/></svg>
      Norpatagonia, Argentina
    </figcaption>
  </figure>
</section>

<section class="home-block" aria-labelledby="secciones-heading">
  <div class="block-head">
    <h2 id="secciones-heading">Explorá el sitio</h2>
    <p>Investigación, producción académica y docencia.</p>
  </div>
  <ul class="section-cards">
    <li>
      <a href="{{ '/pages/research.html' | relative_url }}">
        <span class="card-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="11" cy="11" r="7"/><path d="m20 20-3.5-3.5"/></svg></span>
        <span class="card-title">Investigación</span>
        <span class="card-text">Líneas de trabajo y proyectos en curso.</span>
        <span class="card-arrow" aria-hidden="true">→</span>
      </a>
    </li>
    <li>
      <a href="{{ '/pages/publications.html' | relative_url }}">
        <span class="card-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 19.5V5a2 2 0 0 1 2-2h13v16H6a2 2 0 0 0-2 2z"/><path d="M8 7h7M8 11h7"/></svg></span>
        <span class="card-title">Publicaciones</span>
        <span class="card-text">Artículos, capítulos y documentos de trabajo.</span>
        <span class="card-arrow" aria-hidden="true">→</span>
      </a>
    </li>
    <li>
      <a href="{{ '/pages/teaching.html' | relative_url }}">
        <span class="card-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m2 9 10-5 10 5-10 5z"/><path d="M6 11v5c0 1.5 3 3 6 3s6-1.5 6-3v-5"/></svg></span>
        <span class="card-title">Docencia</span>
        <span class="card-text">Cursos de grado y posgrado, dirección de tesis.</span>
        <span class="card-arrow" aria-hidden="true">→</span>
      </a>
    </li>
    <li>
      <a href="{{ '/pages/cv.html' | relative_url }}">
        <span class="card-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M14 3H6a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V9z"/><path d="M14 3v6h6M8 13h8M8 17h5"/></svg></span>
        <span class="card-title">Curriculum Vitae</span>
        <span class="card-text">Formación, cargos y antecedentes.</span>
        <span class="card-arrow" aria-hidden="true">→</span>
      </a>
    </li>
  </ul>
</section>

<section class="home-block" aria-labelledby="perfiles-heading">
  <div class="block-head">
    <h2 id="perfiles-heading">Perfiles académicos</h2>
    <p>Identificadores, citas y repositorios de código.</p>
  </div>
  <ul class="profile-links">
    {%- if site.social_links.orcid != "" %}
    <li><a href="{{ site.social_links.orcid }}" target="_blank" rel="noopener noreferrer">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="9"/><path d="M9 8v8M12.5 8h1a4 4 0 0 1 0 8h-1z"/></svg>ORCID</a></li>
    {%- endif %}
    {%- if site.social_links.google_scholar != "" %}
    <li><a href="{{ site.social_links.google_scholar }}" target="_blank" rel="noopener noreferrer">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m2 9 10-6 10 6-10 6z"/><circle cx="12" cy="16" r="4"/></svg>Google Scholar</a></li>
    {%- endif %}
    {%- if site.social_links.github != "" %}
    <li><a href="{{ site.social_links.github }}" target="_blank" rel="noopener noreferrer">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="m8 8-4 4 4 4M16 8l4 4-4 4M14 5l-4 14"/></svg>GitHub</a></li>
    {%- endif %}
    {%- if site.social_links.researchgate != "" %}
    <li><a href="{{ site.social_links.researchgate }}" target="_blank" rel="noopener noreferrer">ResearchGate</a></li>
    {%- endif %}
    {%- if site.social_links.linkedin != "" %}
    <li><a href="{{ site.social_links.linkedin }}" target="_blank" rel="noopener noreferrer">LinkedIn</a></li>
    {%- endif %}
    <li><a href="{{ '/pages/contact.html' | relative_url }}">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="m3 7 9 6 9-6"/></svg>Contacto</a></li>
  </ul>
</section>
