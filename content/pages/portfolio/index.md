+++
title = "Portfolio"
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
    <style>
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

        .video {
            width: 560px;
            margin-bottom: 20px;
        }

        iframe {
            border: none;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            width: 100%;
            height: 315px;
        }

        .video-title {
            font-size: 18px;
            font-weight: bold;
            margin: 0;
        }

        .video-desc {
            font-size: 14px;
            margin: 5px 0 15px;
        }
    </style>
</head>
<body>

<div class="video-container">
    <!-- Video 1 -->
    <div class="video">
        <p class="video-title">Titel des ersten Videos</p>
        <p class="video-desc">Kurze Beschreibung des ersten Videos.</p>
        <iframe src="https://www.youtube.com/embed/VIDEO_ID1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <!-- Weitere Videos hier... -->
    <!-- Video 2 -->
    <div class="video">
        <p class="video-title">Titel des zweiten Videos</p>
        <p class="video-desc">Kurze Beschreibung des zweiten Videos.</p>
        <iframe src="https://www.youtube.com/embed/VIDEO_ID2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <!-- Bis zu Video 6 wiederholen... -->
</div>

</body>
</html>
