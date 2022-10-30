---
title: "Data Analyst Portfolio"
date: 2022/10/24
---
Hi!  I'm Estitxu Larralde

A multilingual Data Analyst with a solid background in finance and sales. 
I love learning, looking for trends in data and communicating my findings.
I like working with SQL, Excel, Python and Tableau.
Get in touch with me on LinkedIn.

---
{% for post in site.posts %}
## {{ post.title }}

{{ post.excerpt }}

[Full Article]({{ post.url | relative_url }})
{% endfor %}
