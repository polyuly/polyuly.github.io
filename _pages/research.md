---
title: "Digital Mental Health Research Group- Research Fund"
layout: textlay
excerpt: "Digital Mental Health Research Group-- Research Fund"
sitemap: false
permalink: /research/
---

# Research Fund

## Research/Academic Grants As Principal Investigator

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

* Chatbot-based mindfulness interventions for young adults with symptoms of depression: a feasibility study. Start-up Fund for RAPs under the Strategic Hiring Scheme. **Principal Investigator**, 1 January 2022-31 December 2023.

* AI-driven Vaccine Communicator——智能疫苗助理: The impact of a Web-based psychoeducation programme with a motivational AI-based digital assistant on Covid-19 vaccine hesitancy in Hong Kong's population. Grant source: Health and Medical Research Fund, Food and Health Bureau, Commissioned Research on the Novel Coronavirus Disease (COVID-19).Project Ref No. COVID1903006.

* Effects of a Physical-Psychological Integrative (PPI) intervention on Physical inactivity, Depression and Chronic pain for Community-Dwelling Spinal Cord Injury Survivors: A Pilot Randomized Controlled Trial; **Health and Medical Research Fund—Research Fellowship Scheme. Principal Investigator**, 01/Sep/2021- 01/Sep/2023. Project No. 06200147.

* Effects of caregiver-administrated acupressure intervention for community-dwelling spinal cord injury survivors with constipation: A randomized controlled trial; Hong Kong Government Chinese Medicine Development Fund; **Principal Investigator**, 1 April 2022- 31/March 2024. (Project No. 20B2/033A).

* Regular Sleep, Healthy Future - Promoting Sleep Health among College Students and Healthcare Professionals. Principal Investigator, 1 September, 2021 – 30 June, 2022, **UGC** Shanghai-Hong Kong University Alliance (SHUA) Open Bid Funding. 

* Greater Bay Area Nursing Forum: From Research to Clinical Practice Cum Workshop on Research Methods Training in Nursing. **Principal Investigator**, November 2021, **UGC** Guangdong-Hong Kong-Macao University Alliance (GHMUA) Open Bid Funding.

* Global Research Grant. Personal Research Development Fund, **King's College London.**

* Effectiveness of peer-delivered interventions for people with severe mental illness: A systematic review. Professor Ida Martinson Fund, EAFONS.


## Research Fields
1. Spinal Cord Injury Rehabilitation;
2. Psychosocial interventions (e.g., coping-based, mindfulness-based, Motivational interviewing, psychoeducation);
3. Mental Health Promotion / Technologies (e.g., AI-based, web-based, chatbot) in healthcare interventions.
