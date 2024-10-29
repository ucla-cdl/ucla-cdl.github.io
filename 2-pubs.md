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

# TODO: Add research themes and papers here?

### Conference and journal papers
------------------------
*signifies research mentees

#### Compter science 
{% assign bib_file = 'papers.bib' %}
{% bibliography -f papers.bib --query @*[group=computer science] --bibliography_list_tag ol %}

#### Multidisciplinary
{% assign bib_file = 'papers.bib' %}
{% bibliography -f {{bib_file}} --query @*[group=multidisciplinary] --bibliography_list_tag ol %}

### Workshop, demo, and poster papers
--------------------
*signifies research mentees
^signifies equal contribution
{% assign bib_file = 'others.bib' %}
{% bibliography -f {{bib_file}} --bibliography_list_tag ol %}

### Dissertation
--------------------
{% assign bib_file = 'others.bib' %}
{% bibliography -f others.bib --query @*[group=dissertation] --bibliography_list_tag ol %}
