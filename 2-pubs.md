---
layout: page
title: Publications
permalink: /publications/
---
<style type="text/css" media="screen">
    .award {
        color: red;
    }
</style>
<link rel="icon" href="{{ site.url }}/favicon.ico" type="image/x-icon">

### Conference and journal papers
------------------------
*signifies students

#### Compter science 
{% assign bib_file = 'papers.bib' %}
{% bibliography -f papers.bib --query @*[group=computer science] --bibliography_list_tag ol %}

#### Multidisciplinary
{% assign bib_file = 'papers.bib' %}
{% bibliography -f {{bib_file}} --query @*[group=multidisciplinary] --bibliography_list_tag ol %}

### Workshop, demo, and poster papers
--------------------
*signifies students
^signifies equal contribution
{% assign bib_file = 'others.bib' %}
{% bibliography -f {{bib_file}} --bibliography_list_tag ol %}

### Theses
--------------------
{% assign bib_file = 'others.bib' %}
{% bibliography -f others.bib --query @*[group=dissertation] --bibliography_list_tag ol %}
