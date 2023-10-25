+++
title = "Portraitfotografie > mein Ablauf "
date = "2023-10-25"
draft = false
pinned = false
image = "screenshot-2023-10-25-at-21.39.12.jpeg"
+++
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .box {
            border-radius: 100px;
            margin: 10px 0;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .blue-box {
            background: #98C1D9;
            width: 3056px;
            height: 6468px;
        }
        .dark-box {
            background: #293241;
            width: 2767px;
        }
        .content-box {
            width: 2409.84px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        .text {
            color: white;
            font-family: 'Inter', sans-serif;
            word-wrap: break-word;
        }
        .large-text {
            font-size: 200px;
            font-weight: 700;
        }
        .medium-text {
            font-size: 130px;
            font-weight: 600;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box blue-box"></div>
        <div class="box dark-box" style="height: 633.79px;"></div>
        <div class="box dark-box" style="height: 1446.69px;"></div>
        <div class="content-box" style="height: 1068.87px;">
            <span class="text large-text">Vignetten</span>
            <span class="text medium-text">Background separation</span>
            <span class="text medium-text">>Highlights runter<br> >Texture runter<br> >Clarity runter<br> >Color curve adjustments<br> >Radiergummi</span>
        </div>
        <div class="box dark-box" style="height: 678.10px;"></div>
        <div class="content-box" style="height: 732.85px;">
            <span class="text large-text">Basic:</span>
            <span class="text medium-text">Auto - danach anpassen<br> Denoise</span>
        </div>
        <div class="box dark-box" style="height: 951.66px;"></div>
        <div class="content-box" style="height: 850.30px;">
            <span class="text large-text">Auge schärfen</span>
            <span class="text medium-text">new Layer<br>Sharpening tool<br>sample all Layers, protect detail</span>
        </div>
        <div class="box dark-box" style="height: 633.79px;"></div>
        <div class="box" style="height: 511.75px; text-align: center; background: #293241;">
            <span class="text large-text" style="font-size: 430px; font-weight: 800;">Photoshop</span>
        </div>
        <div class="box dark-box" style="height: 951.66px;"></div>
        <div class="content-box" style="height: 703.13px;">
            <span class="text large-text">Auge aufhellen</span>
            <span class="text medium-text">Elliptical tool - Auge auswählen<br>Adjustment Layer - Levels<br>Blend mode Linear Dodge (Add)<br>Subtract from mask (nicht Auge)</span>
        </div>
    </div>
</body>
</html>


-------------------


<script src="https://unpkg.com/image-compare-viewer/dist/image-compare-viewer.min.js" /></script>

<link href="https://unpkg.com/image-compare-viewer/dist/image-compare-viewer.min.css" rel="stylesheet" type="text/css" />

<div id="image-compare">
<img src="mael-before.jpg" alt="" style="max-width: none; height: 100%;" />
<img src="mael-after.jpg" alt="" style="max-width: none; height: 100%;" />
</div>

<script>
const element = document.getElementById("image-compare");
const viewer = new ImageCompare(element).mount();
</script>
ChatGPT
