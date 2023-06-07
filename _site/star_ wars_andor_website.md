---
title: “Andor” Website
date: Created
layout: base
tags:
  - Web 
  - Development
  - Project
---

<div class="project_images">
  <img src="/images/andor_about_page.jpg" alt="andor_about_page">
</div>

<div class="project_text">
  <h2>“Star Wars: Andor” Website</h2>
  <p>
      <strong>2022<br>Figma, Atom, Github</strong>
  </p>
</div>

<div class="project_bio">
  <p>
    For my web design class, I designed and developed a two-page website about 
    the "Star Wars: Andor" series that I love. The website aims to provide a 
    clear and comprehensive home page and episodes' guide for fans of the show. 
    To achieve this, I first prototyped the layout using Figma and then translated 
    it into a functional web page using HTML, CSS, and JS with Atom. The design 
    and layout were carefully thought out to enhance the user experience and create 
    an immersive environment for fans of the show. Click on the links below to see 
    the working website and Prototype on Figma.
  </p>
</div>

<div class="project_text">
  <p>
      <strong>Link to Website: <a href="https://alecardena.github.io/mmp240/midterm/index.html" target="_blank" rel="noopener noreferrer">https://alecardena.github.io/mmp240/midterm/index.html</a></strong>  
  </p>
  <p>
      <strong>Link to Figma: <a href="https://www.figma.com/file/lFrpVZgF1AQ6CklaypLMH3/Andor-Website-Mock-Up-%26-Moodboard?type=design&t=VHQ9FKXBRc5wMlt3-1" target="_blank" rel="noopener noreferrer">https://www.figma.com/file/lFrpVZgF1AQ6CklaypLMH3/Andor-Website-Mock-Up-%26-Moodboard?type=design&t=VHQ9FKXBRc5wMlt3-1</a></strong>  
  </p>
</div>

<section class="collections">
  <h1>Other Web Development Projects</h1>
  <ul>
    {% for Web in collections.Web %}      
      <li><a href="{{Web.url}}">{{Web.data.title}}</a></li>
    {% endfor %}
  </ul>
</section>