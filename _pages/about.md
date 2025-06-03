---
permalink: /
title: "Chenghao Mo"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* Clean and minimal styling with tighter spacing */
.news-item {
  padding: 0.5em 0;
  border-bottom: 1px solid #f0f0f0;
  margin-bottom: 0.3em;
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  font-weight: 700;
  color: #333;
  margin-right: 0.8em;
  font-size: 0.95em;
}

.paper-entry {
  margin-bottom: 1.5em;
  padding: 1.2em;
  background: #fafafa;
  border-radius: 8px;
  border-left: 4px solid #4285f4;
}

.paper-conference-badge {
  display: inline-block;
  background: #4285f4;
  color: white;
  padding: 0.3em 0.8em;
  border-radius: 4px;
  font-size: 0.85em;
  font-weight: 600;
  margin-bottom: 0.6em;
}

.paper-title {
  font-size: 1.2em;
  font-weight: 600;
  color: #333;
  margin-bottom: 0.4em;
  line-height: 1.3;
}

.paper-authors {
  margin-bottom: 0.4em;
  color: #666;
  font-size: 0.95em;
}

.paper-venue {
  font-style: italic;
  color: #888;
  margin-bottom: 0.6em;
  font-size: 0.9em;
}

.paper-highlight {
  color: #d73502;
  font-weight: 600;
  margin-bottom: 0.8em;
  font-size: 0.95em;
}

.paper-buttons {
  margin-top: 0.8em;
}

.paper-buttons a {
  display: inline-block;
  padding: 0.4em 0.8em;
  margin-right: 0.5em;
  background: #4285f4;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  font-size: 0.85em;
  font-weight: 500;
}

.paper-buttons a:hover {
  background: #3367d6;
}

/* Section headers with reduced spacing */
.page__content h2 {
  font-size: 1.5em;
  margin-top: 2em;
  margin-bottom: 0.3em;
  color: #333;
  font-weight: 600;
}

/* Reduce overall content spacing */
.page__content p {
  margin-bottom: 1em;
}

/* Reduce top padding for first news item */
.news-item:first-child {
  padding-top: 0.2em;
}
</style>

I am a Master of Science in Computer Science (MSCS) student at the [University of Illinois at Urbana-Champaign](https://cs.illinois.edu/), working with [Minjia Zhang](https://minjiazhang.github.io/). I am very interested in **large-scale vector databases on GPUs**, efficient data management systems, and high-performance computing for AI applications.

Feel free to reach out via [email](mailto:cmo8@illinois.edu) if you are interested in my research.

## 🔥 News

<div class="news-item">
  <span class="news-date">May 23, 2025</span> Our work on VecFlow has been accepted at <strong>SIGMOD 2026</strong>!
</div>

## 📝 Selected Papers

<div class="paper-entry">
  <div class="paper-conference-badge">SIGMOD'26</div>
  <div class="paper-title">VecFlow: A High-Performance Vector Data Management System for Filtered-Search on GPUs</div>
  <div class="paper-authors">
    Jingyi Xi*†¹, <strong>Chenghao Mo*¹</strong>, Ben Karsin², Artem Chirkin², Mingqin Li³, Minjia Zhang¹<br>
    <small>¹University of Illinois Urbana-Champaign, ²Nvidia, ³Microsoft<br>
    *Both authors contributed equally to this research. †Work done while intern at UIUC.</small>
  </div>
  <div class="paper-venue"><em>Proceedings of the 2026 ACM SIGMOD International Conference on Management of Data. 2026</em></div>
  <div class="paper-highlight">
   The first GPU-accelerated filter-based vector search system, delivering up to 100X higher throughput than state-of-the-arts CPU-based solutions!
  </div>
  <div class="paper-buttons">
    <a href="https://supercomputing-system-ai-lab.github.io/projects/vecflow/">Project Page</a>
    <a href="https://arxiv.org/abs/2506.00812">arXiv</a>
    <a href="https://github.com/Supercomputing-System-AI-Lab/VecFlow/tree/main/vecflow">Code</a>
  </div>
</div>

