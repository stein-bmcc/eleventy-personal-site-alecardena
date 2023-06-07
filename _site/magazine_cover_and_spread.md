---
title: Magazine Cover & Spread
date: Created
layout: base
tags:
  - Print
  - Project
---

<div class="project_images">
    <div class="project_images_2">
        <img src="/images/magazine_cover.png" alt="magazine_cover">
    </div>
        <div class="spread">
            <img src="/images/magazine_spread_1.png" alt="magazine_spread_1">
            <img src="/images/magazine_spread_2.png" alt="magazine_spread_2">
        </div>
 </div>
 

 <div class="project_text">
    <h2>Magazine Cover & Spread</h2>
    <p>
        <strong>2022<br>Adobe Indesign, Adobe Photoshop</strong>
    </p>
</div>

<div class="project_bio">
    <p>
        For this project in my Multimedia class, I designed a magazine cover and 
        spread featuring an upcoming “Star Wars” game. Using InDesign and Photoshop, 
        I carefully selected and edited images to perfectly capture the essence of 
        the game. The color scheme I chose reflects the futuristic and sci-fi themes 
        of the game, while the font I used for the main header in the spread adds to 
        the overall aesthetic. I combined the text and images seamlessly in InDesign, 
        resulting in a visually appealing and cohesive layout.
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