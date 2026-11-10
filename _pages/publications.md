---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Full and up-to-date lists are on [ORCID](https://orcid.org/0000-0003-0337-7084), [Scopus](https://www.scopus.com/authid/detail.uri?authorId=35495930100) and [CIÊNCIA VITAE](https://www.cienciavitae.pt/portal/8B1F-4494-6198).

{% assign journals = site.publications | where: "pubtype", "journal" | reverse %}
{% assign chapters = site.publications | where: "pubtype", "chapter" | reverse %}
{% assign confs = site.publications | where: "pubtype", "conference" | reverse %}

<h2>Journal articles</h2>
{% for post in journals %}
  {% include archive-single.html %}
{% endfor %}

<h2>Book chapters</h2>
{% for post in chapters %}
  {% include archive-single.html %}
{% endfor %}

<h2>Conference papers</h2>
{% for post in confs %}
  {% include archive-single.html %}
{% endfor %}
