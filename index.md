---
layout: default
title: Home
order: 1
---

<meta name="google-site-verification" content="TPYaVhXyNFsqt1tPGI-kgNPtJGHlLGuMEXaaEURbcCM" />

<img src="/assets/thatsme.jpg" alt="thatsme" style="width:200px;"/>

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

## Links
[Azure Test page - via static app](https://proud-sky-0fe630703.1.azurestaticapps.net/)

[Azure Test page - via vm](http://20.160.58.41/)