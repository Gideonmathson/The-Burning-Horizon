---
layout: default
title: Founding Editor
permalink: /authors/editor/
---
<section class="wrap page-head"><h1>Founding Editor</h1><p>Writes on heat, perception, embodiment, cities, and phenomenology.</p></section><section class="wrap">{% assign posts = site.posts | where: "author", "editor" %}{% for post in posts %}{% include post-card.html post=post %}{% endfor %}</section>
