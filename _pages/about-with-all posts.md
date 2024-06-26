---
permalink: /test-2/
title: "Vince Lam"
# excerpt: "About me"
author_profile: true
redirect_from: 

---
I’m a data scientist with experience in delivering business impact by deploying machine learning models, applying data analysis, communicating actionable insights to stakeholders, and collaborating with cross-functional teams. I have a passion for AutoML, natural language processing, time-series analysis, modelling, and data storytelling. Formerly based in London and newly relocated in Singapore.

Within the UK public sector, I developed and deployed machine learning models, predicted Covid cases and deaths, applied probabilistic data linkage, automated pipelines, built public facing dashboards, orchestrated the central dashboard, and created a new knowledge share data community.

You can see what I'm working on now [here](now.md). If you'd like to get in touch, just drop me an [email](mailto:vincenthmlam@gmail.com).

# Recent posts

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
{% if year != written_year %}
<h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
{% capture written_year %}{{ year }}{% endcapture %}
{% endif %}
{% include archive-single.html %}
{% endfor %}
