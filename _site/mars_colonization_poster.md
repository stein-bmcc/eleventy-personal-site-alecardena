---
title: Mars Exploration Poster
date: Created
layout: base
tags:
  - Print
  - Project
---

<div class="project_images_2">
    <img src="/images/mars_exploration_poster.png" alt="mars_exploration_poster">
 </div>
 
 <div class="project_text">
    <h2>Mars Colonization Poster</h2>
    <p>
        <strong>2022<br>Adobe Illustrator, Adobe Photoshop</strong>
    </p>
</div>

<div class="project_bio">
    <p>
        I designed this space-themed poster using a combination of Illustrator and Photoshop. 
        The concept behind the poster was to depict what Mars colonization might look like in 
        the future. The artwork features three different domed cities set against a backdrop 
        of mountain ranges. To create the poster, I sourced images of three city skylines and 
        used Photoshop to create outlines of each skyline. I then transferred these outlines 
        to Illustrator and used various shapes to create the mountain ranges, sky, and domes. 
        To capture the distinctive red color of Mars, I used a palette that mainly featured 
        shades of red. For the font, I selected Bauhaus 93 as it complemented the sci-fi/futuristic 
        feel of the poster.
    </p>
</div>

<section class="collections">
  <h1>Other Print Design Projects</h1>
  <ul>
    {% for Print in collections.Print %}      
      <li><a href="{{Print.url}}">{{Print.data.title}}</a></li>
    {% endfor %}
  </ul>
</section>