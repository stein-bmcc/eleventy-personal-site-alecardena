---
title: Surrealism Postcard
date: Created
layout: base
tags:
  - Print
  - Project
---

<div class="surrealism_project_images">
    <img src="/images/surrealism_postcard_front.png" alt="surrealism_postcard_front">
    <img src="/images/surrealism_postcard_back.png" alt="surrealism_postcard_back">
</div>

<div class="project_text">
    <h2>Surrealism Museum Postcard</h2>
    <p>
        <strong>2022<br>Adobe Indesign</strong>
    </p>
</div>

<div class="project_bio">
    <p>
        This postcard was created for a hypothetical museum exhibit on Surrealism at the 
        Museum of Modern Art. It was  a project for my Digital Graphic Design class. The 
        front of the postcard features a wall with different paintings hanging on it, 
        representing the Surrealist movement. To create a realistic effect, the paintings 
        were placed in frames, and the background of the wall was chosen to resemble a 
        wallpaper style of the 1920s. The color and font were carefully chosen to fit the 
        time period and enhance the overall design. The layout was created using InDesign, 
        and the result is a well-crafted postcard that effectively conveys the message of 
        the museum exhibit.
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