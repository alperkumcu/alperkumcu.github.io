---
layout: page
title: multimedia
permalink: /multimedia/
lang: en
---

<style>

.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  padding: 20px;
}

.video-item {
  text-align: center;
  border: 1px solid #ddd;
  padding: 10px;
  border-radius: 10px;
  background-color: #f9f9f9;
}

.video-thumbnail {
  width: 100%;
  height: auto;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.video-thumbnail:hover {
  transform: scale(1.05);
}

.video-title {
  display: block;
  margin-top: 10px;
  font-size: 1.2em;
  font-weight: bold;
  text-decoration: none;
  color: #333;
}

.video-title:hover {
  color: #007bff;
}

</style>


### Videos

<div class="video-grid">
  <!-- Video 1 -->
  <div class="video-item">
    <a href="aa.md">
      <img src="/thumbnails/aa.png" alt="Anadolu Ajansı" class="video-thumbnail">
    </a>
    <a href="\alperkumcu.github.io\multimedia\aa.md" class="video-title">Anadolu Ajansı</a>
  </div>

  <!-- Video 2 -->
  <div class="video-item">
    <a href="tpd.md">
      <img src="/thumbnails/tpd.png" alt="Türkiye Psikiyatri Derneği" class="video-thumbnail">
    </a>
    <a href="https://alperkumcu.github.io/multimedia/tpd.md" class="video-title">Türkiye Psikiyatri Derneği</a>
  </div>
</div>


### Audio

#### TRT Radyo 1

<audio controls>
  <source src="/audio/aa.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<br>

#### Aston University

<audio controls>
  <source src="/audio/aa.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>