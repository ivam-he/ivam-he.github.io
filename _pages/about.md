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
<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 60px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<span class='anchor' id='about-me'></span>


I am currently a Research Fellow at the School of Computing, [National University of Singapore](https://www.nus.edu.sg/), working with Prof. [Yatao Bian](https://yataobian.com/). Previously, I worked with Prof. [Xiaokui Xiao](https://www.comp.nus.edu.sg/~xiaoxk/) at NUS. I obtained my Ph.D. degree in June 2025 from the Gaoling School of Artificial Intelligence, [Renmin University of China](https://www.ruc.edu.cn/), under the supervision of Prof. [Zhewei Wei](https://weizhewei.com/). Between October 2024 and May 2025, I was a visiting student at the Technical University of Munich, where I collaborated with Prof. [Stephan Günnemann](https://www.professoren.tum.de/guennemann-stephan). Prior to my Ph.D., I earned a B.E. degree in Software Engineering from [Central South University](https://www.csu.edu.cn/) in June 2020.

My research interests lie at the intersection of **Graph Machine Learning**, **Generative Modeling**, and **AI for Science (AI4Science)**, with a current focus on **AI for Drug Discovery (AI4Drug)**. My previous research has primarily focused on **Spectral Graph Neural Networks (GNNs)** and **Graph Transformers**, leveraging spectral and structural properties to develop expressive and efficient graph learning methods. More recently, I have been exploring generative approaches, including diffusion models and energy-based learning, for molecular representation, generation, and optimization, aiming to accelerate drug discovery and molecular design.


# 🔥 News
- *2026.04*: Our paper, "Rethinking Link Prediction for Directed Graphs," was accepted by **IEEE TPAMI 2026**.
- *2026.01*: Our paper, "Robustness in Text-Attributed Graph Learning: Insights, Trade-offs, and New Defenses," was accepted at **ICLR 2026**.
- *2025.05*: We are excited to introduce a new benchmark for Directed Graph Link Prediction, [DirLinkBench](https://arxiv.org/abs/2502.05724).
- *2024.01*: Our paper was accepted at TheWebConf 2024 and selected for oral presentation.

# 📝 Publications 

+  *Rethinking Link Prediction for Directed Graphs.*  [[Paper](https://arxiv.org/abs/2502.05724)][[Code](https://github.com/ivam-he/DirLinkBench-SDGAE)] <br>
**Mingguo He**, Yuhe Guo, Yanping Zheng, Zhewei Wei, Stephan Günnemann, Xiaokui Xiao <br>
Accepted by Transactions on Pattern Analysis and Machine Intelligence. (**TPAMI 2026**) <br>

+ *Robustness in Text-Attributed Graph Learning: Insights, Trade-offs, and New Defenses.* [[Paper](https://openreview.net/forum?id=CEJl0gN2gj)][[Code](https://github.com/Leirunlin/TGRB)] <br>
Runlin Lei, Lu Yi, **Mingguo He**, Pengyu Qiu, Zhewei Wei, Yongchao Liu, Chuntao Hong <br>
In the Fourteenth International Conference on Learning Representations. (**ICLR 2026**) <br>

+ *PolyFormer: Scalable Node-wise Filters via Polynomial Graph Transformer.* [[Paper](https://dl.acm.org/doi/10.1145/3637528.3671849)][[Code](https://github.com/air029/PolyFormer)] <br>
Jiahong Ma, **Mingguo He**, Zhewei Wei. <br>
In Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery & Data Mining. (**KDD 2024**) <br>

+ *Spectral Heterogeneous Graph Convolutions via Positive Noncommutative Polynomials.* [[Paper](https://arxiv.org/abs/2305.19872)][[Code](https://github.com/ivam-he/PSHGCN)] <br>
**Mingguo He**, Zhewei Wei, Shikun Feng, Zhengjie Huang, Weibin Li, Yu Sun, Dianhai Yu.<br>
In Proceedings of the ACM Web Conference 2024. (**TheWebConf 2024**, **Oral 9.4%**) <br>

+  *Convolutional Neural Networks on Graphs with Chebyshev Approximation, Revisited.* [[Paper](https://arxiv.org/abs/2202.03580)][[Code](https://github.com/ivam-he/ChebNetII)] <br>
**Mingguo He**, Zhewei Wei, Ji-Rong Wen.<br>
In the 36th Conference on Neural Information Processing Systems. (**NeurIPS 2022**, **Oral 1.8%**) <br>

+  *BernNet: Learning Arbitrary Graph Spectral Filters via Bernstein Approximation.*  [[Paper](https://arxiv.org/abs/2106.10994)][[Code](https://github.com/ivam-he/BernNet)] <br>
**Mingguo He**, Zhewei Wei, Zengfeng Huang, Hongteng Xu.<br>
The 35th Conference on Neural Information Processing Systems. (**NeurIPS 2021**) <br>

+ *Approximate Graph Propagation.*  [[Paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467243)][[Code](https://github.com/wanghzccls/AGP-Approximate_Graph_Propagation)] <br>
Hanzhi Wang, **Mingguo He**, Zhewei Wei, Sibo Wang, Ye Yuan, Xiaoyong Du, Ji-Rong Wen.<br>
In Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining. (**KDD 2021**) <br>



# 🎖 Honors and Awards
- *2024* National Scholarship for Doctoral Students
- *2020* Provincial Excellent Graduates
- *2018* National Scholarship for Undergraduate Students

  

# 📖 Educations
- *2020.09 - 2025.06*: Ph.D. in Artificial Intelligence from the Gaoling School of Artificial Intelligence, Renmin University of China.
- *2024.10 - 2025.03*: Visiting Researcher at the School of Computation, Information and Technology, Technical University of Munich.
- *2016.09 - 2020.06*: B.Eng. in Software Engineering, School of Computer Science, Central South University.


# 💼 Academic Services
I have served as an Area Chair, program committee member, and reviewer for the following conferences and journals:

**Area Chair**
- International Conference on Learning Representations (**ICLR 2027**)

**Program Committee Member / Reviewer**
- Conference on Neural Information Processing Systems (**NeurIPS 2022–2025**)
- International Conference on Machine Learning (**ICML 2023–2026**)
- International Conference on Learning Representations (**ICLR 2024–2026**)
- ACM Web Conference (**TheWebConf 2024–2026**)
- Learning on Graphs Conference (**LoG 2024–2026**)
- AAAI Conference on Artificial Intelligence (**AAAI 2025–2026**)
- ACM International Conference on Web Search and Data Mining (**WSDM 2023–2025**)

**Journal Reviewer**
- IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**)
- IEEE Transactions on Knowledge and Data Engineering (**TKDE**)



# 🌍 Visitor Map

<div style="text-align: center; margin: 20px 0;">
  <script
    type="text/javascript"
    id="mapmyvisitors"
    src="https://mapmyvisitors.com/map.js?d=l_GuPPBrcBRMxdUKgkwlF5MMs0_c59GgaHtLqRHCMc4&cl=ffffff&w=400">
  </script>
</div>

<footer class="site-footer">
  <p>&copy; 2025–2026 Mingguo He. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>


