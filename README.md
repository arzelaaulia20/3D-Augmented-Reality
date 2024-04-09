<!DOCTYPE html>
<html>
  <head>
    <title>AR.js with A-Frame Magic</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://cdn.rawgit.com/jeromeetienne/AR.js/2.0.8/aframe/build/aframe-ar.js"></script>
  </head>
  <body style="margin : 0px; overflow: hidden;">
    <a-scene embedded arjs="detectionMode: mono_and_matrix; matrixCodeType: 3x3;">
      <a-marker preset="hiro">
        <a-box position='0 0.5 0' material='color: red;'></a-box>
      </a-marker>
      <a-entity camera></a-entity>
    </a-scene>
  </body>
</html>
