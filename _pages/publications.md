---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

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

