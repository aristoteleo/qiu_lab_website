---
layout: people
title: Meet the People
name: "Yifan Lu"
position: "Visiting Researcher"
current: true
headshot: "yifan.jpeg"
bio: "I am currently a visiting Ph.D. student at Wuhan University, specializing in Information and Communication Engineering under the guidance of Prof. Jiayi Ma. My earlier research 
    focused on computer vision and pattern recognition, particularly in 3D vision and feature matching. Intrigued by computational biology, I've shifted my interests towards the 
    integration of spatial transcriptomics and RNA velocity in single cells, and actively expanding my knowledge in biology. Beyond academics, I enjoy activities like ping pong 
    and exploring new places through travel."
twitter: ""
---

<div class="bigspacer"></div>
<h3>Papers</h3>
<div class="spacer"></div>
<ul>
    {% assign sorted_array = site.papers | sort: "rank" %}
    {% for paper in sorted_array %}
        {% if paper.author_list contains "Yifan Lu" %}
            <li><a href="{{ paper.url }}">{{ paper.paper_title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
