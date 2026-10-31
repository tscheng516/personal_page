---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Also on [Google Scholar]({{ site.author.googlescholar }}) · [ORCID]({{ site.author.orcid }}).

{% assign published = site.publications | where: "status", "published" | sort: "date" | reverse %}
{% assign preprints = site.publications | where: "status", "preprint" | sort: "date" | reverse %}

Peer-reviewed
======
{% for post in published %}
  {% include archive-single.html %}
{% endfor %}

Preprints and under review
======
{% for post in preprints %}
  {% include archive-single.html %}
{% endfor %}
