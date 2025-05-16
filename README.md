# Geo3d<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Geo 3D - Murakkab shaklli 3D geometrik modellar</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121c2a;
      color: #c0d6df;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    header {
      background: #0b1421;
      padding: 1rem 2rem;
      text-align: center;
      font-size: 1.8rem;
      font-weight: bold;
      color: #63a4ff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.5);
    }
    main {
      flex: 1;
      padding: 2rem;
      max-width: 1000px;
      margin: 0 auto;
    }
    h1 {
      color: #63a4ff;
      margin-bottom: 0.5rem;
      text-align: center;
    }
    p.description {
      text-align: center;
      font-size: 1.1rem;
      margin-bottom: 2rem;
      color: #a9c5ff;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .model-card {
      background: #1b2a48;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 4px 15px rgba(0,0,0,0.4);
      display: flex;
      flex-direction: column;
      align-items: center;
      color: #d1e6ff;
    }
    .model-card h2 {
      margin: 0.5rem 0 1rem;
    }
    model-viewer {
      width: 100%;
      height: 280px;
      border-radius: 8px;
      background-color: #293952;
      box-shadow: inset 0 0 10px #00000088;
    }
    footer {
      background: #0b1421;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #627d98;
    }
    @media (max-width: 480px) {
      h1 {
        font-size: 1.4rem;
      }
      .model-card {
        padding: 0.5rem;
      }
    }
  </style>
  <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
</head>
<body>
  <header>
    Geo 3D — Murakkab shaklli 3D geometrik ob'yektlarni modellashtirish
  </header>
  <main>
    <h1>3D modellar galereyasi</h1>
    <p class="description">
      Bu yerda murakkab shaklli uch o'lchovli geometrik ob'yektlarning interaktiv modellarini ko'rishingiz mumkin. Sichqoncha yoki sensor yordamida aylantiring va turli burchaklardan tahlil qiling.
    </p>
    <div class="gallery">
      <div class="model-card">
        <h2>Kub (Cube)</h2>
        <model-viewer src="https://modelviewer.dev/shared-assets/models/Cube.glb" alt="Kub" auto-rotate camera-controls></model-viewer>
      </div>
      <div class="model-card">
        <h2>Sfera (Sphere)</h2>
        <model-viewer src="https://modelviewer.dev/shared-assets/models/Sphere.glb" alt="Sfera" auto-rotate camera-controls></model-viewer>
      </div>
      <div class="model-card">
        <h2>Konus (Cone)</h2>
        <model-viewer src="https://modelviewer.dev/shared-assets/models/Cone.glb" alt="Konus" auto-rotate camera-controls></model-viewer>
      </div>
      <div class="model-card">
        <h2>Silindr (Cylinder)</h2>
        <model-viewer src="https://modelviewer.dev/shared-assets/models/Cylinder.glb" alt="Silindr" auto-rotate camera-controls></model-viewer>
      </div>
      <div class="model-card">
        <h2>Piramida (Pyramid)</h2>
        <model-viewer src="https://modelviewer.dev/shared-assets/models/Pyramid.glb" alt="Piramida" auto-rotate camera-controls></model-viewer>
      </div>
      <div class="model-card">
        <h2>Parallelepiped</h2>
        <model-viewer src="https://modelviewer.dev/shared-assets/models/Parallelepiped.glb" alt="Parallelepiped" auto-rotate camera-controls></model-viewer>
      </div>
    </div>
  </main>
  <footer>
    © 2025 Azizbek tomonidan tayyorlandi. Geo 3D sayti.
  </footer>
</body>
</html>
