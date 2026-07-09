---
layout: default
title: "Inicio"
description: "Perfil académico de F. Contiggiani"
---

<section class="hero" aria-labelledby="hero-heading">
  <img src="{{ '/assets/img/foto-perfil.jpg' | relative_url }}"
       alt="Fotografía de perfil de F. Contiggiani"
       class="profile-photo"
       width="220" height="220">

  <div class="hero-text">
    <h1 id="hero-heading">F. Contiggiani</h1>
    <p class="affiliation">Afiliación institucional / cargo</p>
    <p class="bio">
      Breve presentación biográfica y líneas de investigación
      (contenido pendiente de redacción y validación por el usuario,
      conforme a lo establecido en el apartado VI de las directrices
      del proyecto).
    </p>
  </div>
</section>

<section aria-labelledby="secciones-heading">
  <h2 id="secciones-heading">Secciones</h2>
  <ul class="section-links">
    <li><a href="{{ '/pages/research.html' | relative_url }}">Investigación</a></li>
    <li><a href="{{ '/pages/publications.html' | relative_url }}">Publicaciones</a></li>
    <li><a href="{{ '/pages/teaching.html' | relative_url }}">Docencia</a></li>
    <li><a href="{{ '/pages/cv.html' | relative_url }}">Curriculum Vitae</a></li>
    <li><a href="{{ '/pages/contact.html' | relative_url }}">Contacto</a></li>
  </ul>
</section>

<section aria-labelledby="perfiles-heading">
  <h2 id="perfiles-heading">Perfiles Académicos y Repositorios</h2>
  <ul class="external-links">
    {% if site.social_links.orcid != "" %}
    <li><a href="{{ site.social_links.orcid }}" target="_blank" rel="noopener noreferrer">ORCID</a></li>
    {% endif %}
    {% if site.social_links.google_scholar != "" %}
    <li><a href="{{ site.social_links.google_scholar }}" target="_blank" rel="noopener noreferrer">Google Scholar</a></li>
    {% endif %}
    {% if site.social_links.github != "" %}
    <li><a href="{{ site.social_links.github }}" target="_blank" rel="noopener noreferrer">GitHub</a></li>
    {% endif %}
    {% if site.social_links.researchgate != "" %}
    <li><a href="{{ site.social_links.researchgate }}" target="_blank" rel="noopener noreferrer">ResearchGate</a></li>
    {% endif %}
    {% if site.social_links.linkedin != "" %}
    <li><a href="{{ site.social_links.linkedin }}" target="_blank" rel="noopener noreferrer">LinkedIn</a></li>
    {% endif %}
  </ul>
</section>
