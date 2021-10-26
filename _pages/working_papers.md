---
layout: archive
title: "Working Papers"
permalink: /working-papers/
author_profile: true
---

{% for post in site.working_papers reversed %}
  {% include archive-single.html %}
{% endfor %}

# Works in Progress
**"Sexual Minority Youth Homelessness: Health Disparities and Policy Implications”**
Cameron Deal, Gilbert Gonzales.

**“Medicaid Expansion and its Effects on Same-Sex Households”** Samuel Mann,
Christopher Carpenter, Gilbert Gonzales, Cameron Deal.

**“LGBT Health Disparities During COVID-19: Evidence from the Household
Pulse Survey”** Cameron Deal, Abinaya Ramakrishnan, Tara McKay, Kirsty
Clark.

**“The Bisexual Health Gap: Evidence from the YRBS”** Cameron Deal.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


