<!DOCTYPE html>
<html>

<head>
  <style>
    video {
      position: fixed;
      top: 50%;
      left: 50%;
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      z-index: -100;
      transform: translateX(-50%) translateY(-50%);
      background: url('path/to/video-poster.jpg') no-repeat;
      background-size: cover;
    }
  </style>
</head>

<body>
  <video autoplay loop>
    <source src="braveheart.mp4" type="video/mp4">
  </video>
</body>
</html>
