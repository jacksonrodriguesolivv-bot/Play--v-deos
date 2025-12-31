<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Play Vídeos 🌴</title>

<!-- 🔸 Código do AdSense -->
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3386947717980401"
     crossorigin="anonymous"></script>

<style>
  body {
    font-family: Arial, sans-serif;
    background: linear-gradient(to bottom, #87ceeb, #fff);
    text-align: center;
    color: #005f73;
    margin: 0;
    padding: 0;
  }
  header {
    background: #00aaff;
    padding: 20px;
    color: white;
    font-size: 2rem;
    font-weight: bold;
  }
  .container {
    padding: 20px;
  }
  .btn {
    background: #008ecc;
    color: white;
    padding: 15px 30px;
    font-size: 1.2rem;
    border: none;
    border-radius: 8px;
    margin: 15px;
    cursor: pointer;
  }
  .btn:hover {
    background: #006fa1;
  }
  .video-frame {
    width: 100%;
    max-width: 560px;
    height: 315px;
    margin: 10px auto;
    border: none;
    display: none;
  }
  #ad-space {
    background: #e0f7fa;
    color: #006064;
    border: 2px dashed #006064;
    padding: 20px;
    margin: 20px auto;
    max-width: 600px;
    font-size: 1.2rem;
  }
  footer {
    padding: 20px;
    background: #00aaff;
    color: white;
  }
</style>
</head>
<body>

<header>Play Vídeos 🌴</header>

<!-- 🔸 Anúncio superior (opcional) -->
<div style="margin:20px auto; max-width:600px;">
  <ins class="adsbygoogle"
       style="display:block"
       data-ad-client="ca-pub-3386947717980401"
       data-ad-slot="1111111111"
       data-ad-format="auto"
       data-full-width-responsive="true"></ins>
  <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
</div>

<div class="container">

  <button class="btn" onclick="document.getElementById('video1').style.display='block'">Play Vídeo 1</button>
  <iframe id="video1" class="video-frame" src="https://www.youtube.com/embed/ipD3OjY64oc" allowfullscreen></iframe>

  <button class="btn" onclick="document.getElementById('video2').style.display='block'">Play Vídeo 2</button>
  <iframe id="video2" class="video-frame" src="https://www.youtube.com/embed/bOSia3DQ9ME" allowfullscreen></iframe>

  <!-- 🔸 Espaço principal do AdSense -->
  <div id="ad-space">
    <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-3386947717980401"
         data-ad-slot="2222222222"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
    <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
  </div>

  <button class="btn" onclick="window.location.href='https://play.google.com/store'">Ir para a Play Store</button>

</div>

<footer>
  © 2025 Play Vídeos 🌊 — Todos os direitos reservados
</footer>

</body>
</html>
