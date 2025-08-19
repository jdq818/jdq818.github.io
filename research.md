---
layout: page
permalink: /research/index.html
title: Research
---

Notes, demos, and links.

# Demos
## Vascular simulations

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

<div class="third">
<img src="https://jdq818.github.io/images/research/FSI/vesselwall.gif" alt="image" onclick="showModal(this)">
<img src="https://jdq818.github.io/images/research/FSI/bloods.gif" alt="image" onclick="showModal(this)">
<img src="https://jdq818.github.io/images/research/FSI/lesion.gif" alt="image" onclick="showModal(this)">
</div>
<br>

## Vascular image segmentation
<div class="third">
<img src="https://jdq818.github.io/images/research/Mesh/seg.png" alt="image" onclick="showModal(this)">
</div>

## Vascular mesh
<div class="third">
<img src="https://jdq818.github.io/images/research/Mesh/meshquality.png" alt="image" onclick="showModal(this)">
</div>

<div class="third">
<img src="https://jdq818.github.io/images/research/Mesh/vsmesh.gif" alt="image" onclick="showModal(this)">
</div>

## Coroanry motion

<div class="third">
<img src="https://jdq818.github.io/images/research/Mesh/cmotion.gif" alt="image" onclick="showModal(this)">
<br>
</div>

## Simulation

<div class="third">
<img src="https://jdq818.github.io/images/research/Mesh/simulation_sten_e.gif" alt="image" onclick="showModal(this)">
<br>
</div>

<div class="third">
<img src="https://jdq818.github.io/images/research/Mesh/Cycle.png" alt="image" onclick="showModal(this)">
<br>
</div>

# Notes
## Algorithms
### Segmentation

| Publication| Title | Link | Code |
|------|------|:----:|------|
|TMI 25.07.18 | SegMamba-V2: Long-range Sequential Modeling Mamba For General 3D Medical Image Segmentation |  [Paper](https://ieeexplore.ieee.org/document/11084842) | [Code](https://github.com/ge-xing/SegMamba-V2); |

### Registration

| Publication| Title | Link | Code |
|------|------|:----:|------|
|TMI 25.07.03 | Joint Shape Reconstruction and Registration via a Shared Hybrid Diffeomorphic Flow |  [Paper](https://ieeexplore.ieee.org/document/11069310) | -; |


## Theory
### Transformer

| Publication| Title | Link | Code |
|------|------|:----:|------|
|TPAMI 25.09| Taylor-Series-Expansion-Based Vision Transformer Models |  [Paper](https://ieeexplore-ieee-org.mpu.idm.oclc.org/document/11030317/) | -; |

### Diffusion

| Publication| Title | Link | Code |
|------|------|:----:|------|
TPAMI 25.07.03 | Temporal Feature Matters: A Framework for Diffusion Model Quantization |  [Paper](https://ieeexplore.ieee.org/document/11068163) | -; |

### Others

| Publication| Title | Link | Code |
|------|------|:----:|------|
|Arxiv 24.01.17 | Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model |  [Paper](https://arxiv.org/abs/2403.03234) | [Code](https://github.com/wangtz19/NetMamba); |

# Links
## Zmic
[Zmic](https://zmiclab.github.io/index.html)<br>
## Brain-Heart-Gut Axis
[Brain-Heart-Gut Axis](http://supramarginal.top/pubmed)
By Dr. Bai Shuwei <br>