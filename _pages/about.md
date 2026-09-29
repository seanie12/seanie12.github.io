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

<span class="anchor" id="about-me"></span>

I received my PhD in Artificial Intelligence from <a href="https://www.kaist.ac.kr/en/" style="color: #7289da; text-decoration: none;">KAIST</a> in 2026, advised by Professors <a href="http://www.sungjuhwang.com/" style="color: #7289da; text-decoration: none;">Sung Ju Hwang</a> and <a href="https://juho-lee.github.io/" style="color: #7289da; text-decoration: none;">Juho Lee</a> in the <a href="https://www.mlai-kaist.com/" style="color: #7289da; text-decoration: none;">Machine Learning and Artificial Intelligence (MLAI) Lab</a>. My research focuses on AI safety, responsible AI, and evaluation. I also collaborate closely with <a href="https://ml.comp.nus.edu.sg/kawaguchi" style="color: #7289da; text-decoration: none;">Kenji Kawaguchi</a>. I was a recipient of the <a href="https://machinelearning.apple.com/updates/apple-scholars-aiml-2023" style="color: #7289da; text-decoration: none;">2023 Apple Scholars in AI/ML PhD Fellowship</a>. Here is my <a href="https://seanie12.github.io/assets/cv.pdf" style="color: #7289da; text-decoration: none;">CV</a>.

During my PhD, I interned with Apple Machine Learning Research in Seattle, working on synthetic data generation for tool-calling language models. I also interned at Krafton, <a href="https://mila.quebec/en/" style="color: #7289da; text-decoration: none;">Mila</a> with <a href="https://yoshuabengio.org/" style="color: #7289da; text-decoration: none;">Yoshua Bengio</a>, Apple Cambridge with <a href="http://www.johannsen.com/" style="color: #7289da; text-decoration: none;">Anders Johannsen</a> and <a href="https://scholar.google.com/citations?user=51FYPYsAAAAJ" style="color: #7289da; text-decoration: none;">Jianpeng Cheng</a>, and the National University of Singapore with <a href="https://ml.comp.nus.edu.sg/kawaguchi" style="color: #7289da; text-decoration: none;">Kenji Kawaguchi</a>.

# 📖 Education

- *2022–2026*, PhD in Artificial Intelligence, KAIST. Advisors: Sung Ju Hwang and Juho Lee.
- *2020–2022*, MS in Artificial Intelligence, KAIST.
- *2011–2018*, BA in Library and Information Science, Yonsei University.

# 💻 Work Experience

- *2025.10–2026.09*, Research internship, Apple Machine Learning Research, Seattle. Host: Raviteja Vemulapalli.
- *2025.07–2025.10*, Research internship, Krafton, Seoul.
- *2024.01–2024.06*, Research internship, <a href="https://mila.quebec/en/" style="color: #7289da; text-decoration: none;">Mila</a>, Montreal. Advisor: <a href="https://yoshuabengio.org/" style="color: #7289da; text-decoration: none;">Yoshua Bengio</a>.
- *2023.05–2023.09*, Research internship, Apple Cambridge. Host: <a href="http://www.johannsen.com/" style="color: #7289da; text-decoration: none;">Anders Johannsen</a>.
- *2022.07–2022.09*, Remote research internship, <a href="https://ml.comp.nus.edu.sg/" style="color: #7289da; text-decoration: none;">National University of Singapore</a>. Advisor: <a href="https://ml.comp.nus.edu.sg/kawaguchi" style="color: #7289da; text-decoration: none;">Kenji Kawaguchi</a>.

# 📝 Publications

- <font size="4">Simulate to Generalize: Scaling Stateful Supervision for API-calling Agents using LLM World Models</font>
[[paper]](https://arxiv.org/abs/2607.16900)  
**Seanie Lee**, Sanjoy Chowdhury, Chao Jiang, Cheng-Yu Hsieh, Ting-Yao Hu, Alexander T. Toshev, Oncel Tuzel, and Raviteja Vemulapalli  
<span style="color:purple">**arXiv**</span> 2026

- <font size="4">THINKSAFE: Self-Generated Safety Alignment for Reasoning Models</font>
[[paper]](https://arxiv.org/abs/2601.23143) [[code]](https://github.com/seanie12/ThinkSafe)  
**Seanie Lee\***, Sangwoo Park\*, Yumin Choi, Gyeongman Kim, Minki Kang, Jihun Yun, Dongmin Park, Jongho Park, and Sung Ju Hwang  
<span style="color:purple">**NeurIPS**</span> 2026

- <font size="4">It Takes Two: Complementary Self-Distillation for Contextual Integrity in LLMs</font>
[[paper]](https://arxiv.org/abs/2605.20258) [[code]](https://github.com/sw-programmer/SelfCI)  
Sangwoo Park\*, Woongyeong Yeo\*, **Seanie Lee**, Yumin Choi, Hyomin Lee, Kangsan Kim, Jinheon Baek, Seong Joon Oh, and Sung Ju Hwang  
<span style="color:purple">**NeurIPS**</span> 2026

- <font size="4">T-MAP: Red-Teaming LLM Agents with Trajectory-aware Evolutionary Search</font>
[[paper]](https://arxiv.org/abs/2603.22341) [[code]](https://github.com/pwnhyo/T-MAP)  
Hyomin Lee, Sangwoo Park, Yumin Choi, Sohyun An, **Seanie Lee**, and Sung Ju Hwang  
<span style="color:purple">**EMNLP**</span> 2026

- <font size="4">Rethinking Reward Models for Multi-Domain Test-Time Scaling</font>
[[paper]](https://arxiv.org/abs/2510.00492) [[code]](https://github.com/db-Lee/Multi-RM)  
Dong Bok Lee\*, **Seanie Lee\***, Sangwoo Park, Minki Kang, Jinheon Baek, Dongki Kim, Dominik Wagner, Jiongdao Jin, Heejun Lee, Tobias Bocklet, Jinyu Wang, Jingjing Fu, Sung Ju Hwang, Jiang Bian, and Lei Song  
<span style="color:purple">**TMLR**</span> 2026

- <font size="4">HoliSafe: Holistic Safety Benchmarking and Modeling with Safety Meta Token for Vision-Language Model</font>
[[paper]](https://arxiv.org/abs/2506.04704) [[code]](https://youngwanlee.github.io/holisafe/)  
Youngwan Lee, Kangsan Kim, Kwanyong Park, Ilcahe Jung, Soojin Jang, **Seanie Lee**, Yong-Ju Lee, and Sung Ju Hwang  
<span style="color:purple">**CVPR Findings**</span> 2025

- <font size="4">FedSVD: Adaptive Orthogonalization for Private Federated Learning with LoRA</font>
[[paper]](https://arxiv.org/abs/2505.12805) [[code]](https://github.com/seanie12/fed-svd)  
**Seanie Lee\***, Sangwoo Park\*, Dong Bok Lee\*, Dominik Wagner, Haebin Seong, Tobias Bocklet, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**NeurIPS**</span> 2025

- <font size="4">Distilling LLM Agent into Small Models with Retrieval and Code Tools</font>
[[paper]](https://arxiv.org/abs/2505.17612) [[code]](https://github.com/Nardien/agent-distillation)  
Minki Kang, Jongwon Jeong, **Seanie Lee**, Jaewoong Cho, and Sung Ju Hwang  
<span style="color:purple">**NeurIPS  Spotlight**</span> 2025

- <font size="4">Reliable Decision-Making via Calibration-Oriented Retrieval-Augmented Generation</font>
[[paper]](https://arxiv.org/abs/2411.08891) [[code]](https://github.com/chaeyoon-jang/calibrag)  
Chaeyun Jang, Deukhwan Cho, **Seanie Lee**, Hyungi Lee, and Juho Lee  
<span style="color:purple">**NeurIPS**</span> 2025

- <font size="4">Trajectory Balance with Asynchrony: Decoupling Exploration and Learning for Fast, Scalable LLM Post-Training</font>
[[paper]](https://arxiv.org/abs/2503.18929) [[code]](https://github.com/bbartoldson/TBA)  
Brian R. Bartoldson, Siddarth Venkatraman, James Diffenderfer, Moksh Jain, Tal Ben-Nun, **Seanie Lee**, Minsu Kim, Johan Obando-Ceron, Yoshua Bengio, and Bhavya Kailkhura  
<span style="color:purple">**NeurIPS**</span> 2025

- <font size="4">SafeRoute: Adaptive Model Selection for Efficient and Accurate Safety Guardrails in Large Language Models</font>
[[paper]](https://arxiv.org/abs/2502.12464) [[code]](https://github.com/seanie12/safe-route)  
**Seanie Lee\***, Dong Bok Lee\*, Dominik Wagner, Minki Kang, Haebin Seong, Tobias Bocklet, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**ACL Findings**</span> 2025

- <font size="4">Personalized Fine-Tuning with Controllable Synthetic Speech from LLM-Generated Transcripts for Dysarthric Speech Recognition</font>
[[paper]](https://arxiv.org/abs/2505.12991)  
Dominik Wagner, Ilja Baumann, Natalie Engert, **Seanie Lee**, Elmar Nöth, Korbinian Riedhammer, and Tobias Bocklet  
<span style="color:purple">**Interspeech**</span> 2025

- <font size="4">HarmAug: Effective Data Augmentation for Knowledge Distillation of Safety Guard Models</font>
[[paper]](https://arxiv.org/abs/2410.01524) [[code]](https://github.com/hbseong97/HarmAug)  
**Seanie Lee\***, Haebin Seong\*, Dong Bok Lee, Minki Kang, Xiaoyin Chen, Dominik Wagner, Yoshua Bengio, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2025

- <font size="4">Learning Diverse Attacks on Large Language Models for Robust Red-teaming and Safety Tuning</font>
[[paper]](https://arxiv.org/abs/2405.18540) [[code]](https://github.com/GFNOrg/red-teaming)  
**Seanie Lee**, Minsu Kim, Lynn Cherif, David Dobre, Juho Lee, Sung Ju Hwang, Kenji Kawaguchi, Gauthier Gidel, Yoshua Bengio, Nikolay Malkin, and Moksh Jain  
<span style="color:purple">**ICLR**</span> 2025

- <font size="4">Optimized Speculative Sampling for GPU Hardware Accelerators</font>
[[paper]](https://arxiv.org/abs/2406.11016) [[code]](https://github.com/dwgnr/optimized-speculative-sampling)  
Dominik Wagner, **Seanie Lee**, Ilja Baumann, Philipp Seeberger, Korbinian Riedhammer, and Tobias Bocklet  
<span style="color:purple">**EMNLP**</span> 2024

- <font size="4">Drug Discovery with Dynamic Goal-aware Fragment</font>
[[paper]](https://arxiv.org/abs/2310.00841) [[code]](https://github.com/SeulLee05/GEAM)  
Seul Lee, **Seanie Lee**, Kenji Kawaguchi, and Sung Ju Hwang  
<span style="color:purple">**ICML**</span> 2024

- <font size="4">Effective and Efficient Conversation Retrieval for Dialogue State Tracking with Implicit Text Summaries</font>
[[paper]](https://aclanthology.org/2024.naacl-long.6/)  
**Seanie Lee**, Jianpeng Cheng, Joris Driesen, Alexandru Coca, and Anders Johannsen  
<span style="color:purple">**NAACL**</span> 2024

- <font size="4">Self-Supervised Dataset Distillation for Transfer Learning</font>
[[paper]](https://arxiv.org/abs/2310.06511) [[code]](https://github.com/db-Lee/selfsup_dd)  
Dong Bok Lee\*, **Seanie Lee\***, Joonho Ko, Kenji Kawaguchi, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2024

- <font size="4">DiffusionNAG: Task-guided Neural Architecture Generation with Diffusion Models</font>
[[paper]](https://arxiv.org/abs/2305.16943) [[code]](https://github.com/CownowAn/DiffusionNAG)  
Sohyun Ahn\*, Hayeon Lee\*, Jaehyeong Jo, **Seanie Lee**, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2024

- <font size="4">Knowledge-Augmented Reasoning Distillation for Small Language Models in Knowledge-Intensive Tasks</font>
[[paper]](https://arxiv.org/abs/2305.18395) [[code]](https://github.com/Nardien/KARD)  
Minki Kang, **Seanie Lee**, Jinheon Baek, Kenji Kawaguchi, and Sung Ju Hwang  
<span style="color:purple">**NeurIPS**</span> 2023

- <font size="4">Scalable Set Encoding with Universal Mini-Batch Consistency and Unbiased Full Set Gradient Approximation</font>
[[paper]](https://arxiv.org/abs/2208.12401) [[code]](https://github.com/jeffwillette/umbc/)  
Jeffrey Willette\*, **Seanie Lee\***, Bruno Andreis, Kenji Kawaguchi, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**ICML**</span> 2023

- <font size="4">Margin-based Neural Network Watermarking</font>
[[paper]](https://proceedings.mlr.press/v202/kim23o.html)  
Byungjoo Kim, Suyoung Lee, **Seanie Lee**, Sooel Son, and Sung Ju Hwang  
<span style="color:purple">**ICML**</span> 2023

- <font size="4">Self-Supervised Set Representation Learning for Unsupervised Meta-Learning</font>
[[paper]](https://openreview.net/forum?id=kIAx30hYi_p)  
Dong Bok Lee\*, **Seanie Lee\***, Kenji Kawaguchi, Yunji Kim, Jihwan Bang, Jung-Woo Ha, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2023

- <font size="4">Self-Distillation for Further Pre-training of Transformers</font>
[[paper]](https://openreview.net/forum?id=kj6oK_Hj40) [[code]](https://github.com/seanie12/self-distillation)  
**Seanie Lee**, Minki Kang, Juho Lee, Sung Ju Hwang, and Kenji Kawaguchi  
<span style="color:purple">**ICLR**</span> 2023

- <font size="4">Set-based Meta-Interpolation for Few-Task Meta-Learning</font>
[[paper]](https://arxiv.org/abs/2205.09990)  
**Seanie Lee\***, Bruno Andreis\*, Kenji Kawaguchi, and Sung Ju Hwang  
<span style="color:purple">**NeurIPS**</span> 2022

- <font size="4">On Divergence Measures for Bayesian Pseudocoresets</font>
[[paper]](https://arxiv.org/abs/2210.06205)  
Balhae Kim, Jungwon Choi, **Seanie Lee**, Yoonho Lee, Jung-Woo Ha, and Juho Lee  
<span style="color:purple">**NeurIPS**</span> 2022

- <font size="4">Set Based Stochastic Subsampling</font>
[[paper]](https://proceedings.mlr.press/v162/andreis22a.html)  
Bruno Andreis, **Seanie Lee**, A. Tuan Nguyen, Juho Lee, Eunho Yang, and Sung Ju Hwang  
<span style="color:purple">**ICML**</span> 2022

- <font size="4">Sequential Reptile: Inter-Task Gradient Alignment for Multilingual Learning</font>
[[paper]](https://openreview.net/forum?id=ivQruZvXxtz)  
**Seanie Lee\***, Hae Beom Lee\*, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2022

- <font size="4">Learning to Perturb Word Embeddings for Out-of-distribution QA</font>
[[paper]](https://arxiv.org/abs/2105.02692) [[code]](https://github.com/seanie12/SWEP)  
**Seanie Lee\***, Minki Kang\*, Juho Lee, and Sung Ju Hwang  
<span style="color:purple">**ACL**</span> 2021

- <font size="4">Contrastive Learning with Adversarial Perturbations for Conditional Text Generation</font>
[[paper]](https://openreview.net/forum?id=Wga_hrCa3P3) [[code]](https://github.com/seanie12/CLAPS)  
**Seanie Lee\***, Dong Bok Lee\*, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2021

- <font size="4">Meta-GMVAE: Mixture of Gaussian VAE for Unsupervised Meta-Learning</font>
[[paper]](https://openreview.net/forum?id=wS0UFjsNYjn) [[code]](https://github.com/db-Lee/Meta-GMVAE)  
Dong Bok Lee, Dongchan Min, **Seanie Lee**, and Sung Ju Hwang  
<span style="color:purple">**ICLR**</span> 2021

- <font size="4">Generating Diverse and Consistent QA pairs from Contexts with Information-Maximizing Hierarchical Conditional VAEs</font>
[[paper]](https://aclanthology.org/2020.acl-main.20/) [[code]](https://github.com/seanie12/Info-HCVAE) [[video]](https://slideslive.com/38928851/generating-diverse-and-consistent-qa-pairs-from-contexts-with-informationmaximizing-hierarchical-conditional-vaes)  
Dong Bok Lee\*, **Seanie Lee\***, WooTae Jeong, Donghwan Kim, and Sung Ju Hwang  
<span style="color:purple">**ACL**</span> 2020

- <font size="4">g2pM: A Neural Grapheme-to-Phoneme Conversion Package for Mandarin Chinese Based on a New Open Benchmark Dataset</font>
[[paper]](https://arxiv.org/abs/2004.03136) [[code]](https://github.com/kakaobrain/g2pM)  
Kyubyong Park\* and **Seanie Lee\***  
<span style="color:purple">**Interspeech**</span> 2020

# 🎖 Honors and Awards

- *2023*, <a href="https://machinelearning.apple.com/updates/apple-scholars-aiml-2023" style="color: #7289da; text-decoration: none;">Apple Scholars in AI/ML PhD Fellowship</a>.
- *2022*, Google Travel Grant for NeurIPS 2022.
- *2019*, <a href="https://github.com/naver/nlp-challenge" style="color: #7289da; text-decoration: none;">Silver Medal, Named Entity Recognition in the NAVER NLP Challenge</a>.

# 💬 Invited Talks

- *2025.05*, Seminar, Korea University, Seoul. Synthetic Data Generation for LLM Safeguards.
- *2025.04*, Seminar, Hanyang University, Seoul. Synthetic Data Generation for LLM Safeguards.
- *2023.10*, Tech talk, <a href="https://www.th-nuernberg.de/en/" style="color: #7289da; text-decoration: none;">Nuremberg Institute of Technology Georg Simon Ohm</a>. <a href="https://docs.google.com/presentation/d/1s0M7g0kkl2tfiAEiX51uMoaAY7-EuEXt/edit?usp=sharing&ouid=117903268632818009810&rtpof=true&sd=true" style="color: #7289da; text-decoration: none;">Scalable Set Encoding with Universal Mini-Batch Consistency and Unbiased Full Set Gradient Approximation</a>.
- *2023.05*, Tech talk, Samsung SDS. <a href="https://docs.google.com/presentation/d/1s0M7g0kkl2tfiAEiX51uMoaAY7-EuEXt/edit?usp=sharing&ouid=117903268632818009810&rtpof=true&sd=true" style="color: #7289da; text-decoration: none;">Scalable Set Encoding with Universal Mini-Batch Consistency and Unbiased Full Set Gradient Approximation</a>.
- *2020.12*, Tech talk, NAVER. Generating Diverse and Consistent QA pairs from Contexts with Information-Maximizing Hierarchical Conditional VAEs.
