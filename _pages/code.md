---
title: "VLG - Data/Code"
layout: gridlay
excerpt: "VLG - Data/Code"
sitemap: false
permalink: /code/
---

# Data/Code


{% for publi in site.data.code %}

<div class="row">

<div class="col-sm-12 clearfix">
 <div class="well clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-fluid"  width= "300px" style="float: left" />
  <pubtit>{{ publi.acronym }} : {{ publi.title }} <em>{{ publi.conference }}</em></pubtit> 
  <p>{{ publi.description }}</p>
  <p><strong><a href="{{ site.url }}{{ site.baseurl }}/projects/{{ publi.acronym }}/">Code/Data</a></strong></p>
 </div>
</div>


</div>

{% endfor %}



<p> &nbsp; </p>