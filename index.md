---
layout: home
title: "Home"
author_profile: true
---

Hi! I’m **Kevin Crooks Jr.** — CS @ UB (Cybersecurity minor).  
I’m focused on **application / software security** and I post longer technical writeups about Security+, AppSec, and my projects.

## Latest posts
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

{% if site.posts.size == 0 %}
No posts yet — first technical writeup coming soon.
{% endif %}

## Links
[View Resume]({{ '/assets/resume/Kevin_Crooks_Jr_Resume.pdf' | relative_url }})
{: .btn .btn--primary .btn--large }

[GitHub](https://github.com/letslycook)
{: .btn .btn--inverse .btn--large }

[LinkedIn](https://www.linkedin.com/in/kevin-crooks-jr/)
{: .btn .btn--inverse .btn--large }
