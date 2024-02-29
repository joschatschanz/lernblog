+++
title = "Portfolio 1"
draft = false
image = ""
description = "Das ist mein Portfolio"
+++
<!DOCTYPE html>

<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine YouTube Sammlung</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="video-container">
    <!-- Hier kommen die YouTube-Einbettungen hin -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

</body>
</html>



body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
    padding: 20px;
    margin: 0;
}

.video-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

iframe {
    border: none;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}