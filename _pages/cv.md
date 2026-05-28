---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech., Electronics & Communication Engineering, Indian Institute of Technology (IIT) Roorkee, 2020 — GPA: 9.23/10.0
* Ph.D., Computer Science (Computer Architecture), University of Virginia, 2027 (expected) — GPA: 3.88/4.0
  * Advisor: Prof. Kevin Skadron

Industry Experience
======
<ul>{% for post in site.work_exp reversed %}{% if post.type == "Industry" %}
  {% include archive-single-workexp-cv.html %}
{% endif %}{% endfor %}</ul>

Research Projects
======
<ul>{% for post in site.work_exp reversed %}{% if post.type == "Research" %}
  {% include archive-single-workexp-cv.html %}
{% endif %}{% endfor %}</ul>

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks and Presentations
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Awards and Achievements
======
* Selected to participate in CRA-WP Grad Cohort Workshop for Women, San Francisco, USA, 2023
* UVA Engineering Distinguished Fellowship 2022 (awarded to top Ph.D. applicants)
* Semi-finalist, Swadeshi Microprocessor Challenge 2020–21 (RISC-V based prototype for autonomous emergency distress system)
* Honda Y-E-S Award 2018; Y-E-S Plus Scholarship 2019 (research internship in Japan)
* Quarter-finalist, India Innovation Challenge Design Contest (IICDC) 2018, Texas Instruments
* 1988 Batch Award 2017 (undergraduate academic merit award, IIT Roorkee)
* First prize in Spectrum (circuit design), Third prize in Ideaz (innovative IoT applications), Tech Fest IIT Roorkee 2017

Service and Leadership
======
* Artifact Evaluation Committee Member, ISCA 2024, 2025
* Steering Committee Member, Computer Architecture Student Association (CASA), 2025 — leading the Computer Architecture Long-term Mentorship (CALM) program
* Co-organized Systems Interest Group (SIG) meetings, University of Virginia (Nov 2022 – May 2024)
* Mentored junior PhD student on CS doctoral program navigation, CS Graduate Student Group, Fall 2024 – Fall 2025
* Mentored CS undergraduate on graduate school applications, Engineering Grad School Mentor Program, Fall 2024 – Fall 2025
* Rise Together, Charlottesville, VA — assisted high school students with US college applications (Oct 2023 – April 2024)
* SOPAN, IIT Roorkee — weekly educational outreach for primary and middle school students in nearby rural village (Aug 2018 – May 2020)
* Unnat Bharat Abhiyan, IIT Roorkee — leveraged IIT technical expertise for rural development initiative (Sep 2016 – May 2018)
* Student Mentorship Programme, IIT Roorkee — mentored 12 first-year students (Aug 2018 – May 2020)
