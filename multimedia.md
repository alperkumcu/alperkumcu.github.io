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

/* Responsive YouTube Embed */
.video-embed {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 */
  height: 0;
  overflow: hidden;
  border-radius: 8px;
}

.video-embed iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
  border-radius: 8px;
}

</style>


### Videos

<div class="video-grid">

  <!-- YouTube Video (NEW FIRST VIDEO) -->
  <div class="video-item">
    <div class="video-embed">
      <iframe 
        src="https://www.youtube.com/embed/JzrFLoyDWlY?si=DEzCjpcRCSW2JhvT" 
        title="YouTube video player" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
      </iframe>
    </div>
    <span class="video-title">Video Title Here</span>
  </div>

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