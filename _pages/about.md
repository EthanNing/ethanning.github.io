---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.page__title {
  display: none !important;
}

.page__hero {
  display: none !important;
}

.page__hero-caption {
  display: none !important;
}

.page__content {
  margin-top: 0 !important;
  padding-top: 0 !important;
}

.archive {
  margin-top: 0 !important;
  padding-top: 0 !important;
}
</style>

<!-- About Me Section -->
<section id="about">
<h2>About Me</h2>
<p>I'm a Master's student in Computer Science (MCDS) at Carnegie Mellon University, expected to graduate in May 2026. I conduct research on query understanding and neural ranking at the intersection of large language models (LLMs) and information retrieval (IR), under the supervision of Prof. Jamie Callan.</p>

<p>Previously, I worked as a Senior Data Scientist at Tencent, where I led the data science for Tencent Games' Minors Protection program and developed the "Xinyue Mall" game item recommendation system. I also gained industry experience as a Machine Learning Engineer Intern at TikTok, optimizing their recommendation system.</p>

</section>

<!-- News Section -->
<section id="news">
<h2>🔥 News</h2>
<ul>
<li><strong>2025.05</strong>: Started Machine Learning Engineer Internship at TikTok Inc., San Jose</li>
<li><strong>2025.03</strong>: DeepResearchGym paper submitted to NeurIPS 2025 (under review)</li>
<li><strong>2024.12</strong>: Started research on query understanding and neural ranking at CMU</li>
<li><strong>2024.08</strong>: Started Master's program at Carnegie Mellon University</li>
<li><strong>2024.06</strong>: Completed 3 years as Senior Data Scientist at Tencent</li>
</ul>
</section>

<!-- Publications Section -->
<section id="publications">
<h2>📝 Publications</h2>

<div class="publication-item">
  <div class="publication-image">
    <img src="/images/deepresearchgym.png" alt="DeepResearchGym">
  </div>
  <div class="publication-content">
    <h3>DeepResearchGym: A Free, Transparent, and Reproducible Evaluation Sandbox for Deep Research</h3>
    <p class="authors">Coelho, J., <strong>Ning, J.</strong>, He, J., Mao, K., Paladugu, A., Setlur, P., ... & Xiong, C. (2025)</p>
    <p class="venue"><em>Manuscript under review at ICLR 2025</em></p>
    <p class="description">A unified framework for evaluating deep research with reproducible benchmarks and transparent evaluation metrics.</p>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2505.19253" class="btn btn-paper">paper</a>
      <a href="https://github.com/cxcscmu/large-scale-embeddings" class="btn btn-code">code</a>
      <a href="https://deepresearchgym.ai" class="btn btn-project">Gym URL</a>
    </div>
  </div>
</div>


</section>


<!-- Education Section -->
<section id="education">
<h2>🎓 Education</h2>
<h3>Carnegie Mellon University</h3>
<p><strong>Master of Science in Computer Science (MCDS)</strong> | May 2026<br>
Location: Pittsburgh, PA</p>

<h3>The Chinese University of Hong Kong</h3>
<p><strong>Double Degree of BSc Computer Science and BBA Business Analytics</strong> | Jun 2021<br>
Location: Hong Kong</p>
</section>

<!-- Career Section -->
<section id="career">
<h2>💼 Career</h2>

<h3>Research Assistant | Carnegie Mellon University</h3>
<p><strong>Dec 2024 – Present</strong> | Pittsburgh, PA</p>
<ul>
<li>Pursuing research on query understanding and neural ranking at the intersection of LLMs and IR</li>
<li>Supervised by Prof. Jamie Callan (former SIGIR Chair)</li>
<li>Focusing on optimizing RAG systems and query understanding via semantic decomposition</li>
</ul>

<h3>Machine Learning Engineer Intern | TikTok Inc.</h3>
<p><strong>May 2025 – Aug 2025</strong> | San Jose, CA</p>
<ul>
<li>Optimized fine-ranking stage of TikTok Shop's recommendation system</li>
<li>Enhanced semantic alignment with +3.75% lift in offline user-level AUC</li>
<li>Improved online A/B tests: RPG@7 by +0.94% and RPG@14 by +1.12%</li>
</ul>

<h3>Senior Data Scientist | Tencent</h3>
<p><strong>Jul 2021 – Jun 2024</strong> | Shenzhen, China</p>
<ul>
<li>Led data science for Tencent Games' Minors Protection program (730K+ teenagers protected monthly)</li>
<li>Developed "Xinyue Mall" recommendation system from scratch (14.98% ARPU increase, ~$2.13M monthly revenue)</li>
<li>Recognized as top performer with multiple awards including "Outstanding Employee" (top 10%)</li>
</ul>
</section>

<style>
/* 减少段落间距 */
section p {
  margin-bottom: 0.8em !important;
  margin-top: 0.5em !important;
}

section ul, section ol {
  margin-bottom: 0.5em !important;
  margin-top: 0.5em !important;
}

section li {
  margin-bottom: 0.3em !important;
}

section h3 {
  margin-bottom: 0.5em !important;
  margin-top: 0.5em !important;
}

section {
  margin-top: 0 !important;
  padding-top: 0 !important;
  margin-bottom: 2em !important;
}

section:first-child {
  margin-top: 0 !important;
}

section {
  line-height: 1.5 !important;
}

section h2 {
  margin-top: 0.5em !important;
  padding-top: 0 !important;
}
/* Publications 布局样式 */
.publication-item {
  display: flex;
  margin-bottom: 2em;
  padding: 1em;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  gap: 1.5em;
}

.publication-image {
  flex: 0 0 300px;
}

.publication-image img {
  width: 100%;
  height: auto;
  border-radius: 4px;
}

.publication-content {
  flex: 1;
}

.publication-content h3 {
  margin-top: 0;
  margin-bottom: 0.5em;
  font-size: 1.1em;
}

.authors {
  margin-bottom: 0.3em;
  color: #666;
}

.venue {
  margin-bottom: 0.5em;
  font-style: italic;
}

.description {
  margin-bottom: 1em;
  line-height: 1.4;
}

.publication-links {
  display: flex;
  gap: 0.5em;
}

.btn {
  padding: 0.3em 0.8em;
  text-decoration: none;
  border-radius: 4px;
  font-size: 0.9em;
  border: 1px solid;
}

.btn-paper { background-color: #007acc; color: white; border-color: #007acc; }
.btn-code { background-color: #28a745; color: white; border-color: #28a745; }
.btn-project { background-color: #6f42c1; color: white; border-color: #6f42c1; }

/* 响应式设计 */
@media (max-width: 768px) {
  .publication-item {
    flex-direction: column;
  }
  .publication-image {
    flex: none;
  }
}

</style>

