---
title: The Adventures  of Kron the Penguin Animation
date: Created
layout: base
tags:
  - Animation
  - Project
---

<div class="videoWrapper ratio-16-9">
    <!-- iframe below is Copy & Pasted from YouTube replace with your own -->
    <iframe width="853" height="480" src="/images/the_adventures_of_kron_the_penguin_animation.mp4" frameborder="0" allowfullscreen></iframe>
</div><!-- end .videoWrapper -->

<div class="project_text">
    <h2>The Adventures of Kron the Penguin</h2>
     <p>
        <strong>2022<br>Adobe Animate, Audacity</strong>
     </p>
</div>

<div class="project_bio">
    <p>
        For this project in my animation class, I was tasked with creating a 2D character animation 
        using Adobe Animate. I decided to create an original character design and story to bring to 
        life. After completing the animation, I used Audacity to create a custom soundtrack that 
        complemented the animation's visuals and mood. The final product was a cohesive and engaging 
        animation that showcased my skills in both design and sound production.
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