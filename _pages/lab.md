---
layout: page
title: members
permalink: /members/
nav: true
nav_order: 2
horizontal: true
---

<div class="lab-members">
  {% for member in site.data.lab_members %}
  <div class="lab-member-card">
    <img src="{{ member.image | relative_url }}" class="lab-photo" alt="{{ member.name }}">
    <h3>{{ member.name }}</h3>
    <p><strong>{{ member.role }}</strong></p>
    <p>{{ member.bio }}</p>
  </div>
  {% endfor %}
</div>
