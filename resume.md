---
layout: page
title: Resume
featured_image:
---

<!-- Trigger the Modal -->

<img class="myImages" id="myResume" src="/assets/images/respage1.jpg" alt="Page 1" style="width:100%;max-width:300px" align="center">
<img class="myImages" id="myResume" src="/assets/images/respage2.jpg" alt="Page 2" style="width:100%;max-width:300px" align="center">
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>

<script>

var modal = document.getElementById('myModal');
var images = document.getElementsByClassName('myImages');
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");

for (var i = 0; i < images.length; i++) {
  var img = images[i];
  img.onclick = function(evt) {
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }
}

var span = document.getElementsByClassName("close")[0];

span.onclick = function() {
  modal.style.display = "none";
}

</script>

Download in PDF format [here](https://github.com/aisaadaniya/aisaportfolio/raw/master/assets/files/Alejandro%20Isa%20Adaniya%20-%20Resume.pdf).

Last updated: 17/10/2018
