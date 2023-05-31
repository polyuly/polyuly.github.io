---
title: "Polyu Nursing - Gallery"
layout: piclay
excerpt: "Polyu Nursing -- Gallery"
permalink: /pictures/
---

<!-- # Gallery -->
## Professor @ PolyU

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_poly2 %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyuNew/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
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

## Postdoc @ UoE
From [The Soft Systems Group](https://softsystemsgroup.com/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/UOE/apple.jpg" width="21%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/UOE/xmas.jpg" width="28%">
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/UOE/dinner.jpg" width="45%"> -->
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/UOE/rov3.jpg" width="40%">
</figure>

## Postdoc @ NTU
From [Air Traffic Management Research Institute](atmri.ntu.edu.sg).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/ATMRI/DSC08906.JPG" width="35%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/ATMRI/coffee.jpg" width="30%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/ATMRI/new-year.jpg" width="30%">
</figure>

## PhD Study @ PolyU
From [High-speed Thermo-fluid and MAV/UAV Laboratory](https://www.polyu.edu.hk/researchgrp/cywen/index.php/en/index.html).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/sust.jpg" width="32%">
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/IMG_3809.JPG" width="32%"> -->
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/IMG_3720.JPG" width="32%"> -->
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/IMG_0953.jpg" width="32%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/IMG_3232.JPG" width="32%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/taiwan_competition3.jpg" width="32%">
<!-- <img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/taiwan_competition4.jpg" width="32%"> -->
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/taiwan_competition5.jpg" width="32%">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/PolyU/pilot2.jpg" width="25%">
</figure>

<!-- ## Old-time @ NPU
From the [Micro Air Vehicle Laboratory](https://hangkong.nwpu.edu.cn/English/home.htm) and undergraduate student groups.
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/NPU/car1.jpg" width="40%">
</figure> -->



<!-- # Pictures
Jump to: [Leiden](#leiden), [ETHZ](#ethz), [Cornell](#cornell), [St Andrews](#st-andrews)


## Leiden

#### Timelapse of our STM assembling [(see LION news item)](https://www.physics.leidenuniv.nl/index.php?id=11573&news=867&type=lion&ln=EN):
<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
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

First advertisement.
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >
</figure>


## ETHZ
From the [group of Andreas Wallraff](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>

## Cornell
From the [group of Seamus JC Davis](http://davisgroup.lassp.cornell.edu).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>

## St Andrews
From the [group of Felix Baumberger](http://dqmp.unige.ch/baumberger/) (now at University of Geneva).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageSTA_red.jpg" width="60%">
</figure> -->
