---
layout: people
order: 1
title: Meet the People
name: "Xiaojie Qiu"
position: "Principal Investigator"
current: true
headshot: "xiaojie.jpg"
google_scholar: "https://scholar.google.com/citations?user=XlMd8TAAAAAJ&hl=en"
GitHub: "https://github.com/Xiaojieqiu"
cv_url: "assets/PDFs/xiaojie-cv.pdf"
email: "xiaojie@stanford.edu"
bio: "I’m an Assistant Professor at the Department of Genetics, the BASE program, and the Department of Computer Science at Stanford. 
    I worked with Dr. Cole Trapnell at the University of Washington during my PhD to develop Monocle 2 and 3 for pseudotemporal trajectory analysis of scRNA-seq data. 
    During my post-doc, I worked with Dr. Jonathan Weissman initially at UCSF and then Whitehead Institute and MIT to develop <a href='https://github.com/aristoteleo/dynamo-release'>Dynamo</a> 
    to reconstruct RNA velocity vector field and make reprogramming and in silico perturbation predictions with metabolic labeling enabled single-cell RNA-seq. I recently also
    lead the development of <a href='https://github.com/aristoteleo/spateo-release'>Spateo</a>, for advanced spatiotemporal modeling of single cells. My lab is currently focused 
    mostly on predictive modeling of single cells through a uniuqe synthesis of genomics and machine learning. Outside the lab, I like going to the gym, run and read all kinds of books."
twitter: "https://twitter.com/Xiaojie_Qiu"
---

<div class="bigspacer"></div>
<h3>Papers</h3>
<div class="spacer"></div>
<ul>
    {% assign sorted_array = site.papers | sort: "rank" %}
    {% for paper in sorted_array %}
        <li><a href="{{ paper.url }}">{{ paper.paper_title }}</a></li>
    {% endfor %}
</ul>
