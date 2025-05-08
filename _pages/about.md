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

Hi, I am a PhD student at the National University of Singapore, supervised by Professor [Kenji Kawaguchi](https://scholar.google.com/citations?user=aLl3rYoAAAAJ&hl=en), driven by a passion for advancing the frontiers of artificial intelligence. My research explores the intersection of **efficiency**, **controllability**, and **explainability** in AI systems.

I started my research journey by delving into explainability—unpacking the “black box” of neural networks to reveal how they make decisions. Over time, my interests have grown broader. Today, I work on making AI not only more transparent but also smarter in its resource use and more controllable in its outputs, empowering us to shape these systems with precision and trust.

Prior to my PhD study, I finished my master’s at the Technical University of Munich, Germany. I spent a great time doing research at CAMP (Chair for Computer Aided Medical Procedures & Augmented Reality) under the supervision of Professor [Nassir Navab](https://scholar.google.de/citations?user=kzoVUPYAAAAJ&hl=en). At CAMP, my research topic was about explainable AI and how to apply explanation methods on neural networks trained for medical purposes.

I did my bachelor’s study at RWTH Aachen University in Germany. My final year thesis and research at the senior stage is about hardware security (logic encryption on microprocessors), supervised by Professor [Rainer Leupers](https://scholar.google.com/citations?user=f57N-_oAAAAJ&hl=de). I spent one year with the group working on my thesis and later as an RA.

My vision is to contribute to the advancement of AI as a transformative tool that enhances the quality of life and addresses meaningful challenges for humanity. I aspire to develop AI systems that are safe, reliable, and impactful, fostering solutions that promote progress and well-being on a global scale. During my part-time, I enjoy traveling to different places, especially relaxing beside the sea, and exploring the other side of our planet through diving.

<!---
My research interests include neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 I have paper accepted at ICML.
- *2025.01*: &nbsp;🎉🎉 I finished my visit at Torr Vision Group, University of Oxford.
- *2024.08*: &nbsp;🎉🎉 I finished my internship at American Express Innovation Lab in Singapore.

# 📄 Preprint
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/resized_image_500x300_ecodiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Effortless Efficiency: Low-Cost Pruning of Diffusion Models](https://arxiv.org/pdf/2412.02852)

**Yang Zhang**, Er Jin, Yanfei Dong, Ashkan Khakzar, Philip Torr, Johannes Stegmaier, Kenji Kawaguchi

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
Diffusion model pruning by neural mask optimization. 

Keywords: **diffusion model**, **structural pruning**

Project homepage: [Here](https://yangzhang-v5.github.io/EcoDiff). Demo: [Here at Huggingface Space](https://huggingface.co/spaces/zhangyang-0123/EcoDiff)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/resized_image_500x300_attributionlab.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AttributionLab: Faithfulness of Feature Attribution Under Controllable Environments](https://arxiv.org/abs/2310.06514)

**Yang Zhang**, Yawei Li, Mina Rezaei, Bernd Bischl, Philip Torr, Ashkan Khakzar, Kenji Kawaguchi

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
A feature attribution evaluation framework that leverages synthetic models and data to ensure correct ground truth knowledge.

Keywords: **feature attribution**, **evaluation metric**, **synthetic data**
</div>
</div>

# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/resized_image_500x300_dual.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Dual-Perspective Approach to Evaluating Feature Attribution Methods](https://openreview.net/forum?id=znlTP5RLur)

Yawei Li, **Yang Zhang**, Kenji Kawaguchi, Ashkan Khakzar, Bernd Bischl, Mina Rezaei

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
An feature attribution evaluation framework that evaluates the soundness and completeness of feature attribution methods.

Keywords: **feature attribution**, **evaluation metric**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/resized_image_500x300_attention_regulation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Semantic Fidelity in Text-to-Image Synthesis: Attention Regulation in Diffusion Models](https://link.springer.com/chapter/10.1007/978-3-031-73016-0_5)

**Yang Zhang**, Teoh Tze Tzun, Lim Wei Hern, Tiviatis Sim, Kenji Kawaguchi

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
An optimization-based approach to enhance the semantic fidelity of text-to-image diffusion models by regulating the attention maps in diffusion models.

Keywords: **diffusion model**, **attention edit**
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2021</div><img src='images/resized_image_500x300_input_iba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained neural network explanation by identifying input features with predictive information](https://proceedings.neurips.cc/paper/2021/hash/a6d259bfbfa2062843ef543e21d7ec8e-Abstract.html)

**Yang Zhang**, Ashkan Khakzar, Yawei Li, Azade Farshad, Seong Tae Kim, Nassir Navab

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
Fine-grained neural network explanation by attributing input features with predictive information.

Keywords: **feature attribution**, **information bottleneck**
</div>
</div>

- [Memory-Efficient Gradient Unrolling for Large-Scale Bi-level Optimization](https://openreview.net/forum?id=ZvFLbEPv6x), Qianli Shen, Yezhen Wang, Zhouhao Yang, Xiang Li, Haonan Wang, Yang Zhang, Jonathan Scarlett, Zhanxing Zhu, Kenji Kawaguchi, **NeurIPS 2024**
- [The stronger the diffusion model, the easier the backdoor: Data poisoning to induce copyright breaches without adjusting finetuning pipeline](https://openreview.net/forum?id=ZvFLbEPv6x), Haonan Wang, Qianli Shen, Yao Tong, Yang Zhang, Kenji Kawaguchi, **ICML 2024**
- [Explaining covid-19 and thoracic pathology model predictions by identifying informative input features](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_37), Ashkan Khakzar, Yang Zhang, Wejdene Mansour, Yuezhi Cai, Yawei Li, Yucheng Zhang, Seong Tae Kim, Nassir Navab, **MICCAI 2021**

# 💻 Internships
- *2024.05 - 2024.08*, Data Scientist Intern, **American Express Decision Science**, Singapore, Singapore.
- *2022.03 - 2022.09*, Research Intern, **Microsoft Research Asia**, Beijing, China.

# 📖 Educations
- Ph.D. student in Computer Science, School of Computing, **National University of Singapore**, Singapore, Singapore.
- M.Sc. in Robotics, Cognition, Intelligence, Department of Computer Science, **Technical University of Munich**, Munich, Germany. 
- B.Sc. in Computer Engineering, Department of Electrical Engineering. **RWTH Aachen University**, Aachen, Germany.

# 💬 Academic Service
- Reviewer for CVPR 2024, 2025, ACM MM 2024, Neurips 2024, AAAI 2025, ICLR 2025

<!---
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
-->

<!---
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

