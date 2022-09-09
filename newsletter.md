---
title: Baugarten
layout: newsletter
---

<img src="https://www.baugarten.app/assets/images/newsletter/newsletter_header.png" class="center-image">
* * *

### Latest News

<div class="container center" style="max-width: 500px">



{%- if site.posts.size > 0 -%}
  <ul class="post-list"> {%- for post in site.posts limit:6 -%}
    <li>
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </h3>
      {%- if site.show_excerpts -%}
        <div id="leftify">
          {{ post.excerpt }}
        </div>
      {%- endif -%}
    </li>
    {%- endfor -%}
  </ul>

{%- endif -%}
</div>


* * *

### Are you a student, a teacher, a gamer, or just someone who finds our project exciting? 
#### We'd love to hear from you.

##### <a href="mailto: henry@baugarten.app">henry@baugarten.app</a>
* +49 0176 473 89 458
* Kreuzberg, Berlin
* 10965, Deutschland

[![instagram_baugarten_link](https://www.baugarten.app/assets/images/insta_logo.png.webp){: style="width: 100px"}](https://www.instagram.com/baugarten_formula_game/)

