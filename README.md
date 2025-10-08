<!DOCTYPE html>
<html lang="hu">
  <head>
    <meta charset="UTF-8" />
    <title>3D Modellek</title>
    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
    <style>
      body { margin: 0; background: #f5f5f5; font-family: sans-serif; }
      model-viewer { width: 100%; height: 500px; margin-bottom: 40px; }
    </style>
  </head>
  <body>
    <h2 style="text-align:center;">Beltéri modell</h2>
    <model-viewer src="Ceklima_belteri.glb"
                  alt="Beltéri modell"
                  auto-rotate
                  camera-controls
                  shadow-intensity="1"
                  exposure="1.2">
    </model-viewer>

    <h2 style="text-align:center;">Kültéri modell</h2>
    <model-viewer src="Ceklima_kulteri.glb"
                  alt="Kültéri modell"
                  auto-rotate
                  camera-controls
                  shadow-intensity="1"
                  exposure="1.2">
    </model-viewer>
  </body>
</html>

