---
title: "Digital Psychosocial Health Research Group- Research Project"
layout: gridlay
excerpt: "Digital Psychosocial Health Research Group-- Research Project"
sitemap: false
permalink: /research/
---


<h3>Research Projects</h3>

<hr>

<h3 id="digital">Digital / e-Health Intervention</h3>

<p>
Representative projects focusing on digital mental health, virtual reality, chatbots, and other technology-based interventions.
</p>

{% for project in site.data.projects.digital %}

<div class="project-card" style="border:1px solid #d9d9d9; background:#f7f7f7; border-radius:10px; padding:18px 20px; margin-bottom:28px; box-shadow:0 1px 3px rgba(0,0,0,0.06);">

  {% if project.image %}
  <img src="{{ site.baseurl }}{{ project.image }}"
  alt="{{ project.title }}"
  class="img-responsive"
  style="max-width:420px; border-radius:8px; margin-bottom:12px; display:block; margin-left:auto; margin-right:auto;">
{% endif %}

<h4 style="margin-top:0; margin-bottom:8px; font-weight:600;">
  {{ project.title }}
</h4>

<h5 style="margin-top:0; margin-bottom:4px; font-weight:600;">
  Funder: {{ project.funder }}
</h5>

<h5 style="margin-top:0; margin-bottom:8px; font-weight:600;">
  Duration: {{ project.duration }}
</h5>

{% if project.more_information and project.more_information.size > 0 %}
<p style="margin-bottom:0;">
  <strong>More information:</strong>
  {% for item in project.more_information %}
  <a href="{{ item.url }}" target="_blank">{{ item.name }}</a>
  {% unless forloop.last %}|{% endunless %}
  {% endfor %}
  </p>
{% endif %}

</div>

{% endfor %}



<h3 id="mentalhealth" style="margin-top: 30px;">Mental Health Promotion</h3>

<p>
Representative projects focusing on mental health promotion among diverse populations and settings.
</p>

{% for project in site.data.projects.mental_health %}

<div class="project-card" style="border:1px solid #d9d9d9; background:#f7f7f7; border-radius:10px; padding:18px 20px; margin-bottom:28px; box-shadow:0 1px 3px rgba(0,0,0,0.06);">

  {% if project.image %}
  <img src="{{ site.baseurl }}{{ project.image }}"
  alt="{{ project.title }}"
  class="img-responsive"
  style="max-width:420px; border-radius:8px; margin-bottom:12px; display:block; margin-left:auto; margin-right:auto;">
{% endif %}

<h4 style="margin-top:0; margin-bottom:8px; font-weight:600;">
  {{ project.title }}
  </h4>

<p style="margin-bottom:6px;">
  <strong>Funder:</strong> {{ project.funder }} <br>
  <strong>Duration:</strong> {{ project.duration }}
</p>

{% if project.more_information %}
  <p style="margin-bottom:0;">
  <strong>More information:</strong><br>
  {% for item in project.more_information %}
  <a href="{{ item.url }}" target="_blank">{{ item.name }}</a>
  {% unless forloop.last %} &nbsp;|&nbsp; {% endunless %}
  {% endfor %}
  </p>
  {% endif %}

</div>

{% endfor %}



<h3 id="SCI" style="margin-top: 30px;">Spinal Cord Injury Rehabilitation</h3>

<p>
Projects emphasizing rehabilitation and psychosocial outcomes among people living with spinal cord injury.
</p>

{% for project in site.data.projects.sci %}

<div class="project-card" style="border:1px solid #d9d9d9; background:#f7f7f7; border-radius:10px; padding:18px 20px; margin-bottom:28px; box-shadow:0 1px 3px rgba(0,0,0,0.06);">

  {% if project.image %}
  <img src="{{ site.baseurl }}{{ project.image }}"
  alt="{{ project.title }}"
  class="img-responsive"
  style="max-width:420px; border-radius:8px; margin-bottom:12px; display:block; margin-left:auto; margin-right:auto;">
{% endif %}

<h4 style="margin-top:0; margin-bottom:8px; font-weight:600;">
  {{ project.title }}
  </h4>

<p style="margin-bottom:6px;">
  <strong>Funder:</strong> {{ project.funder }} <br>
  <strong>Duration:</strong> {{ project.duration }}
</p>

{% if project.more_information %}
  <p style="margin-bottom:0;">
  <strong>More information:</strong><br>
  {% for item in project.more_information %}
  <a href="{{ item.url }}" target="_blank">{{ item.name }}</a>
  {% unless forloop.last %} &nbsp;|&nbsp; {% endunless %}
  {% endfor %}
  </p>
{% endif %}

</div>

{% endfor %}



<h3 id="teaching" style="margin-top: 30px;">Teaching &amp; Learning Grants</h3>

<p>
Teaching-related grants and projects, such as curriculum innovation,new teaching tools, or education research.
</p>

{% for project in site.data.projects.teaching %}

<div class="project-card" style="border:1px solid #d9d9d9; background:#f7f7f7; border-radius:10px; padding:18px 20px; margin-bottom:28px; box-shadow:0 1px 3px rgba(0,0,0,0.06);">

  {% if project.image %}
  <img src="{{ site.baseurl }}{{ project.image }}"
  alt="{{ project.title }}"
  class="img-responsive"
  style="max-width:420px; border-radius:8px; margin-bottom:12px; display:block; margin-left:auto; margin-right:auto;">
{% endif %}

<h4 style="margin-top:0; margin-bottom:8px; font-weight:600;">
  {{ project.title }}
  </h4>

<p style="margin-bottom:6px;">
  <strong>Funder:</strong> {{ project.funder }} <br>
  <strong>Duration:</strong> {{ project.duration }}
</p>

{% if project.more_information %}
  <p style="margin-bottom:0;">
  <strong>More information:</strong><br>
  {% for item in project.more_information %}
  <a href="{{ item.url }}" target="_blank">{{ item.name }}</a>
  {% unless forloop.last %} &nbsp;|&nbsp; {% endunless %}
  {% endfor %}
  </p>
  {% endif %}

</div>

{% endfor %}
