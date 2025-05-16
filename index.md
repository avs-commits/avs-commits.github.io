---
layout: splash
title: "HI, I'm Alex V. Smith"
subtitle: "Digital Transforamtion | ESG | Post M&A Integration
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/header.jpg
  actions:
    - label: "View Research"
      url: "/research"
    - label: "Read Blog"
      url: "/"
excerpt: "Welcome to my personal site. I explore complexe systems, machine learning, and the science of science."
---

## Welcome

Thanks for stopping by. I use this site to share ideas, research, and occasional writing on topics that interest me.

---

## Featured Post

{% assign post = site.posts.first %}
> [**{{ post.title}}**]({{_post.url}})<br>
> {{ post.excerpt | strip_html | truncatewords: 25 }}
_Read the full post → [{{ post.url }}]({{ post.url }})_
