---
layout: page
title: publications
permalink: /publications/
lang: en
---

<style>
.pub-intro {
  margin-bottom: 1.5rem;
  color: #555;
  font-size: 1.05rem;
  line-height: 1.6;
}

.pub-toolbar {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 1.5rem 0 2rem 0;
}

.pub-filter {
  border: 1px solid #ddd;
  background: #fff;
  color: inherit;
  padding: 0.45rem 0.8rem;
  border-radius: 999px;
  cursor: pointer;
  font-size: 0.9rem;
  transition: all 0.2s ease;
}

.pub-filter:hover,
.pub-filter.active {
  border-color: #777;
  background: #f7f7f7;
}

.pub-list {
  display: grid;
  gap: 1rem;
  margin: 1.2rem 0 2.5rem 0;
}

.pub-card {
  border: 1px solid #e6e6e6;
  border-radius: 14px;
  padding: 1rem 1.1rem;
  background: #fff;
  transition: all 0.2s ease;
}

.pub-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 22px rgba(0, 0, 0, 0.06);
  border-color: #ccc;
}

.pub-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-bottom: 0.65rem;
}

.pub-badge {
  font-size: 0.75rem;
  line-height: 1;
  border: 1px solid #ddd;
  border-radius: 999px;
  padding: 0.3rem 0.5rem;
  color: #555;
  background: #fafafa;
}

.pub-title {
  font-size: 1.05rem;
  font-weight: 650;
  line-height: 1.45;
  margin-bottom: 0.35rem;
}

.pub-citation {
  font-size: 0.97rem;
  line-height: 1.55;
  color: #333;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 0.8rem;
}

.pub-link,
.pub-copy {
  font-size: 0.82rem;
  border: 1px solid #ddd;
  border-radius: 999px;
  padding: 0.35rem 0.6rem;
  text-decoration: none;
  color: inherit;
  background: #fff;
  cursor: pointer;
  transition: all 0.2s ease;
}

.pub-link:hover,
.pub-copy:hover {
  background: #f7f7f7;
  border-color: #aaa;
  text-decoration: none;
}

.pub-note {
  font-size: 0.85rem;
  color: #666;
  margin-top: 0.55rem;
}

.pub-section {
  margin-top: 2.5rem;
}
</style>

## Publications

<div class="pub-intro">
Selected journal articles, book chapters, edited volumes, and other scholarly outputs. 
Open materials, datasets, preprints, and PDFs are linked where available.
</div>

<div class="pub-toolbar">
  <button class="pub-filter active" onclick="filterPubs('all', this)">All</button>
  <button class="pub-filter" onclick="filterPubs('sci', this)">SCI/SSCI</button>
  <button class="pub-filter" onclick="filterPubs('scopus', this)">Scopus</button>
  <button class="pub-filter" onclick="filterPubs('trindex', this)">TRIndex</button>
  <button class="pub-filter" onclick="filterPubs('chapter', this)">Book chapters</button>
  <button class="pub-filter" onclick="filterPubs('book', this)">Books</button>
  <button class="pub-filter" onclick="filterPubs('translation', this)">Translation</button>
</div>

## Papers

### SCI/SSCI

<div class="pub-list">

<article class="pub-card" data-type="sci">
  <div class="pub-meta">
    <span class="pub-badge">2026</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">In press</span>
  </div>

  <div class="pub-title">
    Disentangling cognitive and emotional load in interpreting: multimodal evidence from physiological and prosodic data
  </div>

  <div class="pub-citation">
    <strong>Kumcu, A.</strong>, &amp; Duman, D. (2026). 
    <em>Target</em>, <em>xx</em>(x), xxx–xxx.
  </div>

  <div class="pub-links">
    <a class="pub-link" href="http://doi.org/" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/preprints/psyarxiv/zjbf4_v1" target="_blank" rel="noopener noreferrer">Preprint</a>
    <a class="pub-link" href="https://osf.io/2j749/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Duman, D. (2026). Disentangling cognitive and emotional load in interpreting: multimodal evidence from physiological and prosodic data. Target, xx(x), xxx–xxx.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-type="sci">
  <div class="pub-meta">
    <span class="pub-badge">2023</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Data available</span>
  </div>

  <div class="pub-title">
    Visual mental imagery and verbal working memory: evidence from consecutive interpreting
  </div>

  <div class="pub-citation">
    <strong>Kumcu, A.</strong>, &amp; Öztürk, A. (2023). 
    <em>Journal of Cognitive Psychology</em>, <em>35</em>(5), 545–560.
  </div>

  <div class="pub-links">
    <a class="pub-link" href="http://doi.org/10.1080/20445911.2023.2216917" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/gtxwa/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Öztürk, A. (2023). Visual mental imagery and verbal working memory: evidence from consecutive interpreting. Journal of Cognitive Psychology, 35(5), 545–560. https://doi.org/10.1080/20445911.2023.2216917">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-type="sci">
  <div class="pub-meta">
    <span class="pub-badge">2022</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Open materials</span>
  </div>

  <div class="pub-title">
    Remembering spatial words: Sensorimotor simulation affects verbal recognition memory
  </div>

  <div class="pub-citation">
    <strong>Kumcu, A.</strong>, &amp; Thompson, R. L. (2022). 
    <em>Quarterly Journal of Experimental Psychology</em>, <em>75</em>(9), 1694–1710.
  </div>

  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1177/17470218211059011" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/6wcen/" target="_blank" rel="noopener noreferrer">Data</a>
    <a class="pub-link" href="https://link.growkudos.com/1n3kszmuw3k" target="_blank" rel="noopener noreferrer">Showcase</a>
    <a class="pub-link" href="https://alperkumcu.github.io/pdfs/Remembering%20Spatial%20Words%20Sensorimotor%20Simulation%20Affects%20Verbal%20Recognition%20Memory.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Thompson, R. L. (2022). Remembering spatial words: Sensorimotor simulation affects verbal recognition memory. Quarterly Journal of Experimental Psychology, 75(9), 1694–1710. https://doi.org/10.1177/17470218211059011">Copy citation</button>
  </div>
</article>

</div>

### Scopus

<div class="pub-list">

<article class="pub-card" data-type="scopus">
  <div class="pub-meta">
    <span class="pub-badge">2025</span>
    <span class="pub-badge">Scopus</span>
    <span class="pub-badge">Systematic review</span>
  </div>

  <div class="pub-title">
    Looking at Online Language Comprehension with the Visual World Paradigm: A Systematic Review of Three Decades
  </div>

  <div class="pub-citation">
    Uzun, İ. P., &amp; <strong>Kumcu, A.</strong> (2025). 
    <em>Dilbilim Araştırmaları Dergisi</em>, <em>36</em>(2), 185–223.
  </div>

  <div class="pub-links">
    <a class="pub-link" href="http://doi.org/10.18492/dad.1692960" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/mp637/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Uzun, İ. P., & Kumcu, A. (2025). Looking at Online Language Comprehension with the Visual World Paradigm: A Systematic Review of Three Decades. Dilbilim Araştırmaları Dergisi, 36(2), 185–223. https://doi.org/10.18492/dad.1692960">Copy citation</button>
  </div>
</article>

</div>

## Books

### Book chapters

<div class="pub-list">

<article class="pub-card" data-type="chapter">
  <div class="pub-meta">
    <span class="pub-badge">2025</span>
    <span class="pub-badge">Book chapter</span>
    <span class="pub-badge">Data available</span>
  </div>

  <div class="pub-title">
    It's High Time: A Corpus and NLP-Based Investigation of the Time Metaphors in Turkish
  </div>

  <div class="pub-citation">
    <strong>Kumcu, A.</strong> (2025). In H. Cangır, K. Uzun, T. Can, &amp; E. Oğuz (Eds.), 
    <em>Exploration of the Intersection of Corpus Linguistics and Language Science</em> 
    (pp. 223–252). IGI Global Scientific Publishing.
  </div>

  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.4018/979-8-3693-8146-5.ch010" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/ynwdm/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2025). It's High Time: A Corpus and NLP-Based Investigation of the Time Metaphors in Turkish. In H. Cangır, K. Uzun, T. Can, & E. Oğuz (Eds.), Exploration of the Intersection of Corpus Linguistics and Language Science (pp. 223–252). IGI Global Scientific Publishing. https://doi.org/10.4018/979-8-3693-8146-5.ch010">Copy citation</button>
  </div>
</article>

</div>

<script>
function filterPubs(type, button) {
  const cards = document.querySelectorAll('.pub-card');
  const buttons = document.querySelectorAll('.pub-filter');

  buttons.forEach(btn => btn.classList.remove('active'));
  button.classList.add('active');

  cards.forEach(card => {
    if (type === 'all' || card.dataset.type === type) {
      card.style.display = 'block';
    } else {
      card.style.display = 'none';
    }
  });
}

function copyPubCitation(button) {
  const citation = button.getAttribute('data-citation');

  navigator.clipboard.writeText(citation).then(() => {
    const originalText = button.textContent;
    button.textContent = 'Copied';
    setTimeout(() => {
      button.textContent = originalText;
    }, 1400);
  });
}
</script>