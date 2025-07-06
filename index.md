---
layout: default
title: Home
---

{% assign main_post = site.posts | where: "slug", "battery" | first %}

<h1>{{ main_post.title }}</h1>
<p><em>{{ main_post.date | date: "%d %B %Y" }}</em></p>
{{ main_post.content }}