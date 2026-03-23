# amazon-feetsocks
Rickrolled :p
<html lang="en">
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Video</title>

  <style>
    body {
      margin: 0;
      background: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .video-container {
      aspect-ratio: 3 / 4;
      width: 92vw;
      max-width: 420px;
      position: relative;
      cursor: pointer;
    }

    iframe {
      width: 100%;
      height: 100%;
      border: none;
      border-radius: 10px;
    }
  </style>
</head>

<body>

  <div class="video-container" onclick="startVideo()">
    
    <iframe 
      id="video"
      src="https://www.youtube.com/embed/7X1H5AxJPb8?loop=1&playlist=7X1H5AxJPb8"
      allow="autoplay; fullscreen">
    </iframe>

  </div>

  <script>
    function startVideo() {
      const iframe = document.getElementById("video");
      iframe.src = "https://www.youtube.com/embed/7X1H5AxJPb8?autoplay=1&loop=1&playlist=7X1H5AxJPb8";
    }
  </script>

</body>
</html>
