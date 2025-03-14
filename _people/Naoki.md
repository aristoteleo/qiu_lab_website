---
layout: people
order: 9
title: Meet the People
name: "Naoki Konno"
position: "Incoming Post-doc, PhD"
current: true
headshot: "naoki.JPG"
google_scholar: "https://scholar.google.co.jp/citations?user=TY6BaUEAAAAJ&hl=en"
GitHub: "https://github.com/UTNK"
website: "https://sites.google.com/view/naoki-konno/"
bio: "Hi, I'm an incoming postdoc at Dr. Xiaojie Qiu's lab at Stanford. I aim to decipher evolutionary patterns and rules in developmental processes of multicellular organisms by leveraging single-cell and spatial omics technologies. I received my PhD from the University of Tokyo, where I studied predictability in microbial genome evolution using phylogenetics, machine learning, and wet-lab approaches. In my free time, I enjoy walking outdoors and observing birds and other wildlife in their natural habitats."
twitter: "https://x.com/utnk1"
---

<div class="bigspacer"></div>
{% if page.website != "" %}
<div class="row">
    <div class="col-md-3">
        <h3>Website</h3>
    </div>
    <div class="col-md-9">
        <p><a href="{{ page.website }}">{{ page.website }}</a></p>
    </div>
</div>
<div class="bigspacer"></div>
{% endif %}
<h3>Papers</h3>
<div class="spacer"></div>
<ul>
    {% assign sorted_array = site.papers | sort: "rank" %}
    {% for paper in sorted_array %}
        {% if paper.author_list contains "Naoki Konno" %}
            <li><a href="{{ paper.url }}">{{ paper.paper_title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
