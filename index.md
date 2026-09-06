---
layout: page
title: Thomas Foucault
permalink: /
showcase_categories:
  - showcase_published
  - showcase_personal
  - showcase_non_games

hide_hero: true
show_sidebar: false
---

<section class="section">
    <div class="container has-text-centered">
        <figure class="image is-256x256" style="margin: 0 auto;">
        <img class="is-rounded" src="{{ '/assets/img/profile.jpg' | relative_url }}" alt="Thomas Foucault">
        </figure>

        <h1 class="title is-2 mt-5 mb-2">Thomas Foucault</h1>
        <p class="subtitle is-5 mb-4">
        Game developer building small and playful web games.
        </p>

        <div class="buttons is-centered mt-4">
        <a class="button is-primary" href="#projects">Games</a>
        <a class="button is-light" target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/thfoucault">LinkedIn</a>
        <a class="button is-light" href="mailto:thomasfclt@gmail.com">Contact</a>
        </div>
    </div>
</section>

<section class="section pt-1">
  <div class="container">
    <hr id="projects">
    {% include showcase-grid-categories.html %}
  </div>
</section>
