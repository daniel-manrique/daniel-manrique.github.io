---
layout: page
permalink: /repositories/
title: Repositories
description: Code, data and teaching materials behind my research, tutorials and courses. Everything is open on GitHub.
nav: false
---

<p><a href="https://github.com/{{ site.github_username }}"><i class="fa-brands fa-github"></i> github.com/{{ site.github_username }}</a></p>

<div class="row row-cols-1 row-cols-md-2">
  {% for repo in site.data.repositories.github_repos %}
  <div class="col mb-4">
    <a href="https://github.com/{{ repo.name }}" class="text-decoration-none">
      <div class="card hoverable h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="fa-brands fa-github fa-sm"></i> {{ repo.name }}</h5>
          <p class="card-text">{{ repo.description }}</p>
        </div>
      </div>
    </a>
  </div>
  {% endfor %}
</div>
