---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<style>
.news-container {
  max-height: 220px;
  overflow-y: auto;
  padding: 15px 16px 15px 18px;
  margin: 0 0 22px 0;
  border-left: 3px solid #224b8d;
  border-radius: 8px;
  background: linear-gradient(to bottom, rgba(255,255,255,0.96), rgba(247,250,255,0.92));
  box-shadow:
    0 -8px 16px -12px rgba(34, 75, 141, 0.18),
    0 8px 16px -12px rgba(34, 75, 141, 0.22),
    0 2px 8px rgba(20, 42, 80, 0.06);
}
.news-container ul { margin-bottom: 0; }
.news-container li { margin-bottom: 0.58em; }
.news-container li:last-child { margin-bottom: 0; }
.news-container::-webkit-scrollbar { width: 6px; }
.news-container::-webkit-scrollbar-track { background: #eef2f8; border-radius: 3px; }
.news-container::-webkit-scrollbar-thumb { background: #9eb2cf; border-radius: 3px; }
.news-container::-webkit-scrollbar-thumb:hover { background: #7e98bd; }

.pub-toggle-container {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 4px 0 18px 0;
}
.pub-toggle-btn {
  min-height: 34px;
  padding: 7px 15px;
  border: 1px solid #224b8d;
  background: transparent;
  color: #224b8d;
  border-radius: 18px;
  cursor: pointer;
  font-weight: 600;
  font-size: 14px;
  line-height: 1;
  transition: all 0.2s ease;
}
.pub-toggle-btn:hover { background: rgba(34, 75, 141, 0.08); }
.pub-toggle-btn.active { background: #224b8d; color: #fff; }
.pub-item {
  margin-bottom: 1.4em;
  padding: 10px 12px;
  border-left: 2px solid #e6edf7;
}
.pub-item p { margin-bottom: 0.3em; }
.full-only { display: none; }
.show-full .full-only { display: block; }

.timeline {
  position: relative;
  padding-left: 24px;
  margin: 10px 0 20px 8px;
}
.timeline::before {
  content: '';
  position: absolute;
  left: 0; top: 0; bottom: 0;
  width: 2px;
  background: linear-gradient(to bottom, #224b8d, #8fb0d9);
}
.timeline-item {
  position: relative;
  padding-bottom: 20px;
}
.timeline-item:last-child { padding-bottom: 0; }
.timeline-item::before {
  content: '';
  position: absolute;
  left: -29px; top: 6px;
  width: 12px; height: 12px;
  border-radius: 50%;
  background: #fff;
  border: 2px solid #224b8d;
}
.timeline-item.current::before {
  background: #224b8d;
  box-shadow: 0 0 0 3px rgba(34, 75, 141, 0.16);
}
.timeline-date { font-size: 13px; color: #777; margin-bottom: 2px; }
.timeline-title { font-weight: 600; font-size: 15px; color: #333; }
.timeline-desc { font-size: 14px; color: #666; }

@media (max-width: 600px) {
  .news-container { max-height: 260px; padding-right: 12px; }
  .pub-toggle-btn { min-height: 32px; padding: 7px 13px; }
}
</style>

Hi, I am Chunkang Zhang (张淳慷).  

🎓 I obtained my M.Sc. degree from the [University of Chinese Academy of Sciences (UCAS)](https://www.ucas.ac.cn/), advised by [Prof. Le Sun](https://www.icip.org.cn/team/sunle/) and [Prof. Yaojie Lu](https://yaojie.lu/). I received my B.S. degree in Software Engineering (Elite Class) from [Wuhan University of Technology (WHUT)](https://english.whut.edu.cn/).


🔬 My research interests include **Agentic Memory**, **Retrieval-Augmented Generation (RAG)**, **Long-Context Comprehension**, and **LLM Alignment**. I work closely with [Jialong Tang](https://tangjialong.github.io/) and [Chulun Zhou](https://encyclomen.github.io/) at Qwen, Alibaba. I also enjoyed close collaboration with [Mo Yu](https://sites.google.com/site/moyunlp/) at Hunyuan, Tencent.


💡 I believe that true intelligence requires not just reasoning, but **remembering** — forming structured, evolving knowledge from raw experience. My ongoing work centers on **OmniModal Memory**: extending agentic memory beyond text into a unified, modality-agnostic framework where agents can perceive, consolidate, and reason across language, vision, and structured data.


📩 If you are interested in my work or potential collaboration, feel free to email me at <zkang5051@gmail.com>.


# 🔥 News

<div class="news-container" markdown="1">

- \[2026.05\] 🎉🎉 [HGMem](https://arxiv.org/abs/2512.23959) is accepted at **ICML 2026**!
- \[2026.05\] 🎉🎉 [Self-Jailbreak](https://arxiv.org/abs/2510.21285) is accepted at **ACL 2026 Findings**！
- \[2026.01\] 🏅 [HGMem](https://arxiv.org/abs/2512.23959) is featured as **#1 Paper of the Day** on [Hugging Face](https://huggingface.co/papers/2512.23959)!
- \[2025.12\] 📄 [HGMem](https://arxiv.org/abs/2512.23959) is released on arXiv — a hypergraph-based working memory mechanism for multi-step RAG.
- \[2025.10\] 📄 [Self-Jailbreak](https://arxiv.org/abs/2510.21285) is released on arXiv — unveiling and mitigating self-jailbreak risks in Large Reasoning Models.
- \[2025.09\] 🚀 The [LongCat-Flash](https://arxiv.org/abs/2509.01322) technical report is released by the Meituan LongCat team — a 560B MoE model trained on 20T+ tokens.
- \[2025.08\] 🎉🎉 [AUTOALIGN](https://aclanthology.org/2025.acl-demo.19/) is accepted at **ACL 2025**.
- \[2025.03\] 🎉🎉 Our paper on the influence of external information on LLMs is published in **IEEE TCSS 2025**.
- \[2024.10\] Concluded internship at **Meituan LLM Group** after contributing to the LongCat series.
- \[2023.08\] 🚀 Started internship at **Meituan LLM Group**, working on long-context LLMs.

</div>

# 📝 Publications

<div class="pub-toggle-container">
  <button class="pub-toggle-btn active" type="button" onclick="showSelectedPubs()">Selected</button>
  <button class="pub-toggle-btn" type="button" onclick="showFullPubs()">Full List</button>
</div>

<div id="publications-container">

<!-- ── SELECTED (always visible) ────────────────────────────────── -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/hgmem.png' alt="HGMem" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HGMem: Hypergraph-based Working Memory to Improve Multi-step RAG for Long-Context Complex Relational Modeling](https://arxiv.org/abs/2512.23959)

<span style="color:#999">Chulun Zhou</span>\*, **Chunkang Zhang**\*, <span style="color:#999">Guoxin Yu, Fandong Meng, Jie Zhou, Wai Lam, Mo Yu</span>

🏅 **#1 Paper of the Day on Hugging Face** \| [arXiv](https://arxiv.org/abs/2512.23959) \| [GitHub](https://github.com/Encyclomen/HGMem) \| [HuggingFace](https://huggingface.co/papers/2512.23959)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/selfjailbreak.png' alt="Self-Jailbreak" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When Models Outthink Their Safety: Unveiling and Mitigating Self-Jailbreak in Large Reasoning Models](https://arxiv.org/abs/2510.21285)

<span style="color:#999">Yingzhi Mao</span>\*, **Chunkang Zhang**\*, <span style="color:#999">Junxiang Wang, Xinyan Guan, Boxi Cao, Yaojie Lu, et al.</span>

[arXiv](https://arxiv.org/abs/2510.21285)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/autoalign.png' alt="AUTOALIGN" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AUTOALIGN: Get Your LLM Aligned with Minimal Annotations](https://aclanthology.org/2025.acl-demo.19/)

<span style="color:#999">Xinyu Lu</span>\*, <span style="color:#999">Dong Xu</span>\*, **Chunkang Zhang**\*, <span style="color:#999">Xinyan Guan, Junxiang Wang, Qingyu Zhang, et al.</span>

[ACL Anthology](https://aclanthology.org/2025.acl-demo.19/) \| [PDF](https://aclanthology.org/2025.acl-demo.19.pdf)
</div>
</div>

**[ChameleonInstruct: Teaching Machines to Reason via Chameleon Game]()**

**Chunkang Zhang**, <span style="color:#999">Yaojie Lu, Hongyu Lin, Cao Liu, Xinyan Guan, Ke Zeng, Guanglu Wan, et al.</span>

*Under Review*
</div>

<div class="pub-item" markdown="1">
<!-- ── FULL LIST ONLY (hidden until "Full List" clicked) ─────────── -->

<div class="full-only">

<div class="pub-item" markdown="1">

**[Investigating Reasoning Models in Retrieval-Augmented Generation]()**

<span style="color:#999">Xinyan Guan, Jiali Zeng, Fandong Meng,</span> **Chunkang Zhang**, <span style="color:#999">Yaojie Lu, Hongyu Lin, et al.</span>

*Under Review*
</div>

<div class="pub-item" markdown="1">

**[ChameleonInstruct: Teaching Machines to Reason via Chameleon Game]()**

**Chunkang Zhang**, <span style="color:#999">Yaojie Lu, Hongyu Lin, Cao Liu, Xinyan Guan, Ke Zeng, Guanglu Wan, et al.</span>

*Under Review*
</div>

<div class="pub-item" markdown="1">

**[Influence of External Information on Large Language Models Mirrors Social Cognitive Patterns](https://ieeexplore.ieee.org/)**

<span style="color:#999">Ning Bian, Hongyu Lin, Peilin Liu, Yaojie Lu,</span> **Chunkang Zhang**, <span style="color:#999">Ben He, Xianpei Han, Le Sun</span>

*IEEE TCSS 2025*
</div>

<div class="pub-item" markdown="1">

**[Pattern Shifting or Knowledge Losing? A Forgetting Perspective for Understanding the Effect of Instruction Fine-Tuning]()**

**Chunkang Zhang**, <span style="color:#999">Boxi Cao, Yaojie Lu, Hongyu Lin, Cao Liu, Ke Zeng, Guanglu Wan, et al.</span>

*CCL 2024*
</div>

<div class="pub-item" markdown="1">

**[A Non-Autoregressive Network for Chinese Text to Speech and Voice Cloning]()**

**Chunkang Zhang**, <span style="color:#999">Yueqing Cai, Wenbi Rao</span>

*ICAICA 2021*
</div>

</div><!-- end full-only -->

</div>

<script>
function showSelectedPubs() {
  document.getElementById('publications-container').classList.remove('show-full');
  document.querySelectorAll('.pub-toggle-btn')[0].classList.add('active');
  document.querySelectorAll('.pub-toggle-btn')[1].classList.remove('active');
}
function showFullPubs() {
  document.getElementById('publications-container').classList.add('show-full');
  document.querySelectorAll('.pub-toggle-btn')[0].classList.remove('active');
  document.querySelectorAll('.pub-toggle-btn')[1].classList.add('active');
}
</script>


# 💼 Experience

<div class="timeline">
  <div class="timeline-item current">
    <div class="timeline-date">2025.06 – present</div>
    <div class="timeline-title">WeChat AI, Tencent</div>
    <div class="timeline-desc">Work closely with <a href="https://sites.google.com/site/moyunlp/">Mo Yu</a> and <a href="https://encyclomen.github.io/">Chulun Zhou</a> (CUHK)</div>
    <div class="timeline-desc">Developed HGMem — a hypergraph-based working memory framework for multi-step RAG.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2023.08 – 2024.10</div>
    <div class="timeline-title">Large Language Model Group, Meituan</div>
    <div class="timeline-desc">Advisor: Cao Liu</div>
    <div class="timeline-desc">Contributed to the LongCat series, focusing on long-context capability and complex instruction following.</div>
  </div>
</div>


# 📖 Educations
- *2022.08 – 2025.06*, M.Sc., Computer Science and Technology, University of Chinese Academy of Sciences (UCAS). Advisor: Prof. Le Sun.
- *2018.08 – 2022.06*, B.S., Software Engineering (Elite Class), Wuhan University of Technology (WHUT). **GPA: 3.9/4.0 (91.14/100).**


# 🎖 Honors and Awards
- Academic Scholarship, UCAS
- Outstanding Thesis & Outstanding Graduate, WHUT
- Academic Scholarship & Outstanding Student Merit, WHUT
- Second Prize, Chinese Collegiate Computing Competition (National Level)
- Best Individual, Cambridge University Summer Exchange Program


# 🎨 Hobbies

Outside of research, I enjoy playing the piano 🎹 (Grade 10 Certification), staying active through fitness 🏋️, badminton 🏸, tennis 🎾, and keeping up with good books 📚. If you share any of these interests, feel free to reach out — always happy to connect!
