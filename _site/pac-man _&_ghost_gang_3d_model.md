---
title: Pac-man 3D Model Animation
date: Created
layout: base
tags:
  - Animation
  - Project
---

<div class="videoWrapper ratio-16-9">
    <!-- iframe below is Copy & Pasted from YouTube replace with your own -->
    <iframe width="853" height="480" src="/images/pac-man_3d_model_animation.mp4" frameborder="0" allowfullscreen></iframe>
</div><!-- end .videoWrapper -->

<div class="project_text">
    <h2>Pac-man & Ghost Gang 3D Model</h2>
     <p>
        <strong>2022<br>Cinema 4D</strong>
     </p>
</div>

<div class="project_bio">
    <p>
        In my animation class, I created a dynamic 3D animation featuring Pac-man and his iconic enemies. 
        Utilizing Cinema 4D, I skillfully modeled, animated, and rendered each character to bring them to 
        life. The attention to detail in each movement and facial expression adds depth to the characters 
        and makes them truly captivating to watch. The use of 3D technology allowed me to create a visually 
        engaging and immersive experience for the viewer. Overall, this project was an exciting opportunity 
        to flex my animation skills and showcase my creativity.
    </p>
</div>

<section class="collections">
  <h1>Other Animation Projects</h1>
  <ul>
    {% for Animation in collections.Animation %}      
      <li><a href="{{Animation.url}}">{{Animation.data.title}}</a></li>
    {% endfor %}
  </ul>
</section>