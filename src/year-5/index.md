---
title: Year 5
tags: years
---

# {{title}}

## Objectives

{% for curriculum in collections.curricula -%}
{%- if curriculum.data.title == title -%}
{{curriculum.templateContent}}
{%- endif -%}
{%- endfor %}

## Projects

{%- if collections.y5 %}

<ol>
{%- for project in collections.y5 -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{%- endfor -%}
</ol>
{%- else %}
Projects coming soon
{%- endif -%}
