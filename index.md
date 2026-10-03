---
layout: page
---

<style>
  :root {
    --accent: #1f4e8c;
    --accent-soft: #e8eef7;
    --text: #1f2933;
    --muted: #5f6b7a;
    --border: #e3e7ed;
    --bg: #ffffff;
    --bg-alt: #f7f9fb;
  }

  /* Force a consistent light theme (the base theme switches to dark mode) */
  body {
    background: var(--bg) !important;
    color: var(--text) !important;
    font-family: "Inter", "Segoe UI", -apple-system, "Helvetica Neue", Roboto, Arial, sans-serif;
    font-size: 16px;
    line-height: 1.65;
  }
  body > header, body > article, body > footer {
    max-width: 920px;
    width: 100%;
    margin: 0 auto;
    box-sizing: border-box;
  }
  body > header {
    border-bottom: 1px solid var(--border);
  }
  body > header .title {
    font-size: 1.15em;
    font-weight: 700;
    letter-spacing: .02em;
    color: var(--text) !important;
  }
  body > header nav a {
    color: var(--muted) !important;
    font-weight: 500;
  }
  body > header nav a:hover {
    color: var(--accent) !important;
    text-decoration: none;
  }
  body > footer {
    border-top: 1px solid var(--border);
    color: var(--muted);
    font-size: .9em;
  }
  body > footer .icon { fill: var(--muted); }
  body > footer a:hover .icon { fill: var(--accent); }
  article > header { display: none; }
  article { border: none !important; }

  a { color: var(--accent); }
  p { text-align: left; }

  .section-title {
    font-size: 1.25em;
    font-weight: 700;
    color: var(--text);
    margin: 2.2em 0 1em;
    padding-bottom: .35em;
    border-bottom: 2px solid var(--accent);
    display: inline-block;
  }

  /* Bio */
  .bio {
    display: flex;
    gap: 36px;
    align-items: flex-start;
    margin-top: .5em;
  }
  .bio-photo {
    flex: 0 0 180px;
    text-align: center;
  }
  .bio-photo img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    margin: 0;
    box-shadow: 0 2px 10px rgba(0, 0, 0, .12);
  }
  .bio-name {
    font-size: 1.2em;
    font-weight: 700;
    margin: .6em 0 0;
  }
  .bio-role {
    color: var(--muted);
    font-size: .9em;
    line-height: 1.4;
    margin: .2em 0 .8em;
  }
  .bio-links a {
    display: inline-block;
    font-size: .82em;
    font-weight: 600;
    padding: .25em .7em;
    margin: .15em;
    border: 1px solid var(--accent);
    border-radius: 4px;
    color: var(--accent);
  }
  .bio-links a:hover {
    background: var(--accent);
    color: #fff;
    text-decoration: none;
  }
  .bio-text { flex: 1; }
  .bio-text p { margin: 0 0 1em; }

  /* News */
  .news {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  .news li {
    display: flex;
    gap: 16px;
    padding: .45em 0;
    margin: 0;
    border-bottom: 1px dashed var(--border);
  }
  .news li:last-child { border-bottom: none; }
  .news-date {
    flex: 0 0 70px;
    font-weight: 600;
    font-size: .9em;
    color: var(--accent);
    font-variant-numeric: tabular-nums;
    padding-top: .1em;
  }
  .news-text { flex: 1; }

  /* Publications */
  .pub {
    display: flex;
    gap: 24px;
    align-items: center;
    padding: 18px;
    margin-bottom: 18px;
    background: var(--bg-alt);
    border: 1px solid var(--border);
    border-radius: 8px;
  }
  .pub-image {
    flex: 0 0 260px;
  }
  .pub-image img {
    width: 100%;
    margin: 0;
    border-radius: 4px;
    background: #fff;
    border: 1px solid var(--border);
  }
  .pub-details { flex: 1; }
  .pub-title {
    font-size: 1.02em;
    font-weight: 700;
    line-height: 1.4;
    margin: 0 0 .35em;
  }
  .pub-authors {
    font-size: .92em;
    color: var(--muted);
    margin: 0 0 .5em;
  }
  .pub-authors strong { color: var(--text); }
  .pub-venue {
    display: inline-block;
    font-size: .78em;
    font-weight: 700;
    letter-spacing: .02em;
    color: var(--accent);
    background: var(--accent-soft);
    padding: .2em .6em;
    border-radius: 4px;
    margin-right: .4em;
  }
  .pub-links { margin-top: .6em; }
  .pub-links a {
    font-size: .85em;
    font-weight: 600;
    margin-right: .9em;
  }

  @media (max-width: 720px) {
    .bio, .pub {
      flex-direction: column;
      align-items: center;
    }
    .bio-photo { flex-basis: auto; }
    .pub-image { flex-basis: auto; width: 100%; }
  }
</style>

<section class="bio">
  <div class="bio-photo">
    <img src="debrup_profile.png" alt="Photo of Debrup Das">
    <div class="bio-name">Debrup Das</div>
    <div class="bio-role">CS PhD Student<br>UMass Amherst</div>
    <div class="bio-links">
      <a href="DebrupDasCV.pdf">CV</a>
      <a href="mailto:debrupdas@umass.edu">Email</a>
      <a href="https://github.com/Debrup-61/">GitHub</a>
      <a href="https://www.linkedin.com/in/debrup-das-6448a41a7/">LinkedIn</a>
    </div>
  </div>
  <div class="bio-text">
    <p>
      I am a 3rd year Computer Science PhD student at the <a href="https://www.cics.umass.edu/">Manning College of Information &amp; Computer Sciences</a>, <a href="https://www.umass.edu/">University of Massachusetts Amherst</a>, and a member of the <a href="https://ciir.cs.umass.edu/">Center for Intelligent Information Retrieval (CIIR)</a>. I am advised by <a href="https://people.cs.umass.edu/~rahimi/">Prof. Negin Rahimi</a>. My broad research interests are in Information Retrieval (IR) and Natural Language Processing (NLP). Prior to this, I received a Dual Degree (Bachelors + Masters) in Mathematics and Computing from IIT Kharagpur, India, where I worked on tool-augmentation for mathematical reasoning in LLMs, supervised by <a href="https://adityasomak.github.io/">Prof. Somak Aditya</a>.
    </p>
    <p>
      My research focuses on building retrievers that reason about relevance rather than matching surface similarity. I am currently working on: (1) scaling test-time thinking for reasoning-intensive retrieval, (2) reinforcement learning approaches to train retrievers optimized under embedding objectives and retrieval rewards, and (3) memory-augmented systems that retrieve and continually learn from past experiences.
    </p>
  </div>
</section>

<h2 class="section-title">News</h2>
<ul class="news">
  <li>
    <span class="news-date">Aug 2026</span>
    <span class="news-text"><a href="https://arxiv.org/abs/2606.20911">Latent Personal Memory: Represent Personal Memory as Dynamic Soft Prompts</a>, my internship work at Samsung Research America, accepted to Findings of EMNLP 2026, Budapest!</span>
  </li>
  <li>
    <span class="news-date">May 2026</span>
    <span class="news-text">Completed my research internship at <a href="https://sra.samsung.com/">Samsung Research America</a>, AI Center, Mountain View.</span>
  </li>
  <li>
    <span class="news-date">Feb 2026</span>
    <span class="news-text">Started a research internship at <a href="https://sra.samsung.com/">Samsung Research America</a>, AI Center, Mountain View, working on latent-memory-augmented systems for long-context personalized user memory.</span>
  </li>
  <li>
    <span class="news-date">Aug 2025</span>
    <span class="news-text"><a href="https://aclanthology.org/2025.emnlp-main.1011/">RaDeR: Reasoning-aware Dense Retrieval Models</a> accepted as a Main Conference paper at EMNLP 2025, Suzhou, China!</span>
  </li>
  <li>
    <span class="news-date">Apr 2025</span>
    <span class="news-text">Joint work with <a href="https://mbzuai.ac.ae/">MBZUAI</a>, <a href="https://aclanthology.org/2025.naacl-long.463/">SMAB: MAB based Word Sensitivity Estimation Framework and its Applications in Adversarial Text Generation</a>, accepted as a Main Conference paper at NAACL 2025, Albuquerque, New Mexico.</span>
  </li>
  <li>
    <span class="news-date">Sep 2024</span>
    <span class="news-text">Started my PhD at UMass Amherst, advised by Prof. Negin Rahimi!</span>
  </li>
  <li>
    <span class="news-date">Jun 2024</span>
    <span class="news-text">Presented <a href="https://aclanthology.org/2024.naacl-long.54/">MathSensei: A Tool-Augmented Large Language Model for Mathematical Reasoning</a> at <a href="https://2024.naacl.org/">NAACL 2024</a>, Mexico City.</span>
  </li>
  <li>
    <span class="news-date">Dec 2023</span>
    <span class="news-text">Completed my internship at <a href="https://global.rakuten.com/corp/">Rakuten</a>, Language and Speech Processing Team, RIT India.</span>
  </li>
</ul>

<h2 class="section-title">Publications</h2>

<div class="pub">
  <div class="pub-image"><img src="lpm.png" alt="Latent Personal Memory overview"></div>
  <div class="pub-details">
    <div class="pub-title">Latent Personal Memory: Represent Personal Memory as Dynamic Soft Prompts</div>
    <div class="pub-authors"><strong>Debrup Das</strong>, Avinash Amballa, Yashas Malur Saidutta, Vijay Srinivasan, Vivek Kulkarni, Srinivas Chappidi</div>
    <span class="pub-venue">EMNLP 2026 Findings</span>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2606.20911">Paper</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-image"><img src="rader.png" alt="RaDeR overview"></div>
  <div class="pub-details">
    <div class="pub-title">RaDeR: Reasoning-aware Dense Retrieval Models</div>
    <div class="pub-authors"><strong>Debrup Das</strong>, Sam O'Nuallain, Negin Rahimi</div>
    <span class="pub-venue">EMNLP 2025 Main</span>
    <div class="pub-links">
      <a href="https://aclanthology.org/2025.emnlp-main.1011/">Paper</a>
      <a href="https://debrup-61.github.io/RaDeR.github.io/">Website</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-image"><img src="smab.png" alt="SMAB overview"></div>
  <div class="pub-details">
    <div class="pub-title">SMAB: MAB based Word Sensitivity Estimation Framework and its Applications in Adversarial Text Generation</div>
    <div class="pub-authors">Saurabh Kumar Pandey, Sachin Vashistha, <strong>Debrup Das</strong>, Somak Aditya, Monojit Choudhury</div>
    <span class="pub-venue">NAACL 2025 Main</span>
    <div class="pub-links">
      <a href="https://aclanthology.org/2025.naacl-long.463/">Paper</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-image"><img src="mathsensei.png" alt="MathSensei overview"></div>
  <div class="pub-details">
    <div class="pub-title">MathSensei: A Tool-Augmented Large Language Model for Mathematical Reasoning</div>
    <div class="pub-authors"><strong>Debrup Das</strong>, Debopriyo Banerjee, Somak Aditya, Ashish Kulkarni</div>
    <span class="pub-venue">NAACL 2024 Main</span>
    <div class="pub-links">
      <a href="https://aclanthology.org/2024.naacl-long.54/">Paper</a>
      <a href="https://rit.rakuten.com/news/2024/research-on-mathematical-reasoning-accepted-at-naacl-and-me-fomo-2024/">Rakuten News</a>
    </div>
  </div>
</div>
