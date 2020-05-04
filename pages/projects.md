---
layout: page-fullwidth
title: "Projects"
subheadline: "Showcase of my works"
# teaser: "Get in touch with me? Use the contact form."
permalink: "/projects/"
header:
   image_fullwidth: "header_roadmap_2.jpg"
---
<!--more-->

<div class="row t60">
    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}/amazon-robot/amazon1.png" alt="">
        <p> Amazon Warehouse: <a href="https://kurshakuz.github.io/projectsamazon-warehouse/">Project</a></p>
    </div>

    <div class="medium-6 columns b30">
        <img src="{{ site.urlimg }}webdesign_screenshot_jcorneille.jpg" alt="">
        <p> Website: <a href="http://jcorneille.de">Grafik Design Jeannette Corneille</a></p>
    </div>
</div>


<div class="row t30">
    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_stilwandel.jpg" alt="">
        <p>Website: <a href="http://stilwandel-koeln.de">Stilwandel-Koeln.de</a></p>
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_tarnkappe.jpg" alt="">
        <p>Website: <a href="http://tarnkarppe.info">Tarnkappe.info</a></p>
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns">
        <img src="{{ site.urlimg }}webdesign_screenshot_schriefer.jpg" alt="">
        <p>Website: <a href="http://www.psychotherapie-schriefer.de/">Praxis für psychologische Psychotherapie Simone Schriefer</a></p>
    </div><!-- /.medium-4.columns -->
</div><!-- /.row -->


<ul>
    {% for post in site.categories.portfolio %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>