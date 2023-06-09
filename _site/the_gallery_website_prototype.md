---
title: “The Gallery” Website Prototype
date: Created
layout: base
tags:
  - Web 
  - Development
  - Project
---

<div class="project_images_2">
    <img src="/images/the_gallery_website_home_page.png" alt="the_gallery_website_home_page">
 </div>

 <div class="project_text">
    <h2>“The Gallery” Website Prototype</h2>
    <p>
        <strong>2022<br>Figma</strong>
    </p>
</div>

<div class="project_bio">
    <p>
        In my Multimedia class, I designed a user interface for an e-commerce art website called 
        "The Gallery" using Figma. My concept was to create a platform where people can purchase 
        a diverse range of artworks including pottery, posters, paintings, and more. The website 
        also features artists’ portfolios and interactive features to connect customers with the 
        artists. I created a comprehensive project proposal outlining the development process and 
        created a prototype, wireframe, and site map using Figma. Click on the link below to see 
        the complete design and layout.
    </p>
</div>

 <div class="project_text">
    <p>
        <strong>Link to Figma: <a href="https://www.figma.com/file/IbqdcRNEottTG2sea2o2JZ/%E2%80%9CThe-Gallery%E2%80%9D-Website-Prototype?node-id=0%3A1&t=Agpu6d1a0aF5SGDa-1" target="_blank" rel="noopener noreferrer">https://www.figma.com/file/IbqdcRNEottTG2sea2o2JZ/%E2%80%9CThe-Gallery%E2%80%9D-Website-Prototype?node-id=0%3A1&t=Agpu6d1a0aF5SGDa-1</a></strong>
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