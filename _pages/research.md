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


1. Innovative Integration of Smart Wearable Rings and Conversational Fabric Bots for Enhancing Mental Health in Patients with Inflammatory Arthritis: A Pragmatic Randomized Clinical Trial.

2. Chatbot-Delivered Mindfulness-based Stress Reduction Program for Enhancing Athletes’ Sports Performance and Psychological Well-being.

3. The Impact of 'Digital Strolling' on Depression and Quality of Life of People with Severe Mobility Impairment. **RGC Healthy Longevity Catalyst Awards 2024**.

4. Evaluation of the Innovative Generative AI-based ‘Socratic Playground for Learning” in the Context of a Newly Developed Health Informatics Subject. PolyU (UGC), Teaching and Learning Grant.

5. Collaborative Development of Mental Health Promotion Activities for Primary School Students. PolyU (UGC), Teaching and Learning Grant.

6. ‘Sleep Equity for Global Health’—Promoting Healthy Sleep among Health Professionals. UGC Shanghai-Hong Kong University Alliance.
- Recruitment Poster:[**促进医护专业人员和医学专业学生睡眠健康**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/Ed_qsauSkoJOum2JdPc2MTIBRAKGj9qG0cfixM6K-Yu7AQ?e=CWtyFS)

7. Development and Evaluation of a Home-based Action Observation and Motor Imagery Intervention on Cognitive Function and Depression among Adults with Spinal Cord Injury: A Pilot Randomized Controlled Trial. UGC Fund, Ref. No. P0051299.

8. Effects of a Coping-Based Interactive Psychosocial Intervention for Teenagers with Adolescent Idiopathic Scoliosis: A Pilot Randomised Controlled Trial. UGC Fund, Ref. No.P0048819.

9. Digital Preventive Healthcare for People with Physical Disabilities: A Programme of Research. UGC – Strategic Hiring Scheme, Ref No. P0044765.

10. AI-driven Vaccine Communicator——智能疫苗助理: The impact of a Web-based psychoeducation programme with a motivational AI-based digital assistant on Covid-19 vaccine hesitancy in Hong Kong's population. Grant source: Health and Medical Research Fund, Food and Health Bureau, Commissioned Research on the Novel Coronavirus Disease (COVID-19).Project Ref No. COVID1903006.
- Conference Poster:
[**The Development of a Web-based Psychoeducation Programme with a MotivationalArtificial Intelligencebased Chatbot to Decrease Vaccine Hesitancy**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/Eb-M8Fzm5LRErH3WbN5YyVYBMzMhgwgxylPpavWn-OGNIQ?e=m8r9Rz) and [**Revisiting Attitudes Towards Covid-19 Vaccines Among Hong Kong Adults: Does The Individual Perception of Health Condition Matter?**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/EVjYuMdYsABDky8ECwT7CbUB_1bMq4W9iyUNHKPeWNKSUw?e=2VG7bN) in 2023 Yonsei International Nursing Conference
- Recruitment Poster:[**智能疫苗助理的成效研究**](https://connectpolyu-my.sharepoint.com/:b:/g/personal/20104257g_connect_polyu_hk/ER-jeualX7ZGgucmp4s57KcB381kGm4d6Wd7Zn_3ArrFoQ?e=9VBIiH)
- Award:[**Best Poster Presentation Award**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/EScu3Vc6ZmBGkvOF2XYoaNMBIKZp0xbKJiv34G3MASxolg?e=DmIAfJ) in 2023 Yonsei International Nursing Conference<br/> 
<br/> 

11. Chatbot-based mindfulness interventions for young adults with symptoms of depression: a feasibility study. Start-up Fund for RAPs under the Strategic Hiring Scheme. 1 January 2022-31 December 2023.
- Conference Poster: [**Chatbot-based Mindfulness Intervention for Young Adults with Symptoms of Depression: A Feasibility Study with Preliminary Effectiveness Testing**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/EU8e9VH4N9ZIons-K4piaNEBRCw55MraO5JHuWKkS51sxA?e=JKUGqB) and [**Development of a Mindfulness-based Chatbot on mental health promotion among College Students**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/EfVfNu9tk2hOlrc6AQYcGFUBA_wmsM25Fkx0_A9LqRvgzQ?e=vNG0lv) in 2023 Yonsei International Nursing Conference
- Recruitment Poster:[**由虛擬聊天機器人主導的靜觀減壓課程之研究**](https://polyuit-my.sharepoint.com/:i:/g/personal/menghe_polyu_edu_hk/EUrQ2p6CsXZKo2NaS4Y8PSwBlU5sMNOIgnnpxKfIzxjH5Q?e=2n9Dal)<br/> 
<br/> 

12. Effects of a Physical-Psychological Integrative (PPI) intervention on Physical inactivity, Depression and Chronic pain for Community-Dwelling Spinal Cord Injury Survivors: A Pilot Randomized Controlled Trial; **Health and Medical Research Fund—Research Fellowship Scheme**, 01/Sep/2021- 01/Sep/2023. Project No. 06200147.
- Conference Poster:[**Feasibility and Effectiveness of Artificial Intelligence-Driven Conversational Agents in Healthcare Interventions: A Systematic Review of Randomized Controlled Trials**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/EXUD8ajMsbFFs3_vtR0Z53AB21hzUfeEIIId5wjE_pZf2Q?e=oeLAZT) in 2023 Yonsei International Nursing Conference
- Recruitment Poster:[**身心綜合干預模式對脊髓損傷人士的效果研究招募計劃**](https://polyuit-my.sharepoint.com/:i:/g/personal/menghe_polyu_edu_hk/EXXnIWlCV4VNtyd4sexhPpIB6gkyDyO53nuh1zY-zURwaA?e=v2DMKv) 
- Award: [**Best Poster Presentation Award**](https://polyuit-my.sharepoint.com/:b:/g/personal/menghe_polyu_edu_hk/EX0AHSwoSB9Pl629VeMJbHABzrAwf6zM-54WFCoh1fiEVQ?e=XpRyNL) in 2023 Yonsei International Nursing Conference<br/> 
<br/> 

13. Effects of caregiver-administrated acupressure intervention for community-dwelling spinal cord injury survivors with constipation: A randomized controlled trial; **Hong Kong Government Chinese Medicine Development Fund**, 1 April 2022- 31/March 2024. (Project No. 20B2/033A).
- Conference Poster:[**Constipation and its related quality of life among community-dwelling spinal cord injury survivors: a cross-sectional study**](https://polyuit-my.sharepoint.com/:i:/g/personal/menghe_polyu_edu_hk/EbyOsgzaMEdHsesHfw5A37cB2fw81dgmNjbebhZBvPmDaQ?e=FZUblb) and [**Effect of Acupressure on Constipation in Community-dwelling People with Spinal Cord Injury: A Study Protocal for A Randomized Controlled Trial**](https://polyuit-my.sharepoint.com/:i:/g/personal/menghe_polyu_edu_hk/EVopGNnvMfZIiynFF_iSHekB24OLNv3qqWKBqm3JCyeThg?e=VTlfPM) in 13th Pan-Pacific Conference on Rehabilitation (2023)
- Recruitment Poster:[**便秘的中醫調理方法研究招募計劃**](https://polyuit-my.sharepoint.com/:i:/g/personal/menghe_polyu_edu_hk/ERSq3hWAbUdBrAM0eftRkfABKiqeHsTaSSmTu7XT39s-aQ?e=1NTuVv) <br/> 
<br/> 

14. Regular Sleep, Healthy Future - Promoting Sleep Health among College Students and Healthcare Professionals. Principal Investigator, 1 September, 2021 – 30 June, 2022, **UGC** Shanghai-Hong Kong University Alliance (SHUA) Open Bid Funding <br/>  
<br/> 

15. Greater Bay Area Nursing Forum: From Research to Clinical Practice Cum Workshop on Research Methods Training in Nursing. **Principal Investigator**, November 2021, **UGC** Guangdong-Hong Kong-Macao University Alliance (GHMUA) Open Bid Funding.<br/> 
<br/> 