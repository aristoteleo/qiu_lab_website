---
layout: people
order: 1
title: Xiaojie Qiu
name: "Xiaojie Qiu"
position: "Principal Investigator"
current: true
headshot: "xiaojie.jpg"
google_scholar: "https://scholar.google.com/citations?user=XlMd8TAAAAAJ&hl=en"
website: ""
GitHub: "https://github.com/Xiaojieqiu"
cv_url: "pdfs/team/xiaojie-cv.pdf"
email: "xiaojie@stanford.edu"
bio: "I’m an Assistant Professor at the Department of Genetics, the BASE program, and the Department of Computer Science at Stanford. 
    I worked with Dr. Cole Trapnell at the University of Washington during my PhD to develop Monocle 2 and 3 for pseudotemporal trajectory analysis of scRNA-seq data. 
    During my post-doc, I worked with Dr. Jonathan Weissman initially at UCSF and then Whitehead Institute and MIT to develop <a href='https://github.com/aristoteleo/dynamo-release'>Dynamo</a> 
    to reconstruct RNA velocity vector field and make reprogramming and in silico perturbation predictions with metabolic labeling enabled single-cell RNA-seq. I recently also
    lead the development of <a href='https://github.com/aristoteleo/spateo-release'>Spateo</a>, for advanced spatiotemporal modeling of single cells. My lab is currently focused 
    mostly on predictive modeling of single cells through a uniuqe synthesis of genomics and machine learning. Outside the lab, I like going to the gym, run and read all kinds of books."
---

<div class="bigspacer"></div>
<div class="head">Research</div>
<div class="post">
    <p>Dr. Xiaojie Qiu is currently an assistant professor at the Department of Genetics, the BASE program, and the Department of Computer Science at Stanford. Xiaojie’s Ph.D. work at University of Washington with Dr. Cole Trapnell made critical contributions to the field of single-cell genomics, exemplified by the development of Monocle ⅔ (monocle 2 & monocle 3) for pseudotemporal trajectory analysis of scRNA-seq data. In his post-doc at Whitehead Institute and MIT with Dr. Jonathan Weissman, Xiaojie developed Dynamo (aristoteleo/dynamo-release) to reconstruct RNA velocity vector field and make reprogramming and in silico perturbation predictions with metabolic labeling enabled single-cell RNA-seq. Recently he also leaded the development of a powerful toolkit, Spateo (aristoteleo/spateo-release), for advanced multi-dimensional spatiotemporal modeling of high definition spatial transcriptomics. </p>
    <p>The Qiu lab at Stanford started on Dec. 16, 2023. Xiaojie will continue leveraging his unique background in single-cell genomics, mathematical modeling, and machine learning to lead a research team that bridges the gap between the “big data” from single-cell and spatial genomics and quantitative/predictive modeling in order to address fundamental questions in mammalian cell fate transitions, especially those of heart evolution, development and disease. His research has been supported by the National Human Genome Research Institute, Chan Zuckerberg Institute, Impetus longevity grant, Arc institute and others.</p>
</div>
<div class="bigspacer"></div>
<div class="head">Papers</div>
<div class="spacer"></div>
<ul>
    {% assign sorted_array = site.papers | sort: "rank" %}
    {% for paper in sorted_array %}
        {% if paper.title == "selected work" %}
            <li><a href="{{ paper.url }}">{{ paper.paper_title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
