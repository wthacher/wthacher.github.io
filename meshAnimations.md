---
layout: null
permalink: /meshAnimations/
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mesh Animations | Will Thacher</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/water.css@2/out/water.css">
    <script defer src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

    <style>
        body {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .video-stack {
            display: flex;
            flex-direction: column;
            gap: 50px; /* Space between different animations */
            margin-top: 30px;
        }
        .video-item {
            text-align: center;
            background: rgba(255, 255, 255, 0.05); /* Subtle background for the video container */
            padding: 15px;
            border-radius: 8px;
        }
        video {
            width: 100%;
            height: auto;
            border-radius: 6px;
            /* Subtle glow/shadow that works in both light and dark mode */
            box-shadow: 0 10px 30px rgba(0,0,0,0.15); 
        }
        h1 {
            text-align: center;
            border-bottom: 2px solid var(--links); /* Uses Water.css variable color */
            padding-bottom: 10px;
        }
        .back-link {
            display: block;
            margin-bottom: 20px;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <a href="/" class="back-link">← Back to Home</a>

    <h1>Mesh Animations</h1>
    <p>A collection of animations related to [Insert specific topic, e.g., Finite Element Analysis].</p>

    <div class="video-stack">
        <div class="video-item">
            <video autoplay loop muted playsinline>
                <source src="{{ '/ezgif-31c1391bce9604d1.mp4' | relative_url }}" type="video/mp4">
            </video>
            
        </div>

        <div class="video-item">
            <video autoplay loop muted playsinline>
                <source src="{{ '/ezgif-343fb225505bec96.mp4' | relative_url }}" type="video/mp4">
            </video>
            
        </div>

        <div class="video-item">
            <video autoplay loop muted playsinline>
                <source src="{{ '/ezgif-36fe03ee80e9f410.mp4' | relative_url }}" type="video/mp4">
            </video>
        </div>

        <div class="video-item">
            <video autoplay loop muted playsinline>
                <source src="{{ '/ezgif-3d4ea05c9a303c7d.mp4' | relative_url }}" type="video/mp4">
            </video>
            
        </div>
    </div>

</body>
</html>
