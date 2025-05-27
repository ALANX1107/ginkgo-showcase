
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>千年銀杏・時光迴廊</title>
  <style>
    body {
      margin: 0;
      font-family: "Noto Serif TC", serif;
      background-color: #fdf9f1;
      color: #4b3e2a;
    }
    header {
      background: linear-gradient(#e4cfa1, #fdf9f1);
      padding: 1em;
      text-align: center;
    }
    h1 {
      font-size: 2em;
      margin: 0.2em 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1em;
      margin-bottom: 1em;
    }
    nav a {
      text-decoration: none;
      color: #6a5a3d;
      font-weight: bold;
    }
    section {
      padding: 1em 2em;
      max-width: 900px;
      margin: auto;
    }
    .tree-container {
      text-align: center;
      margin: 2em 0;
    }
    model-viewer {
      width: 100%;
      height: 500px;
    }
    footer {
      background-color: #e4cfa1;
      text-align: center;
      padding: 1em;
      font-size: 0.9em;
      color: #3e3e3e;
    }
    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
    }
    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
  </style>
  <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
</head>
<body>
  <header>
    <h1>千年銀杏・時光迴廊</h1>
    <p>探索一棵樹的文化、詩意與想像</p>
  </header>
  <nav>
    <a href="#a1">原貌再現</a>
    <a href="#a2">知識擴展</a>
    <a href="#a3">文化再詮釋</a>
  </nav>

  <section id="a1">
    <h2>原貌再現：互動銀杏 3D 模型</h2>
    <div class="tree-container">
      <!-- 請確保 .glb 檔案已部署至網站伺服器對應的路徑或上傳至支援的雲端平台 -->
      <model-viewer src="A_realistic_3D_model__0527103248_texture.glb" alt="銀杏樹模型" auto-rotate camera-controls background-color="#fdf9f1"></model-viewer>
    </div>
  </section>

  <section id="a2">
    <h2>知識擴展：銀杏介紹影片</h2>
    <div class="video-container">
      <!-- 替換以下網址為實際 YouTube 或其他平台的影片連結 -->
      <iframe src="https://www.youtube.com/embed/影片ID" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <section id="a3">
    <h2>文化再詮釋：互動詩歌與模擬體驗</h2>
    <p>輸入一段情感文字，生成一首與銀杏相關的詩，或模擬你的「銀杏人生」。</p>
    <button onclick="alert('這裡可接 ChatGPT 詩歌 API 或人生模擬對話介面')">開始詩歌生成</button>
  </section>

  <footer>
    <p>本平台由 AI 數位轉譯計畫製作，結合文化與科技的跨界展演。</p>
  </footer>
</body>
</html>
