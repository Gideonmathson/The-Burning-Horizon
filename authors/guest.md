
---
layout: default
title: Guest Contributor
permalink: /authors/guest/
---
<section class="wrap page-head"><h1>Guest Contributor</h1><p>This profile is deliberately a placeholder. Duplicate it for each new contributor and add them to <code>_data/authors.yml</code>.</p></section><section class="wrap">{% assign posts = site.posts | where: "author", "guest" %}{% for post in posts %}{% include post-card.html post=post %}{% endfor %}</section>
