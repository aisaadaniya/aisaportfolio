---
layout: page
title: Resume
featured_image: /assets/images/pages/about.jpg
---

<!-- Images used to open the lightbox -->
<div class="row">
  <div class="column">
    <img src="/assets/images/respage1.jpg" onclick="openModal();currentSlide(1)" class="hover-shadow">
  </div>
  <div class="column">
    <img src="/assets/images/respage2.jpg" onclick="openModal();currentSlide(2)" class="hover-shadow">
  </div>
</div>

<!-- The Modal/Lightbox -->
<div id="myModal" class="modal">
  <span class="close cursor" onclick="closeModal()">&times;</span>
  <div class="modal-content">

    <div class="mySlides">
      <div class="numbertext">1 / 2</div>
      <img src="img1_wide.jpg" style="width:100%">
    </div>

    <div class="mySlides">
      <div class="numbertext">2 / 2</div>
      <img src="img2_wide.jpg" style="width:100%">
    </div>

    <!-- Next/previous controls -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>

    <!-- Caption text -->
    <div class="caption-container">
      <p id="caption"></p>
    </div>

    <!-- Thumbnail image controls -->
    <div class="column">
      <img class="demo" src="img1.jpg" onclick="currentSlide(1)" alt="Page 1">
    </div>

    <div class="column">
      <img class="demo" src="img2.jpg" onclick="currentSlide(2)" alt="Page 2">
    </div>

  </div>
</div>

Download in PDF format *here*.
