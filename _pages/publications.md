---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please find the most updated versions of the list of publications on [Scholar](https://scholar.google.it/citations?user=_dJLciQAAAAJ&hl=en), [ORCID](https://orcid.org/0000-0002-5265-7392), or [Scopus](https://www.scopus.com/authid/detail.uri?authorId=56176857700).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Preprints

   <ul>{% for post in site.preprints reversed %}
      {% include archive-single.html %}
   {% endfor %}</ul>

## Peer-reviewed journal

   <ul>{% for post in site.journals reversed %}
      {% include archive-single.html %}
   {% endfor %}</ul>

## Peer-reviewed conference

   <ul>{% for post in site.proceedings reversed %}
      {% include archive-single.html %}
   {% endfor %}</ul>

