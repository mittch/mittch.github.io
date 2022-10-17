---
layout: default
title: Home
order: 1
---
## Persönlicher Blog

<ul class="post-list">
  {% for post in site.posts %}
    <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
    </li>
  {% endfor %}
</ul>

![visitors](https://visitor-badge.glitch.me/badge?page_id=mittch.mittch.github.io)

## Links
*[Azure Test page](https://https://proud-sky-0fe630703.1.azurestaticapps.net/)