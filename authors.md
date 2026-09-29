---
layout: default
title: Authors
permalink: /authors/
---
<section class="wrap page-head"><h1>Authors</h1><p>The site is conceived as a shared notebook rather than a single-author project. Essays, observations, reading notes, dispatches, and fieldnotes can retain distinct voices while inhabiting the same thermal world.</p></section><section class="wrap author-list">{% for item in site.data.authors %}{% assign a = item[1] %}<div class="author-row"><div><h2>{{ a.name }}</h2><div class="smallcaps">{{ a.role }}</div></div><div><p>{{ a.bio }}</p><a href="{{ a.link | relative_url }}">View posts →</a></div></div>{% endfor %}</section>
