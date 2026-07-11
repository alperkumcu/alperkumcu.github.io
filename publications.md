---
layout: page
title: Publications
permalink: /publications/
lang: en
---

<style>
.pub-intro {
  margin-bottom: 1.5rem;
  color: #555;
  font-size: 1.05rem;
  line-height: 1.65;
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

.pub-section {
  margin-top: 2.5rem;
}

.pub-section h2,
.pub-section h3 {
  margin-bottom: 1rem;
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
</style>

<div class="pub-intro">
A complete list of journal articles, edited books, book chapters, conference proceedings, and translations. Open materials, datasets, preprints, PDFs, and other resources are linked where available.
</div>

<div class="pub-toolbar">
  <button class="pub-filter active" onclick="filterPubs('all', this)">All</button>
  <button class="pub-filter" onclick="filterPubs('paper', this)">Papers</button>
  <button class="pub-filter" onclick="filterPubs('sci', this)">SCI/SSCI</button>
  <button class="pub-filter" onclick="filterPubs('scopus', this)">Scopus</button>
  <button class="pub-filter" onclick="filterPubs('trindex', this)">TRIndex</button>
  <button class="pub-filter" onclick="filterPubs('other-index', this)">Other indices</button>
  <button class="pub-filter" onclick="filterPubs('edited-book', this)">Edited books</button>
  <button class="pub-filter" onclick="filterPubs('chapter', this)">Book chapters</button>
  <button class="pub-filter" onclick="filterPubs('translation', this)">Translation</button>
  <button class="pub-filter" onclick="filterPubs('open', this)">Open materials</button>
</div>

<section class="pub-section">

## Papers  

### Web of Science

<div class="pub-list">

<article class="pub-card" data-tags="paper sci open preprint data inpress">
  <div class="pub-meta">
    <span class="pub-badge">2026</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">In press</span>
  </div>
  <div class="pub-title">Disentangling cognitive and emotional load in interpreting: multimodal evidence from physiological and prosodic data</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong>, &amp; Duman, D. (2026). <em>Target</em>, <em>xx</em>(x), xxx–xxx.</div>
  <div class="pub-links">
    <span class="pub-badge">DOI pending</span>
    <a class="pub-link" href="https://osf.io/preprints/psyarxiv/zjbf4_v1" target="_blank" rel="noopener noreferrer">Preprint</a>
    <a class="pub-link" href="https://osf.io/2j749/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Duman, D. (2026). Disentangling cognitive and emotional load in interpreting: multimodal evidence from physiological and prosodic data. Target, xx(x), xxx–xxx.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper sci open data">
  <div class="pub-meta">
    <span class="pub-badge">2026</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Data available</span>
  </div>
  <div class="pub-title">Spoken language biomarkers in Turkish-speaking schizophrenia patients: Evidence from linguistic analysis and word embeddings</div>
  <div class="pub-citation">Çınar Bozdağ, M., <strong>Kumcu, A.</strong>, Şenel, L. K., Temizkan, H. N., Özil, Ö., Arslanyürek, İ., Ertekin, P. N., &amp; Candansayar, S. (2026). <em>Psychiatry Research</em>, <em>362</em>(x), xxx–xxx.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1016/j.psychres.2026.117215" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/x7qd2/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Çınar Bozdağ, M., Kumcu, A., Şenel, L. K., Temizkan, H. N., Özil, Ö., Arslanyürek, İ., Ertekin, P. N., & Candansayar, S. (2026). Spoken language biomarkers in Turkish-speaking schizophrenia patients: Evidence from linguistic analysis and word embeddings. Psychiatry Research, 362(x), xxx–xxx. https://doi.org/10.1016/j.psychres.2026.117215">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper scopus inpress">
  <div class="pub-meta">
    <span class="pub-badge">2026</span>
    <span class="pub-badge">AHCI, Scopus</span>
  </div>
  <div class="pub-title">Testing the impact of translation training on creativity: Evidence from Turkish-English student-translators</div>
  <div class="pub-citation">Yılmaz, B. A., <strong>Kumcu, A.</strong> &amp; Antonova-Ünlü, E. (2026). <em>Moderna Språk</em>. <em>120</em>(1), 102–115.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.58221/mosp.v120i1.60841" target="_blank" rel="noopener noreferrer">DOI</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Ataberk-Yılmaz, B., Kumcu, A., & Antonova-Unlu, E. (2026). Testing the impact of translation training on creativity: Evidence from Turkish-English student-translators. Moderna Språk, 120(1), 102–115. https://doi.org/10.58221/mosp.v120i1.60841">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper sci open data">
  <div class="pub-meta">
    <span class="pub-badge">2023</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Data available</span>
  </div>
  <div class="pub-title">Visual mental imagery and verbal working memory: evidence from consecutive interpreting</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong>, &amp; Öztürk, A. (2023). <em>Journal of Cognitive Psychology</em>, <em>35</em>(5), 545–560.</div>
  <div class="pub-links">
    <a class="pub-link" href="http://doi.org/10.1080/20445911.2023.2216917" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/gtxwa/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Öztürk, A. (2023). Visual mental imagery and verbal working memory: evidence from consecutive interpreting. Journal of Cognitive Psychology, 35(5), 545–560. https://doi.org/10.1080/20445911.2023.2216917">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper sci open data pdf showcase">
  <div class="pub-meta">
    <span class="pub-badge">2022</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Open materials</span>
  </div>
  <div class="pub-title">Remembering spatial words: Sensorimotor simulation affects verbal recognition memory</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong>, &amp; Thompson, R. L. (2022). <em>Quarterly Journal of Experimental Psychology</em>, <em>75</em>(9), 1694–1710.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1177/17470218211059011" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/6wcen/" target="_blank" rel="noopener noreferrer">Data</a>
    <a class="pub-link" href="https://link.growkudos.com/1n3kszmuw3k" target="_blank" rel="noopener noreferrer">Showcase</a>
    <a class="pub-link" href="https://alperkumcu.github.io/pdfs/Remembering%20Spatial%20Words%20Sensorimotor%20Simulation%20Affects%20Verbal%20Recognition%20Memory.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Thompson, R. L. (2022). Remembering spatial words: Sensorimotor simulation affects verbal recognition memory. Quarterly Journal of Experimental Psychology, 75(9), 1694–1710. https://doi.org/10.1177/17470218211059011">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper sci open pdf">
  <div class="pub-meta">
    <span class="pub-badge">2022</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">PDF</span>
  </div>
  <div class="pub-title">Assessing the use of multiple-choice translation items in English proficiency tests: The case of the National English Proficiency Test in Turkey</div>
  <div class="pub-citation">Dinçer, H., Antonova-Ünlü, E., &amp; <strong>Kumcu, A.</strong> (2022). <em>Applied Linguistics Review</em>, <em>13</em>(4), 461–475.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1515/applirev-2019-0064" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://alperkumcu.github.io/pdfs/10.1515_applirev-2019-0064.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Dinçer, H., Antonova-Ünlü, E., & Kumcu, A. (2022). Assessing the use of multiple-choice translation items in English proficiency tests: The case of the National English Proficiency Test in Turkey. Applied Linguistics Review, 13(4), 461–475. https://doi.org/10.1515/applirev-2019-0064">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper sci open data">
  <div class="pub-meta">
    <span class="pub-badge">2021</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Data available</span>
  </div>
  <div class="pub-title">Linguistic synesthesia in Turkish: A corpus-based study of cross-modal directionality</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2021). <em>Metaphor and Symbol</em>, <em>36</em>(4), 241–255.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1080/10926488.2021.1921557" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/2unvy/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2021). Linguistic synesthesia in Turkish: A corpus-based study of cross-modal directionality. Metaphor and Symbol, 36(4), 241–255. https://doi.org/10.1080/10926488.2021.1921557">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper sci open data">
  <div class="pub-meta">
    <span class="pub-badge">2020</span>
    <span class="pub-badge">SCI/SSCI</span>
    <span class="pub-badge">Data available</span>
  </div>
  <div class="pub-title">Less imageable words lead to more looks to blank locations during memory retrieval</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong>, &amp; Thompson, R. L. (2020). <em>Psychological Research</em>, <em>84</em>, 667–684.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.1007/s00426-018-1084-6" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/m9yh3/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Thompson, R. L. (2020). Less imageable words lead to more looks to blank locations during memory retrieval. Psychological Research, 84, 667–684. https://doi.org/10.1007/s00426-018-1084-6">Copy citation</button>
  </div>
</article>

</div>

### Scopus  

<div class="pub-list">

<article class="pub-card" data-tags="paper scopus open data">
  <div class="pub-meta">
    <span class="pub-badge">2025</span>
    <span class="pub-badge">Scopus</span>
    <span class="pub-badge">Data available</span>
  </div>
  <div class="pub-title">Looking at Online Language Comprehension with the Visual World Paradigm: A Systematic Review of Three Decades</div>
  <div class="pub-citation">Uzun, İ. P., &amp; <strong>Kumcu, A.</strong> (2025). <em>Dilbilim Araştırmaları Dergisi</em>, <em>36</em>(2), 185–223.</div>
  <div class="pub-links">
    <a class="pub-link" href="http://doi.org/10.18492/dad.1692960" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/mp637/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Uzun, İ. P., & Kumcu, A. (2025). Looking at Online Language Comprehension with the Visual World Paradigm: A Systematic Review of Three Decades. Dilbilim Araştırmaları Dergisi, 36(2), 185–223. https://doi.org/10.18492/dad.1692960">Copy citation</button>
  </div>
</article>

</div>

### TRIndex  

<div class="pub-list">

<article class="pub-card" data-tags="paper trindex">
  <div class="pub-meta">
    <span class="pub-badge">2025</span>
    <span class="pub-badge">TRIndex</span>
  </div>
  <div class="pub-title">Effort in machine translation post-editing: the role of expertise</div>
  <div class="pub-citation">Öztürk, M. S., &amp; <strong>Kumcu, A.</strong> (2025). <em>Çankaya University Journal of Humanities and Social Sciences</em>, <em>19</em>(2), 293–309.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.47777/cankujhss.1782613" target="_blank" rel="noopener noreferrer">DOI</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Öztürk, M. S., & Kumcu, A. (2025). Effort in machine translation post-editing: the role of expertise. Çankaya University Journal of Humanities and Social Sciences, 19(2), 293–309. https://doi.org/10.47777/cankujhss.1782613">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper trindex">
  <div class="pub-meta">
    <span class="pub-badge">2023</span>
    <span class="pub-badge">TRIndex</span>
  </div>
  <div class="pub-title">Emotional language processing in bilingualism: Subjective affect and prosodic markers in simultaneous interpreting</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2023). <em>Çankaya University Journal of Humanities and Social Sciences</em>, <em>17</em>(2), 194–211.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.47777/cankujhss.1338278" target="_blank" rel="noopener noreferrer">DOI</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2023). Emotional language processing in bilingualism: Subjective affect and prosodic markers in simultaneous interpreting. Çankaya University Journal of Humanities and Social Sciences, 17(2), 194–211. https://doi.org/10.47777/cankujhss.1338278">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper trindex open pdf">
  <div class="pub-meta">
    <span class="pub-badge">2020</span>
    <span class="pub-badge">TRIndex</span>
    <span class="pub-badge">PDF</span>
  </div>
  <div class="pub-title">Konferans salonunda dağıtık biliş: Andaş çeviri sürecine yeni bir bakış</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2020). <em>Hacettepe Üniversitesi Edebiyat Fakültesi Dergisi</em>, <em>37</em>(1), 170–185.</div>
  <div class="pub-note">English title: Distributed cognition in the conference venue: A fresh perspective on the simultaneous interpreting process.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.32600/huefd.621553" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="http://example.com/" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2020). Konferans salonunda dağıtık biliş: Andaş çeviri sürecine yeni bir bakış. Hacettepe Üniversitesi Edebiyat Fakültesi Dergisi, 37(1), 170–185. https://doi.org/10.32600/huefd.621553">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper trindex open pdf">
  <div class="pub-meta">
    <span class="pub-badge">2008</span>
    <span class="pub-badge">TRIndex</span>
    <span class="pub-badge">PDF</span>
  </div>
  <div class="pub-title">Alice çeviri diyarında: Kültürel motifler açısından karşılaştırmalı bir çeviri eleştirisi</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2008). <em>Çeviribilim ve Uygulamaları</em>, <em>18</em>, 123–144.</div>
  <div class="pub-note">English title: Alice in translationland: A comparative translation analysis with regard to cultural motifs.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://github.com/alperkumcu/alperkumcu.github.io/files/6416075/Alice.Ceviri.Diyarinda.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2008). Alice çeviri diyarında: Kültürel motifler açısından karşılaştırmalı bir çeviri eleştirisi. Çeviribilim ve Uygulamaları, 18, 123–144.">Copy citation</button>
  </div>
</article>

</div>

### Other indices  

<div class="pub-list">

<article class="pub-card" data-tags="paper other-index open preprint data">
  <div class="pub-meta">
    <span class="pub-badge">2025</span>
    <span class="pub-badge">Other indices</span>
    <span class="pub-badge">Open materials</span>
  </div>
  <div class="pub-title">The Effect of Syntactic Structure and Distance on Sentence Processing: Evidence from Visual-World Paradigm</div>
  <div class="pub-citation">Çakar, S., <strong>Kumcu, A.</strong>, &amp; Uzun, İ. P. (2025). <em>Mersin Üniversitesi Dil ve Edebiyat Dergisi</em>, <em>21</em>(2), 49–75.</div>
  <div class="pub-links">
    <span class="pub-badge">DOI pending</span>
    <a class="pub-link" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4724807" target="_blank" rel="noopener noreferrer">Preprint</a>
    <a class="pub-link" href="https://osf.io/m276f/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Çakar, S., Kumcu, A., & Uzun, İ. P. (2025). The Effect of Syntactic Structure and Distance on Sentence Processing: Evidence from Visual-World Paradigm. Mersin Üniversitesi Dil ve Edebiyat Dergisi, 21(2), 49–75.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="paper other-index">
  <div class="pub-meta">
    <span class="pub-badge">2020</span>
    <span class="pub-badge">Other indices</span>
  </div>
  <div class="pub-title">The attitude and expectations of Turkish society concerning immigrants residing in Turkey and their social and linguistic acculturation patterns</div>
  <div class="pub-citation">Sağın-Şimşek, Ç., Antonova-Ünlü, E., &amp; <strong>Kumcu, A.</strong> (2020). <em>Journal of Second and Multiple Language Acquisition</em>, <em>8</em>(3), 57–78.</div>
  <div class="pub-links">
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Sağın-Şimşek, Ç., Antonova-Ünlü, E., & Kumcu, A. (2020). The attitude and expectations of Turkish society concerning immigrants residing in Turkey and their social and linguistic acculturation patterns. Journal of Second and Multiple Language Acquisition, 8(3), 57–78.">Copy citation</button>
  </div>
</article>

</div>

</section>

<section class="pub-section">

## Books  

### Editorship  

<div class="pub-list">

<article class="pub-card" data-tags="book edited-book">
  <div class="pub-meta">
    <span class="pub-badge">2021</span>
    <span class="pub-badge">Edited book</span>
  </div>
  <div class="pub-title">Synergy II: Linguistics: Contemporary studies on Turkish linguistics</div>
  <div class="pub-citation">Söylemez, A. S., &amp; <strong>Kumcu, A.</strong> (Eds.). (2021). <em>Synergy II: Linguistics: Contemporary studies on Turkish linguistics</em>. Peter Lang.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://www.peterlang.com/abstract/title/75216?rskey=7oZpw0" target="_blank" rel="noopener noreferrer">Publisher page</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Söylemez, A. S., & Kumcu, A. (Eds.). (2021). Synergy II: Linguistics: Contemporary studies on Turkish linguistics. Peter Lang.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="book edited-book open pdf">
  <div class="pub-meta">
    <span class="pub-badge">2021</span>
    <span class="pub-badge">Edited book</span>
    <span class="pub-badge">PDF</span>
  </div>
  <div class="pub-title">Engelsiz erişim ve iletişim</div>
  <div class="pub-citation">Cihan, A., Gökduman, U., &amp; <strong>Kumcu, A.</strong> (Eds.). (2021). <em>Engelsiz erişim ve iletişim</em>. İletişim Başkanlığı Yayınları.</div>
  <div class="pub-note">English title: Accessibility and Communication.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://www.iletisim.gov.tr/images/uploads/dosyalar/Engelsiz_Eris%CC%A7im_ve_I%CC%87letis%CC%A7im_Kitab%C4%B1_%281%29.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Cihan, A., Gökduman, U., & Kumcu, A. (Eds.). (2021). Engelsiz erişim ve iletişim. İletişim Başkanlığı Yayınları.">Copy citation</button>
  </div>
</article>

</div>

### Book chapters  

<div class="pub-list">

<article class="pub-card" data-tags="book chapter inpress">
  <div class="pub-meta">
    <span class="pub-badge">2026</span>
    <span class="pub-badge">Book chapter</span>
    <span class="pub-badge">Forthcoming</span>
  </div>
  <div class="pub-title">Ne Soyut Temsiller Ne Temsilsiz Zihin: Üçüncü Alternatif Temsilsel Bedenlenme</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2026). In xxx (Eds.), <em>Bilişsel Bilim Felsefesi</em> (pp. xxx–xxx). Doruk Yayınları.</div>
  <div class="pub-links">
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2026). Ne Soyut Temsiller Ne Temsilsiz Zihin: Üçüncü Alternatif Temsilsel Bedenlenme. In xxx (Eds.), Bilişsel Bilim Felsefesi (pp. xxx–xxx). Doruk Yayınları.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="book chapter open data">
  <div class="pub-meta">
    <span class="pub-badge">2025</span>
    <span class="pub-badge">Book chapter</span>
    <span class="pub-badge">Data available</span>
  </div>
  <div class="pub-title">It's High Time: A Corpus and NLP-Based Investigation of the Time Metaphors in Turkish</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2025). In H. Cangır, K. Uzun, T. Can, &amp; E. Oğuz (Eds.), <em>Exploration of the Intersection of Corpus Linguistics and Language Science</em> (pp. 223–252). IGI Global Scientific Publishing.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://doi.org/10.4018/979-8-3693-8146-5.ch010" target="_blank" rel="noopener noreferrer">DOI</a>
    <a class="pub-link" href="https://osf.io/ynwdm/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2025). It's High Time: A Corpus and NLP-Based Investigation of the Time Metaphors in Turkish. In H. Cangır, K. Uzun, T. Can, & E. Oğuz (Eds.), Exploration of the Intersection of Corpus Linguistics and Language Science (pp. 223–252). IGI Global Scientific Publishing. https://doi.org/10.4018/979-8-3693-8146-5.ch010">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="book chapter open data pdf">
  <div class="pub-meta">
    <span class="pub-badge">2022</span>
    <span class="pub-badge">Book chapter</span>
    <span class="pub-badge">Open materials</span>
  </div>
  <div class="pub-title">Space-time mapping in Turkish: A corpus-based, crosslinguistic investigation</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2022). In B. Süverdem &amp; S. Tekalp (Eds.), <em>Linguistics: Cross-Cultural Perspectives</em> (pp. 29–49). Peter Lang.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://alperkumcu.github.io/pdfs/Space-time_mapping_in_Turkish.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <a class="pub-link" href="https://osf.io/3ksfb/" target="_blank" rel="noopener noreferrer">Data</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2022). Space-time mapping in Turkish: A corpus-based, crosslinguistic investigation. In B. Süverdem & S. Tekalp (Eds.), Linguistics: Cross-Cultural Perspectives (pp. 29–49). Peter Lang.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="book chapter proceedings">
  <div class="pub-meta">
    <span class="pub-badge">2016</span>
    <span class="pub-badge">Conference proceedings</span>
  </div>
  <div class="pub-title">Spatial interference and individual differences in looking at nothing for verbal memory</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong>, &amp; Thompson, R. L. (2016). In A. Papafragou, D. Grodner, D. Mirman, &amp; J. C. Trueswell (Eds.), <em>Proceedings of the 38th Annual Conference of the Cognitive Science Society</em> (pp. 2387–2392). Cognitive Science Society.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://mindmodeling.org/cogsci2016/papers/0413/index.html" target="_blank" rel="noopener noreferrer">Proceedings</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A., & Thompson, R. L. (2016). Spatial interference and individual differences in looking at nothing for verbal memory. In A. Papafragou, D. Grodner, D. Mirman, & J. C. Trueswell (Eds.), Proceedings of the 38th Annual Conference of the Cognitive Science Society (pp. 2387–2392). Cognitive Science Society.">Copy citation</button>
  </div>
</article>

<article class="pub-card" data-tags="book chapter open pdf">
  <div class="pub-meta">
    <span class="pub-badge">2013</span>
    <span class="pub-badge">Book chapter</span>
    <span class="pub-badge">PDF</span>
  </div>
  <div class="pub-title">A transnational and translational hi(story): role of translation and interpreting in the course of Turkish Republic accession to the European Union</div>
  <div class="pub-citation"><strong>Kumcu, A.</strong> (2013). In R. Kumar (Ed.), <em>Role of Translation in Nation Building</em> (pp. 73–85). Modlingua. ISBN: 978-81-926798-0-8.</div>
  <div class="pub-links">
    <a class="pub-link" href="https://alperkumcu.github.io/pdfs/A%20transnational%20and%20translational%20history.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Kumcu, A. (2013). A transnational and translational hi(story): role of translation and interpreting in the course of Turkish Republic accession to the European Union. In R. Kumar (Ed.), Role of Translation in Nation Building (pp. 73–85). Modlingua.">Copy citation</button>
  </div>
</article>

</div>

### Translation  

<div class="pub-list">

<article class="pub-card" data-tags="book translation">
  <div class="pub-meta">
    <span class="pub-badge">2014</span>
    <span class="pub-badge">Translation</span>
  </div>
  <div class="pub-title">Yeni hümanistler: İnsandan evrene son bilimsel tartışmalar</div>
  <div class="pub-citation">Brockman, J. (Ed.). (2014). <em>Yeni hümanistler: İnsandan evrene son bilimsel tartışmalar</em>. N. Büyükkantarcıoğlu &amp; <strong>A. Kumcu</strong>, Trans. TÜBİTAK Popüler Bilim Yayınları. Original work published 2003.</div>
  <div class="pub-note">Original title: <em>The New Humanists: Science at the Edge</em>.</div>
  <div class="pub-links">
    <button class="pub-copy" onclick="copyPubCitation(this)" data-citation="Brockman, J. (Ed.). (2014). Yeni hümanistler: İnsandan evrene son bilimsel tartışmalar. N. Büyükkantarcıoğlu & A. Kumcu, Trans. TÜBİTAK Popüler Bilim Yayınları. Original work published 2003.">Copy citation</button>
  </div>
</article>

</div>

</section>

<script>
function filterPubs(tag, button) {
  const cards = document.querySelectorAll('.pub-card');
  const buttons = document.querySelectorAll('.pub-filter');
  const sections = document.querySelectorAll('.pub-section');

  buttons.forEach(btn => btn.classList.remove('active'));
  button.classList.add('active');

  cards.forEach(card => {
    const tags = card.dataset.tags || '';
    if (tag === 'all' || tags.split(' ').includes(tag)) {
      card.style.display = 'block';
    } else {
      card.style.display = 'none';
    }
  });

  sections.forEach(section => {
    const visibleCards = section.querySelectorAll('.pub-card[style*="display: block"], .pub-card:not([style])');
    let hasVisible = false;

    section.querySelectorAll('.pub-card').forEach(card => {
      if (card.style.display !== 'none') {
        hasVisible = true;
      }
    });

    section.style.display = hasVisible ? 'block' : 'none';
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
  }).catch(() => {
    button.textContent = 'Copy failed';
  });
}
</script>