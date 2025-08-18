---
layout: page
permalink: /hobbies/index.html
title: Hobbies
---

I would like record my feelings and life by writings.

# Hobbies

## Poems
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
<img src="https://jdq818.github.io/hobbies/poems/Contemplation.jpg" alt="image" onclick="showModal(this)">
<img src="https://jdq818.github.io/hobbies/poems/TheDist.jpg" alt="image" onclick="showModal(this)">
<img src="https://jdq818.github.io/hobbies/poems/Firstsnow.jpg" alt="image" onclick="showModal(this)"><br>
</div>
<img src="https://jdq818.github.io/hobbies/poems/Monks.jpg" alt="image" onclick="showModal(this)">
</div>
<div id="modal" class="modal" onclick="hideModal()">
  <img id="modal-image" class="modal-image">
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

## Readings
<br>