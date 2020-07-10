---
layout: page
title: Projects
description: Science, machine learning, data analytics, and coding
image: assets/images/fusion_plasma2.jpg
nav-menu: true
show_tile: true

---


  {% for post in site.posts %}
      {% if post.title != 404 %}
  <ul>
     <a href="{{ post.url }}">  <h2>{{ post.title }}</h2> </a>
      {{post.description}}
      <br/>
      <a href="{{ post.url }}">
        <img src="{{site.url}}{{post.image}}" alt="project image" style="width:28%;height:28%;"> 
      </a>

<hr>


  </ul>
      {% endif %}
  {% endfor %}

