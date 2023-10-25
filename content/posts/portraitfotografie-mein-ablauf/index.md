+++
title = "Portraitfotografie > mein Ablauf "
date = "2023-10-25"
draft = false
pinned = false
image = "screenshot-2023-10-25-at-21.39.12.jpeg"
+++
<script src="https://unpkg.com/image-compare-viewer/dist/image-compare-viewer.min.js"></script>

<link href="https://unpkg.com/image-compare-viewer/dist/image-compare-viewer.min.css" rel="stylesheet" type="text/css" />

<div id="image-compare">
  <img src="mael-before.jpg" alt="" style="max-width: none; height: 70%;" />
  <img src="mael-after.jpg" alt="" style="max-width: none; height: 70%;" />
</div>

<script>
  const element = document.getElementById("image-compare");
  const viewer = new ImageCompare(element).mount();
  
  // Hier versuchen wir, den Slider ganz rechts zu bewegen
  viewer.setPosition(1); // Hierbei ist 1 die vollständig rechte Position
</script>
