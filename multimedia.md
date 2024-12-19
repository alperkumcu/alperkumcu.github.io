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
    <a href="/multimedia/aa">
      <img src="/thumbnails/aa.png" alt="Anadolu Ajansı" class="video-thumbnail">
    </a>
    <a href="/multimedia/aa" class="video-title">Anadolu Ajansı</a>
  </div>

  <!-- Video 2 -->
  <div class="video-item">
    <a href="/multimedia/tpd">
      <img src="/thumbnails/tpd.png" alt="Türkiye Psikiyatri Derneği" class="video-thumbnail">
    </a>
    <a href="/multimedia/tpd" class="video-title">Türkiye Psikiyatri Derneği</a>
  </div>

  <!-- Video 3 -->
  <div class="video-item">
    <a href="/multimedia/boun">
      <img src="/thumbnails/tpd.png" alt="Boğaziçi Üniversitesi" class="video-thumbnail">
    </a>
    <a href="/multimedia/boun" class="video-title">Boğaziçi Üniversitesi</a>
  </div>

  <!-- Video 4 -->
  <div class="video-item">
    <a href="/multimedia/bzz">
      <img src="/thumbnails/tpd.png" alt="Bilinç ve Zihin Zirvesi" class="video-thumbnail">
    </a>
    <a href="/multimedia/bzz" class="video-title">Bilinç ve Zihin Zirvesi</a>
  </div>

<!-- Video 5 -->
  <div class="video-item">
    <a href="/multimedia/dho">
      <img src="/thumbnails/tpd.png" alt="Dijital Hikaye Atölyesi" class="video-thumbnail">
    </a>
    <a href="/multimedia/bzz" class="video-title">Dijital Hikaye Atölyesi</a>
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