---
layout: page
title: Resume
featured_image:
---

<!-- Trigger the Modal -->

<img class="myImages" id="myImg" src="/assets/images/respage1.jpg" alt="Page 1" style="width:100%;max-width:300px" align="center">
<img class="myImages" id="myImg" src="/assets/images/respage2.jpg" alt="Page 2" style="width:100%;max-width:300px" align="center">
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>

<script>
// create references to the modal...
var modal = document.getElementById('myModal');
// to all images -- note I'm using a class!
var images = document.getElementsByClassName('myImages');
// the image in the modal
var modalImg = document.getElementById("img01");
// and the caption in the modal
var captionText = document.getElementById("caption");

// Go through all of the images with our custom class
for (var i = 0; i < images.length; i++) {
  var img = images[i];
  // and attach our click listener for this image.
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

Download in PDF format *here*.
