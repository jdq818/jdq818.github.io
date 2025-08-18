---
layout: page
permalink: /research/index.html
title: Research
---

Notes, demos, and links.

# Demos

## Vascular wall motion
<style>
   .modal {
      display: none;
      position: fixed;
      z-index: 9999;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.8);
   }
 
   .modal-image {
      display: block;
      max-width: 90%;
      max-height: 90%;
      margin: auto;
      margin-top: 5%;
   }
</style>

<div class="third">
<img src="https://jdq818.github.io/images/research/vesselwall.gif" alt="image" onclick="showModal(this)">
</div>

<script>
   function showModal(image) {
      var modal = document.getElementById("modal");
      var modalImage = document.getElementById("modal-image");
      modal.style.display = "block";
      modalImage.src = image.src;
   }
 
   function hideModal() {
      var modal = document.getElementById("modal");
      modal.style.display = "none";
   }
</script>
<br>