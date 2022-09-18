---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
{% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

[<i class="ai ai-google-scholar ai-1x fa-align-center"></i>]({{ author.googlescholar }}){:target="_blank"}{:rel="noopener noreferrer"}&nbsp;[Google Scholar]({{ author.googlescholar }}){:target="_blank"}{:rel="noopener noreferrer"}
&emsp;[<i class="ai ai-researchgate ai-1x"></i>]({{ author.researchgate }}){:target="_blank"}{:rel="noopener noreferrer"}&nbsp; [ResearchGate]({{ author.researchgate }}){:target="_blank"}{:rel="noopener noreferrer"}
&emsp;[<i class="ai ai-orcid ai-1x"></i>]({{ author.orcid }}){:target="_blank"}{:rel="noopener noreferrer"}&nbsp;[ORCID]({{ author.orcid }}){:target="_blank"}{:rel="noopener noreferrer"}
&emsp;[<i class="ai ai-dblp ai-1x"></i>]({{ author.dblp }}){:target="_blank"}{:rel="noopener noreferrer"}&nbsp;[dblp]({{ author.dblp }}){:target="_blank"}{:rel="noopener noreferrer"}
&emsp;[<i class="ai ai-scopus ai-1x"></i>]({{ author.scopus }}){:target="_blank"}{:rel="noopener noreferrer"}&nbsp;[Scopus]({{ author.scopus }}){:target="_blank"}{:rel="noopener noreferrer"}
&emsp;[<i class="ai ai-semantic-scholar ai-1x"></i>]({{ author.semantic-scholar }}){:target="_blank"}{:rel="noopener noreferrer"}&nbsp;[Semantic Scholar]({{ author.semantic-scholar }}){:target="_blank"}{:rel="noopener noreferrer"}

{% for post in site.publications reversed %} {% include archive-single.html %} {% endfor %}