---
# layout: archive
title: "Publications"
permalink: /publications/
# author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## 2026
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2026" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2025
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2025" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2024
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2024" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2023
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2023" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2022
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2022" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2021
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2021" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## 2020
{% for post in site.publications reversed %}
  {% capture pub_year %}{{ post.date | date: "%Y" }}{% endcapture %}
  {% if pub_year == "2020" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<sup>*</sup> Equal authorship