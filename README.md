# amazon feetsocks
<!DOCTYPE html>
<html lang="en">
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Video</title>

  <style>
    html, body {
      margin: 0;
      padding: 0;
      background: #ffffff;
      height: 100%;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .video-container {
      aspect-ratio: 3 / 4;
      width: 92vw;
      max-width: 420px;
      background: #ffffff;
    }

    video {
      width: 100%;
      height: 100%;
      object-fit: cover;
      border-radius: 12px;
    }
  </style>
</head>

<body>

  <div class="video-container">
    <video id="video" loop playsinline>
      <source src="https://shattereddisk.github.io/rickroll/rickroll.mp4" type="video/mp4">
    </video>
  </div>


