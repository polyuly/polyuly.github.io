---
title: "Digital Psychosocial Health Research Group- Gallery"
layout: piclay
excerpt: "Digital Psychosocial Health Research Group -- Gallery"
permalink: /pictures/
---

<!-- # Gallery -->

### Research and Study @ PolyU

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_poly_nursing %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyuNursing/{{ pic.image }}" class="img-responsive" width="95%" style="float: left;{% if pic.image contains 'research-study-01.jpg' %} aspect-ratio:4/3; object-fit:cover; object-position:center 65%;{% elsif pic.image contains 'research-study-02.jpg' %} aspect-ratio:4/3; object-fit:cover; object-position:center 20%;{% endif %}" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

### Life and Fun @ PolyU

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_poly_nursing2 %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyuNursing2/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>