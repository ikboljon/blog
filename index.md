---
layout: default
title: Ikboljon Sobirov
permalink: /
---
<section class="wrap">
<h1 class="tele-title">Ikboljon Sobirov</h1>
<p class="tele-sub">Uzbekcha maqolalar — oddiy, toza dizayn, telegra.ph uslubida.</p>

<ul class="tele-ul">
  {%- for post in site.posts -%}
    <li class="tele-li">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="tele-date">{{ post.date | date: "%d %b %Y" }}</span>
    </li>
  {%- endfor -%}
</ul>
</section>
