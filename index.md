---
layout: home
title: "Home"
author_profile: true
---

Hi! I’m **Kevin Crooks Jr.** — CS @ UB (Cybersecurity minor).  
I’m focused on **application / software security** and I post updates about what I’m building and learning.

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

- **LinkedIn:** https://www.linkedin.com/in/YOUR-kevin-crooks-jr
- **GitHub:** https://github.com/letslycook

### Latest updates
You can read my newest posts in the **Blog** tab.
