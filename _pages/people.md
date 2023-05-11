---
title: People
layout: splash
permalink: /people/
classes: wide
sitemap: false
---

<style>
  .flex-container {
    padding: 10px;
    display: flex;
    /* justify-content: center; */
  }
  .wrap {
    flex-wrap: wrap;
  }
  .flex-item {
    /* background: LightGray; */
    flex: 0 0 calc(33% - 20px);
    min-width: 200px;
    padding: 5px;
    /* max-width: 200px; */
    margin: 10px;
    
    /* color: white; */
  } 
</style>

## Team

<div class="flex-container wrap">
  {% for member in site.data.people %}
    {% if member.active and member.staff %}
      <div class="flex-item">
        {% include member-overview.html image=member.image name=member.name role=member.role %}
      </div>
    {% endif %}
  {% endfor %}
</div>

## Students

<div class="flex-container wrap">
  {% for member in site.data.people %}
    {% if member.active %}
      {% unless member.staff %}
        <div class="flex-item">
          {% include member-overview.html image=member.image name=member.name role=member.role %}
        </div>
      {% endunless %}
    {% endif %}
  {% endfor %}
</div>

## Alumni

<div class="flex-container wrap">
  {% for member in site.data.people %}
    {% unless member.active %}
      <div class="flex-item">
        {% include member-overview.html image=member.image name=member.name role=member.role %}
      </div>
    {% endunless %}
  {% endfor %}
</div>
