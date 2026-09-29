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

I received my PhD in Artificial Intelligence from [KAIST](https://www.kaist.ac.kr/en/) in 2026, advised by Professors [Sung Ju Hwang](http://www.sungjuhwang.com/) and [Juho Lee](https://juho-lee.github.io/) in the [Machine Learning and Artificial Intelligence (MLAI) Lab](https://www.mlai-kaist.com/). My research focuses on AI safety, responsible AI, and evaluation. I also collaborate closely with [Kenji Kawaguchi](https://ml.comp.nus.edu.sg/kawaguchi). I was a recipient of the [2023 Apple Scholars in AI/ML PhD Fellowship](https://machinelearning.apple.com/updates/apple-scholars-aiml-2023). Here is my [CV](https://seanie12.github.io/assets/cv.pdf).

During my PhD, I interned with Apple Machine Learning Research in Seattle, working on synthetic data generation for tool-calling language models. I also interned at Krafton, [Mila](https://mila.quebec/en/) with [Yoshua Bengio](https://yoshuabengio.org/), Apple Cambridge with [Anders Johannsen](http://www.johannsen.com/) and [Jianpeng Cheng](https://scholar.google.com/citations?user=51FYPYsAAAAJ), and the National University of Singapore with [Kenji Kawaguchi](https://ml.comp.nus.edu.sg/kawaguchi).

# 📖 Education

- *2022–2026*, PhD in Artificial Intelligence, KAIST. Advisors: Sung Ju Hwang and Juho Lee.
- *2020–2022*, MS in Artificial Intelligence, KAIST.
- *2011–2018*, BA in Library and Information Science, Yonsei University.

# 💻 Work Experience

- *2025.10–2026.09*, Research internship, Apple Machine Learning Research, Seattle. Host: Raviteja Vemulapalli.
- *2025.07–2025.10*, Research internship, Krafton, Seoul.
- *2024.01–2024.06*, Research internship, [Mila](https://mila.quebec/en/), Montreal. Advisor: [Yoshua Bengio](https://yoshuabengio.org/).
- *2023.05–2023.09*, Research internship, Apple Cambridge. Host: [Anders Johannsen](http://www.johannsen.com/).
- *2022.07–2022.09*, Remote research internship, [National University of Singapore](https://ml.comp.nus.edu.sg/). Advisor: [Kenji Kawaguchi](https://ml.comp.nus.edu.sg/kawaguchi).

# 📝 Publications

*An asterisk (\*) denotes equal contribution. My name is shown in bold.*

## Preprints

- **Simulate to Generalize: Scaling Stateful Supervision for API-calling Agents using LLM World Models** [[paper]](https://arxiv.org/abs/2607.16900)  
  **Seanie Lee**, Sanjoy Chowdhury, Chao Jiang, Cheng-Yu Hsieh, Ting-Yao Hu, Alexander T. Toshev, Oncel Tuzel, and Raviteja Vemulapalli  
  **arXiv 2026**

## Conferences and Journals

- **THINKSAFE: Self-Generated Safety Alignment for Reasoning Models** [[paper]](https://arxiv.org/abs/2601.23143) [[code]](https://github.com/seanie12/ThinkSafe)  
  **Seanie Lee\***, Sangwoo Park\*, Yumin Choi, Gyeongman Kim, Minki Kang, Jihun Yun, Dongmin Park, Jongho Park, and Sung Ju Hwang  
  **NeurIPS 2026**

- **It Takes Two: Complementary Self-Distillation for Contextual Integrity in LLMs** [[paper]](https://arxiv.org/abs/2605.20258) [[code]](https://github.com/sw-programmer/SelfCI)  
  Sangwoo Park\*, Woongyeong Yeo\*, **Seanie Lee**, Yumin Choi, Hyomin Lee, Kangsan Kim, Jinheon Baek, Seong Joon Oh, and Sung Ju Hwang  
  **NeurIPS 2026**

- **T-MAP: Red-Teaming LLM Agents with Trajectory-aware Evolutionary Search** [[paper]](https://arxiv.org/abs/2603.22341) [[code]](https://github.com/pwnhyo/T-MAP)  
  Hyomin Lee, Sangwoo Park, Yumin Choi, Sohyun An, **Seanie Lee**, and Sung Ju Hwang  
  **EMNLP 2026**

- **Rethinking Reward Models for Multi-Domain Test-Time Scaling** [[paper]](https://arxiv.org/abs/2510.00492) [[code]](https://github.com/db-Lee/Multi-RM)  
  Dong Bok Lee\*, **Seanie Lee\***, Sangwoo Park, Minki Kang, Jinheon Baek, Dongki Kim, Dominik Wagner, Jiongdao Jin, Heejun Lee, Tobias Bocklet, Jinyu Wang, Jingjing Fu, Sung Ju Hwang, Jiang Bian, and Lei Song  
  **TMLR 2026**

- **HoliSafe: Holistic Safety Benchmarking and Modeling with Safety Meta Token for Vision-Language Model** [[paper]](https://arxiv.org/abs/2506.04704) [[code]](https://youngwanlee.github.io/holisafe/)  
  Youngwan Lee, Kangsan Kim, Kwanyong Park, Ilcahe Jung, Soojin Jang, **Seanie Lee**, Yong-Ju Lee, and Sung Ju Hwang  
  **CVPR Findings 2025**

- **FedSVD: Adaptive Orthogonalization for Private Federated Learning with LoRA** [[paper]](https://arxiv.org/abs/2505.12805) [[code]](https://github.com/seanie12/fed-svd)  
  **Seanie Lee\***, Sangwoo Park\*, Dong Bok Lee\*, Dominik Wagner, Haebin Seong, Tobias Bocklet, Juho Lee, and Sung Ju Hwang  
  **NeurIPS 2025**

- **Distilling LLM Agent into Small Models with Retrieval and Code Tools** [[paper]](https://arxiv.org/abs/2505.17612) [[code]](https://github.com/Nardien/agent-distillation)  
  Minki Kang, Jongwon Jeong, **Seanie Lee**, Jaewoong Cho, and Sung Ju Hwang  
  **NeurIPS 2025 Spotlight**

- **Reliable Decision-Making via Calibration-Oriented Retrieval-Augmented Generation** [[paper]](https://arxiv.org/abs/2411.08891) [[code]](https://github.com/chaeyoon-jang/calibrag)  
  Chaeyun Jang, Deukhwan Cho, **Seanie Lee**, Hyungi Lee, and Juho Lee  
  **NeurIPS 2025**

- **Trajectory Balance with Asynchrony: Decoupling Exploration and Learning for Fast, Scalable LLM Post-Training** [[paper]](https://arxiv.org/abs/2503.18929) [[code]](https://github.com/bbartoldson/TBA)  
  Brian R. Bartoldson, Siddarth Venkatraman, James Diffenderfer, Moksh Jain, Tal Ben-Nun, **Seanie Lee**, Minsu Kim, Johan Obando-Ceron, Yoshua Bengio, and Bhavya Kailkhura  
  **NeurIPS 2025**

- **SafeRoute: Adaptive Model Selection for Efficient and Accurate Safety Guardrails in Large Language Models** [[paper]](https://arxiv.org/abs/2502.12464) [[code]](https://github.com/seanie12/safe-route)  
  **Seanie Lee\***, Dong Bok Lee\*, Dominik Wagner, Minki Kang, Haebin Seong, Tobias Bocklet, Juho Lee, and Sung Ju Hwang  
  **ACL Findings 2025**

- **Personalized Fine-Tuning with Controllable Synthetic Speech from LLM-Generated Transcripts for Dysarthric Speech Recognition** [[paper]](https://arxiv.org/abs/2505.12991)  
  Dominik Wagner, Ilja Baumann, Natalie Engert, **Seanie Lee**, Elmar Nöth, Korbinian Riedhammer, and Tobias Bocklet  
  **Interspeech 2025**

- **HarmAug: Effective Data Augmentation for Knowledge Distillation of Safety Guard Models** [[paper]](https://arxiv.org/abs/2410.01524) [[code]](https://github.com/hbseong97/HarmAug)  
  **Seanie Lee\***, Haebin Seong\*, Dong Bok Lee, Minki Kang, Xiaoyin Chen, Dominik Wagner, Yoshua Bengio, Juho Lee, and Sung Ju Hwang  
  **ICLR 2025**

- **Learning Diverse Attacks on Large Language Models for Robust Red-teaming and Safety Tuning** [[paper]](https://arxiv.org/abs/2405.18540) [[code]](https://github.com/GFNOrg/red-teaming)  
  **Seanie Lee**, Minsu Kim, Lynn Cherif, David Dobre, Juho Lee, Sung Ju Hwang, Kenji Kawaguchi, Gauthier Gidel, Yoshua Bengio, Nikolay Malkin, and Moksh Jain  
  **ICLR 2025**

- **Optimized Speculative Sampling for GPU Hardware Accelerators** [[paper]](https://arxiv.org/abs/2406.11016) [[code]](https://github.com/dwgnr/optimized-speculative-sampling)  
  Dominik Wagner, **Seanie Lee**, Ilja Baumann, Philipp Seeberger, Korbinian Riedhammer, and Tobias Bocklet  
  **EMNLP 2024**

- **Drug Discovery with Dynamic Goal-aware Fragment** [[paper]](https://arxiv.org/abs/2310.00841) [[code]](https://github.com/SeulLee05/GEAM)  
  Seul Lee, **Seanie Lee**, Kenji Kawaguchi, and Sung Ju Hwang  
  **ICML 2024**

- **Effective and Efficient Conversation Retrieval for Dialogue State Tracking with Implicit Text Summaries** [[paper]](https://aclanthology.org/2024.naacl-long.6/)  
  **Seanie Lee**, Jianpeng Cheng, Joris Driesen, Alexandru Coca, and Anders Johannsen  
  **NAACL 2024**

- **Self-Supervised Dataset Distillation for Transfer Learning** [[paper]](https://arxiv.org/abs/2310.06511) [[code]](https://github.com/db-Lee/selfsup_dd)  
  Dong Bok Lee\*, **Seanie Lee\***, Joonho Ko, Kenji Kawaguchi, Juho Lee, and Sung Ju Hwang  
  **ICLR 2024**

- **DiffusionNAG: Task-guided Neural Architecture Generation with Diffusion Models** [[paper]](https://arxiv.org/abs/2305.16943) [[code]](https://github.com/CownowAn/DiffusionNAG)  
  Sohyun Ahn\*, Hayeon Lee\*, Jaehyeong Jo, **Seanie Lee**, and Sung Ju Hwang  
  **ICLR 2024**

- **Knowledge-Augmented Reasoning Distillation for Small Language Models in Knowledge-Intensive Tasks** [[paper]](https://arxiv.org/abs/2305.18395) [[code]](https://github.com/Nardien/KARD)  
  Minki Kang, **Seanie Lee**, Jinheon Baek, Kenji Kawaguchi, and Sung Ju Hwang  
  **NeurIPS 2023**

- **Scalable Set Encoding with Universal Mini-Batch Consistency and Unbiased Full Set Gradient Approximation** [[paper]](https://arxiv.org/abs/2208.12401) [[code]](https://github.com/jeffwillette/umbc/)  
  Jeffrey Willette\*, **Seanie Lee\***, Bruno Andreis, Kenji Kawaguchi, Juho Lee, and Sung Ju Hwang  
  **ICML 2023**

- **Margin-based Neural Network Watermarking** [[paper]](https://proceedings.mlr.press/v202/kim23o.html)  
  Byungjoo Kim, Suyoung Lee, **Seanie Lee**, Sooel Son, and Sung Ju Hwang  
  **ICML 2023**

- **Self-Supervised Set Representation Learning for Unsupervised Meta-Learning** [[paper]](https://openreview.net/forum?id=kIAx30hYi_p)  
  Dong Bok Lee\*, **Seanie Lee\***, Kenji Kawaguchi, Yunji Kim, Jihwan Bang, Jung-Woo Ha, and Sung Ju Hwang  
  **ICLR 2023**

- **Self-Distillation for Further Pre-training of Transformers** [[paper]](https://openreview.net/forum?id=kj6oK_Hj40) [[code]](https://github.com/seanie12/self-distillation)  
  **Seanie Lee**, Minki Kang, Juho Lee, Sung Ju Hwang, and Kenji Kawaguchi  
  **ICLR 2023**

- **Set-based Meta-Interpolation for Few-Task Meta-Learning** [[paper]](https://arxiv.org/abs/2205.09990)  
  **Seanie Lee\***, Bruno Andreis\*, Kenji Kawaguchi, and Sung Ju Hwang  
  **NeurIPS 2022**

- **On Divergence Measures for Bayesian Pseudocoresets** [[paper]](https://arxiv.org/abs/2210.06205)  
  Balhae Kim, Jungwon Choi, **Seanie Lee**, Yoonho Lee, Jung-Woo Ha, and Juho Lee  
  **NeurIPS 2022**

- **Set Based Stochastic Subsampling** [[paper]](https://proceedings.mlr.press/v162/andreis22a.html)  
  Bruno Andreis, **Seanie Lee**, A. Tuan Nguyen, Juho Lee, Eunho Yang, and Sung Ju Hwang  
  **ICML 2022**

- **Sequential Reptile: Inter-Task Gradient Alignment for Multilingual Learning** [[paper]](https://openreview.net/forum?id=ivQruZvXxtz)  
  **Seanie Lee\***, Hae Beom Lee\*, Juho Lee, and Sung Ju Hwang  
  **ICLR 2022**

- **Learning to Perturb Word Embeddings for Out-of-distribution QA** [[paper]](https://arxiv.org/abs/2105.02692) [[code]](https://github.com/seanie12/SWEP)  
  **Seanie Lee\***, Minki Kang\*, Juho Lee, and Sung Ju Hwang  
  **ACL 2021**

- **Contrastive Learning with Adversarial Perturbations for Conditional Text Generation** [[paper]](https://openreview.net/forum?id=Wga_hrCa3P3) [[code]](https://github.com/seanie12/CLAPS)  
  **Seanie Lee\***, Dong Bok Lee\*, and Sung Ju Hwang  
  **ICLR 2021**

- **Meta-GMVAE: Mixture of Gaussian VAE for Unsupervised Meta-Learning** [[paper]](https://openreview.net/forum?id=wS0UFjsNYjn) [[code]](https://github.com/db-Lee/Meta-GMVAE)  
  Dong Bok Lee, Dongchan Min, **Seanie Lee**, and Sung Ju Hwang  
  **ICLR 2021**

- **Generating Diverse and Consistent QA pairs from Contexts with Information-Maximizing Hierarchical Conditional VAEs** [[paper]](https://aclanthology.org/2020.acl-main.20/) [[code]](https://github.com/seanie12/Info-HCVAE) [[video]](https://slideslive.com/38928851/generating-diverse-and-consistent-qa-pairs-from-contexts-with-informationmaximizing-hierarchical-conditional-vaes)  
  Dong Bok Lee\*, **Seanie Lee\***, WooTae Jeong, Donghwan Kim, and Sung Ju Hwang  
  **ACL 2020**

- **g2pM: A Neural Grapheme-to-Phoneme Conversion Package for Mandarin Chinese Based on a New Open Benchmark Dataset** [[paper]](https://arxiv.org/abs/2004.03136) [[code]](https://github.com/kakaobrain/g2pM)  
  Kyubyong Park\* and **Seanie Lee\***  
  **Interspeech 2020**

# 🎖 Honors and Awards

- *2023*, [Apple Scholars in AI/ML PhD Fellowship](https://machinelearning.apple.com/updates/apple-scholars-aiml-2023).
- *2022*, Google Travel Grant for NeurIPS 2022.
- *2019*, [Silver Medal, Named Entity Recognition in the NAVER NLP Challenge](https://github.com/naver/nlp-challenge).

# 💬 Invited Talks

- *2025.05*, Seminar, Korea University, Seoul. Synthetic Data Generation for LLM Safeguards.
- *2025.04*, Seminar, Hanyang University, Seoul. Synthetic Data Generation for LLM Safeguards.
- *2023.10*, Tech talk, [Nuremberg Institute of Technology Georg Simon Ohm](https://www.th-nuernberg.de/en/). [Scalable Set Encoding with Universal Mini-Batch Consistency and Unbiased Full Set Gradient Approximation](https://docs.google.com/presentation/d/1s0M7g0kkl2tfiAEiX51uMoaAY7-EuEXt/edit?usp=sharing&ouid=117903268632818009810&rtpof=true&sd=true).
- *2023.05*, Tech talk, Samsung SDS. [Scalable Set Encoding with Universal Mini-Batch Consistency and Unbiased Full Set Gradient Approximation](https://docs.google.com/presentation/d/1s0M7g0kkl2tfiAEiX51uMoaAY7-EuEXt/edit?usp=sharing&ouid=117903268632818009810&rtpof=true&sd=true).
- *2020.12*, Tech talk, NAVER. Generating Diverse and Consistent QA pairs from Contexts with Information-Maximizing Hierarchical Conditional VAEs.
