---
permalink: /
layout: homepage
title: Research
excerpt: "Zhenting Wang is a research scientist at the MBZUAI Institute of Foundation Models working on large language models, reinforcement learning, and agent reasoning."
redirect_from:
  - /about/
  - /about.html
---

<section class="hero" id="about" aria-labelledby="homepage-title">
  <div class="hero-header">
    <div>
      <h1 id="homepage-title">{{ site.author.name | escape }}</h1>
      <p class="hero-role">Research Scientist, <a href="https://ifm.ai/">MBZUAI Institute of Foundation Models</a></p>
      <p class="hero-location">Silicon Valley Lab &middot; {{ site.author.location | escape }}</p>
    </div>
    <img class="hero-avatar" src="{{ '/images/homepage-avatar.jpg' | relative_url }}" width="128" height="128" alt="Illustrated portrait of {{ site.author.name | escape }}">
  </div>

  <div class="hero-bio">
    <p>I am a Research Scientist at the Institute of Foundation Models (IFM), where I work on post-training the K2 series of open-weight foundation models. I am a core contributor to <a href="https://ifm.ai/k2/">K2 Horizon</a>, a family of six models that includes the flagship 375B-A23B mixture-of-experts model.</p>
    <p>For K2 Horizon, I ran production RL and drove the design and implementation of the RL recipe and training infrastructure. I also contributed to mid-training and RL data.</p>
    <p>Before joining IFM, I was a senior manager-level researcher at Accenture’s Center for Advanced AI, a research scientist intern at Meta GenAI, and a research intern at Sony AI. I earned my PhD in <a href="https://www.cs.rutgers.edu/">computer science</a> at <a href="https://www.rutgers.edu/">Rutgers University</a>.</p>
  </div>
  <p class="research-interests"><strong>Research interests</strong> Large language models, reinforcement learning, and agent reasoning.</p>

  <ul class="profile-links" aria-label="Contact and profiles">
    <li><a href="mailto:{{ site.author.email | escape }}">Email</a></li>
    <li><a href="{{ site.author.googlescholar | escape }}">Google Scholar</a></li>
    <li><a href="{{ '/Zhenting_CV.pdf' | relative_url }}">CV</a></li>
    <li><a href="https://github.com/{{ site.author.github | escape }}">GitHub</a></li>
    <li><a href="https://www.linkedin.com/in/{{ site.author.linkedin | escape }}">LinkedIn</a></li>
    <li><a href="https://twitter.com/{{ site.author.twitter | escape }}">X / Twitter</a></li>
  </ul>
</section>

<section class="home-section" id="publications" aria-labelledby="publications-heading">
  <div class="section-heading">
    <h2 id="publications-heading">Selected Publications</h2>
    <a href="{{ site.author.googlescholar | escape }}">Full list on Google Scholar</a>
  </div>

<div class="publication-content" markdown="1">

* [Memex(RL): Scaling Long-Horizon LLM Agents via Indexed Experience Memory](https://arxiv.org/pdf/2603.04257)<br>
**Zhenting Wang**, Huancheng Chen, Jiayun Wang, Wei Wei (Preprint)

* [MCP-Bench: Benchmarking Tool-Using LLM Agents with Complex Real-World Tasks via MCP Servers](https://arxiv.org/pdf/2508.20453)<br>
**Zhenting Wang**, Qi Chang, Hemani Patel, Shashank Biju, Cheng-En Wu, Quan Liu, Aolin Ding, Alireza Rezazadeh, Ankit Shah, Yujia Bao, Eugene Siow<br>
International Conference on Learning Representations 2026 (**ICLR 2026**)<br>
Also in NeurIPS 2025 Workshop on Scaling Environments for Agents

* [DUMP: Automated Distribution-Level Curriculum Learning for RL-based LLM Post-training](https://arxiv.org/pdf/2504.09710)<br>
**Zhenting Wang**, Guofeng Cui, Yu-Jhe Li, Kun Wan, Wentian Zhao<br>
ICLR 2026 Workshop on Navigating and Addressing Data Problems for Foundation Models

* [Token-Budget-Aware LLM Reasoning](https://arxiv.org/pdf/2412.18547)<br>
Tingxu Han\*, **Zhenting Wang**\*, Chunrong Fang, Shiyu Zhao, Shiqing Ma, Zhenyu Chen (Preprint, **\* indicates equal contribution**)<br>
Annual Meeting of the Association for Computational Linguistics 2025 (**ACL 2025** Findings, **<span class="publication-note">HuggingFace Daily Paper Top1, 200+ citations within 12 months from the release.</span>**)

* [MLLM-as-a-Judge for Image Safety without Human Labeling](https://arxiv.org/pdf/2501.00192)<br>
**Zhenting Wang**, Shuming Hu, Shiyu Zhao, Xiaowen Lin, Felix Juefei-Xu, Zhuowei Li, Ligong Han, Harihar Subramanyam, Li Chen, Jianfa Chen, Nan Jiang, Lingjuan Lyu, Shiqing Ma, Dimitris N. Metaxas, Ankit Jain<br>
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (**CVPR 2025 <span class="publication-note">Highlight, Top 2.9%</span>**)

* [Evaluating and Mitigating IP Infringement in Visual Generative AI](https://arxiv.org/pdf/2406.04662)<br>
**Zhenting Wang**, Chen Chen, Vikash Sehwag, Minzhou Pan, Lingjuan Lyu<br>
International Conference on Machine Learning 2025 (**ICML 2025**)

* [EPO: Entropy-regularized Policy Optimization for LLM Agents Reinforcement Learning](https://arxiv.org/pdf/2509.22576)<br>
Wujiang Xu, Wentian Zhao, **Zhenting Wang**, Yu-Jhe Li, Can Jin, Mingyu Jin, Kai Mei, Kun Wan, Dimitris N. Metaxas (Preprint)

* [A Single Layer to Explain Them All: Understanding Massive Activations in Large Language Models](https://arxiv.org/pdf/2605.08504)<br>
Zeru Shi, **Zhenting Wang**, Fan Yang, Qifan Wang, Ruixiang Tang<br>
International Conference on Machine Learning 2026 (**ICML 2026**)

* [Accelerating Multimodal Large Language Models by Searching Optimal Vision Token Reduction](https://arxiv.org/pdf/2412.00556)<br>
Shiyu Zhao, **Zhenting Wang**, Felix Juefei-Xu, Xide Xia, Miao Liu, Xiaofang Wang, Mingfu Liang, Ning Zhang, Dimitris N. Metaxas, Licheng Yu<br>
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (**CVPR 2025**)

* [Exploring Concept Depth: How Large Language Models Acquire Knowledge at Different Layers?](https://arxiv.org/pdf/2404.07066.pdf)<br>
Mingyu Jin, Qinkai Yu, Jingyuan Huang, Qingcheng Zeng, **Zhenting Wang**, Wenyue Hua, Haiyan Zhao, Kai Mei, Yanda Meng, Kaize Ding, Fan Yang, Mengnan Du, Yongfeng Zhang
International Conference on Computational Linguistics 2025 (**COLING 2025**)

* [Visual Agents as Fast and Slow Thinkers](https://arxiv.org/pdf/2408.08862)<br>
Guangyan Sun, Mingyu Jin, **Zhenting Wang**, Cheng-Long Wang, Siqi Ma, Qifan Wang, Ying Nian Wu, Yongfeng Zhang, Dongfang Liu<br>
International Conference on Learning Representations 2025 (**ICLR 2025**)

* [The Hidden Life of Tokens: Reducing Hallucination of Large Vision-Language Models Via Visual Information Steering](https://arxiv.org/abs/2502.03628)<br>
Zhuowei Li, Haizhou Shi, Yunhe Gao, Di Liu, **Zhenting Wang**, Yuxiao Chen, Ting Liu, Long Zhao, Hao Wang, Dimitris N. Metaxas<br>
International Conference on Machine Learning 2025 (**ICML 2025**)

* [ProSec: Fortifying Code LLMs with Proactive Security Alignment](https://arxiv.org/pdf/2411.12882)<br>
Xiangzhe Xu, Zian Su, Jinyao Guo, Kaiyuan Zhang, **Zhenting Wang**, Xiangyu Zhang<br>
International Conference on Machine Learning 2025 (**ICML 2025**)

* [ProLLM: Protein Chain-of-Thoughts Enhanced LLM for Protein-Protein Interaction Prediction](https://www.biorxiv.org/content/10.1101/2024.04.18.590025v1.full.pdf)<br>
Mingyu Jin, Haochen Xue, **Zhenting Wang**, Boming Kang, Ruosong Ye, Kaixiong Zhou, Mengnan Du, Yongfeng Zhang<br>
Conference on Language Modeling 2024 (**COLM 2024**)

* [Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/pdf/2410.02644)<br>
Hanrong Zhang, Jingyuan Huang, Kai Mei, Yifei Yao, **Zhenting Wang**, Chenlu Zhan, Hongwei Wang, Yongfeng Zhang<br>
International Conference on Learning Representations 2024 (**ICLR 2025**)

* [UNICORN: A Unified Backdoor Trigger Inversion Framework](https://arxiv.org/abs/2304.02786)<br>
**Zhenting Wang**, Kai Mei, Juan Zhai, Shiqing Ma<br>
International Conference on Learning Representations 2023 (**ICLR 2023 <span class="publication-note">Spotlight, Top 5.7%</span>**)

</div>
</section>

<!--Publications
======

### Agentic LLM
* [MCP-Bench: Benchmarking Tool-Using LLM Agents with Complex Real-World Tasks via MCP Servers](https://arxiv.org/pdf/2508.20453)  
**Zhenting Wang**, Qi Chang, Hemani Patel, Shashank Biju, Cheng-En Wu, Quan Liu, Aolin Ding, Alireza Rezazadeh, Ankit Shah, Yujia Bao, Eugene Siow (Preprint)

### LLM Reasoning/LLM Post-training

* [DUMP: Automated Distribution-Level Curriculum Learning for RL-based LLM Post-training](https://arxiv.org/pdf/2504.09710)  
**Zhenting Wang**, Guofeng Cui, Kun Wan, Wentian Zhao (Preprint)

* [Token-Budget-Aware LLM Reasoning](https://arxiv.org/pdf/2412.18547)  
Tingxu Han\*, **Zhenting Wang**\*, Chunrong Fang, Shiyu Zhao, Shiqing Ma, Zhenyu Chen (Preprint, **\* indicates equal contribution**)  
Annual Meeting of the Association for Computational Linguistics 2025 (**ACL 2025** Findings, **<font color=red>HuggingFace Daily Paper Top1</font>**)

* [Visual Agents as Fast and Slow Thinkers](https://arxiv.org/pdf/2408.08862)   
Guangyan Sun, Mingyu Jin, **Zhenting Wang**, Cheng-Long Wang, Siqi Ma, Qifan Wang, Ying Nian Wu, Yongfeng Zhang, Dongfang Liu  
International Conference on Learning Representations 2025 (**ICLR 2025**)

* [The Hidden Life of Tokens: Reducing Hallucination of Large Vision-Language Models Via Visual Information Steering](https://arxiv.org/abs/2502.03628)  
Zhuowei Li, Haizhou Shi, Yunhe Gao, Di Liu, **Zhenting Wang**, Yuxiao Chen, Ting Liu, Long Zhao, Hao Wang, Dimitris N. Metaxas  
International Conference on Machine Learning 2025 (**ICML 2025**)

* [ProSec: Fortifying Code LLMs with Proactive Security Alignment](https://arxiv.org/pdf/2411.12882)  
Xiangzhe Xu, Zian Su, Jinyao Guo, Kaiyuan Zhang, **Zhenting Wang**, Xiangyu Zhang  
International Conference on Machine Learning 2025 (**ICML 2025**)

* [ProLLM: Protein Chain-of-Thoughts Enhanced LLM for Protein-Protein Interaction Prediction](https://www.biorxiv.org/content/10.1101/2024.04.18.590025v1.full.pdf)   
Mingyu Jin, Haochen Xue, **Zhenting Wang**, Boming Kang, Ruosong Ye, Kaixiong Zhou, Mengnan Du, Yongfeng Zhang  
Conference on Language Modeling 2024 (**COLM 2024**)


### LLM-as-a-Judge

* [MLLM-as-a-Judge for Image Safety without Human Labeling](https://arxiv.org/pdf/2501.00192)  
**Zhenting Wang**, Shuming Hu, Shiyu Zhao, Xiaowen Lin, Felix Juefei-Xu, Zhuowei Li, Ligong Han, Harihar Subramanyam, Li Chen, Jianfa Chen, Nan Jiang, Lingjuan Lyu, Shiqing Ma, Dimitris N. Metaxas, Ankit Jain  
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (**CVPR 2025 <font color=red>Highlight, Top 2.9%</font>**)

### Responsible Generative AI

* [Evaluating and Mitigating IP Infringement in Visual Generative AI](https://arxiv.org/pdf/2406.04662)  
**Zhenting Wang**, Chen Chen, Vikash Sehwag, Minzhou Pan, Lingjuan Lyu  
International Conference on Machine Learning 2025 (**ICML 2025**)

* [How to Trace Latent Generative Model Generated Images without Artificial Watermark?](https://arxiv.org/pdf/2405.13360)  
**Zhenting Wang**, Vikash Sehwag, Chen Chen, Lingjuan Lyu, Dimitris N. Metaxas, Shiqing Ma  
International Conference on Machine Learning 2024 (**ICML 2024**)

* [DIAGNOSIS: Detecting Unauthorized Data Usages in Text-to-image Diffusion Models](https://arxiv.org/pdf/2307.03108)  
**Zhenting Wang**, Chen Chen, Lingjuan Lyu, Dimitris N. Metaxas, Shiqing Ma  
International Conference on Learning Representations 2024 (**ICLR 2024**)

* [Where Did I Come From? Origin Attribution of AI-Generated Images](https://proceedings.neurips.cc/paper_files/paper/2023/file/ebb4c188fafe7da089b41a9f615ad84d-Paper-Conference.pdf)  
**Zhenting Wang**, Chen Chen, Yi Zeng, Lingjuan Lyu, Shiqing Ma  
Proceedings of Neural Information Processing Systems 2023 (**NeurIPS 2023**)

* [Continuous Concepts Removal in Text-to-image Diffusion Models](https://arxiv.org/pdf/2412.00580)  
Tingxu Han, Weisong Sun, Yanrong Hu, Chunrong Fang, Yonglong Zhang, Shiqing Ma, Tao Zheng, Zhenyu Chen, **Zhenting Wang** (Preprint)

* [CO-SPY: Combining Semantic and Pixel Features to Detect Synthetic Images by AI](https://arxiv.org/pdf/2503.18286)  
Siyuan Cheng, Lingjuan Lyu, **Zhenting Wang**, Xiangyu Zhang, Vikash Sehwag  
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (**CVPR 2025**)

* [Towards Reliable Verification of Unauthorized Data Usage in Personalized Text-to-Image Diffusion Models](https://zhentingwang.github.io/)  
Boheng Li, Yanhao Wei, Yankai Fu, **Zhenting Wang**, Yiming Li, Jie Zhang, Run Wang, Tianwei Zhang  
IEEE Symposiums on Security and Privacy 2025 (**S&P 2025**)

* [Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/pdf/2410.02644)  
Hanrong Zhang, Jingyuan Huang, Kai Mei, Yifei Yao, **Zhenting Wang**, Chenlu Zhan, Hongwei Wang, Yongfeng Zhang  
International Conference on Learning Representations 2024 (**ICLR 2025**)

* [EmojiPrompt: Generative Prompt Obfuscation for Privacy-Preserving Communication with Cloud-based LLMs](https://zhentingwang.github.io/)  
Sam Lin, Wenyue Hua, **Zhenting Wang**, Mingyu Jin, Lizhou Fan, Yongfeng Zhang  
Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics 2025 (**NAACL 2025** Main)

* [Unlocking Adversarial Suffix Optimization Without Affirmative Phrases: Efficient Black-box Jailbreaking via LLM as Optimizer](https://arxiv.org/pdf/2408.11313)  
Weipeng Jiang, **Zhenting Wang**, Juan Zhai, Shiqing Ma, Zhengyu Zhao, Chao Shen  
Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics 2025 (**NAACL 2025** Findings)

* [Uncertainty Quantification for Multiple-Choice Questions is Just One-Token Deep](https://arxiv.org/pdf/2407.11282)  
Qingcheng Zeng, Mingyu Jin, Qinkai Yu, **Zhenting Wang**, Wenyue Hua, Zihao Zhou, Guangyan Sun, Yanda Meng, Shiqing Ma, Qifan Wang, Felix Juefei-Xu, Kaize Ding, Fan Yang, Ruixiang Tang, Yongfeng Zhang
ACM International Conference on Information and Knowledge Management 2025 (**CIKM 2025**)

* [Finding needles in a haystack: A Black-Box Approach to Invisible Watermark Detection](https://arxiv.org/pdf/2403.15955.pdf)  
Minzhou Pan, **Zhenting Wang**, Xin Dong, Vikash Sehwag, Lingjuan Lyu, Xue Lin  
European Conference on Computer Vision 2024 (**ECCV 2024**)

* [Robustness-aware Automatic Prompt Optimization](https://arxiv.org/pdf/2412.18196)  
Zeru Shi, **Zhenting Wang**, Yongye Su, Weidi Luo, Fan Yang, Yongfeng Zhang (Preprint)



### AI Security

* [Data-centric NLP Backdoor Defense from the Lens of Memorization](https://arxiv.org/pdf/2409.14200)  
**Zhenting Wang**, Zhizhi Wang, Mingyu Jin, Mengnan Du, Juan Zhai, Shiqing Ma  
Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics 2025 (**NAACL 2025** Findings)

* [Invisible Backdoor Attack against Self-supervised Learning](https://arxiv.org/pdf/2405.14672)  
Hanrong Zhang*, **Zhenting Wang**\*, Boheng Li, Fulin Lin, Tingxu Han, Mingyu Jin, Chenlu Zhan, Mengnan Du, Hongwei Wang, Shiqing Ma  
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (**CVPR 2025**, **\* indicates equal contribution**)

* [Distribution Preserving Backdoor Attack in Self-supervised Learning](https://www.cs.purdue.edu/homes/taog/docs/SP24.pdf)  
Guanhong Tao*,**Zhenting Wang**\*,Shiwei Feng,Guangyu Shen,Shiqing Ma,Xiangyu Zhang  
IEEE Symposiums on Security and Privacy 2024  
(**S&P 2024, * indicates equal contribution**)

* [UNICORN: A Unified Backdoor Trigger Inversion Framework](https://arxiv.org/abs/2304.02786)  
**Zhenting Wang**, Kai Mei, Juan Zhai, Shiqing Ma  
International Conference on Learning Representations 2023 (**ICLR 2023 <font color=red>Spotlight</font>**)

* [Rethinking the Reverse-engineering of Trojan Triggers](https://arxiv.org/abs/2210.15127)  
**Zhenting Wang**, Kai Mei, Hailun Ding, Juan Zhai, Shiqing Ma  
Proceedings of Neural Information Processing Systems 2022 (**NeurIPS 2022**)

* [Training with More Confidence: Mitigating Injected and Natural Backdoors During Training](https://arxiv.org/abs/2202.06382)  
**Zhenting Wang**, Hailun Ding, Juan Zhai, Shiqing Ma  
Proceedings of Neural Information Processing Systems 2022 (**NeurIPS 2022**)

* [BppAttack: Stealthy and Efficient Trojan Attacks against Deep Neural Networks via Image Quantization and Contrastive Adversarial Learning](https://arxiv.org/abs/2205.13383)  
**Zhenting Wang**, Juan Zhai, Shiqing Ma  
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2022 (**CVPR 2022**)

* [Exploring Inherent Backdoors in Deep Learning Models](https://arxiv.org/abs/2211.15929)  
Guanhong Tao, Siyuan Cheng, **Zhenting Wang**, Shiqing Ma, Shengwei An, Yingqi Liu, Guangyu Shen, Zhuo Zhang, Yunshu Mao, Xiangyu Zhang  
Annual Computer Security Applications Conference 2024 (**ACSAC 2024**)

* [NOTABLE: Transferable Backdoor Attacks Against Prompt-based NLP Models](https://arxiv.org/abs/2305.17826)  
Kai Mei, Zheng Li, **Zhenting Wang**, Yang Zhang, Shiqing Ma  
Annual Meeting of the Association for Computational Linguistics 2023 (**ACL 2023** Main)

* [Complex Backdoor Detection by Symmetric Feature Differencing](https://www.cs.purdue.edu/homes/taog/docs/CVPR22_Liu.pdf)  
Yingqi Liu, Guangyu Shen, Guanhong Tao, **Zhenting Wang**, Shiqing Ma, Xiangyu Zhang  
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2022 (**CVPR 2022**)

### (Multimodal) Large Language Models

* [Accelerating Multimodel Large Language Models by Searching Optimal Vision Token Reduction](https://arxiv.org/pdf/2412.00556)   
Shiyu Zhao, **Zhenting Wang**, Felix Juefei-Xu, Xide Xia, Miao Liu, Xiaofang Wang, Mingfu Liang, Ning Zhang, Dimitris N. Metaxas, Licheng Yu  
IEEE/CVF Conference on Computer Vision and Pattern Recognition 2025 (**CVPR 2025**)

* [Exploring Concept Depth: How Large Language Models Acquire Knowledge at Different Layers?](https://arxiv.org/pdf/2404.07066.pdf)   
Mingyu Jin, Qinkai Yu, Jingyuan Huang, Qingcheng Zeng, **Zhenting Wang**, Wenyue Hua, Haiyan Zhao, Kai Mei, Yanda Meng, Kaize Ding, Fan Yang, Mengnan Du, Yongfeng Zhang
International Conference on Computational Linguistics 2025 (**COLING 2025**)

* [ADO: Automatic Data Optimization for Inputs in LLM Prompts](https://arxiv.org/abs/2502.11436)   
Sam Lin, Wenyue Hua, Lingyao Li, **Zhenting Wang**, Yongfeng Zhang  
Annual Meeting of the Association for Computational Linguistics 2025 (**ACL 2025** Findings)

* [APEER: Automatic Prompt Engineering Enhances Large Language Model Reranking](https://arxiv.org/pdf/2406.14449)   
Can Jin, Hongwu Peng, Shiyu Zhao, **Zhenting Wang**, Wujiang Xu, Ligong Han, Jiahui Zhao, Kai Zhong, Sanguthevar Rajasekaran, Dimitris N. Metaxas  
Resource-efficient Learning Workshop@WWW 2025 (**<font color=red>Best Paper Award @ RelWeb 2025</font>**)

* [Time Series Forecasting with LLMs: Understanding and Enhancing Model Capabilities](https://arxiv.org/pdf/2402.10835)   
Hua Tang, Chong Zhang, Mingyu Jin, Qinkai Yu, **Zhenting Wang**, Xiaobo Jin, Yongfeng Zhang, Mengnan Du (**SIGKDD Explorations 2024**)

* [LED: LLM Enhanced Open-Vocabulary Object Detection without Human Curated Data Generation](https://arxiv.org/pdf/2503.13794)   
Yang Zhou, Shiyu Zhao, Yuxiao Chen, **Zhenting Wang**, Dimitris N. Metaxas (Preprint)

* [Health-LLM: Personalized Retrieval-Augmented Disease Prediction Model](https://arxiv.org/abs/2402.00746)  
Mingyu Jin, Qinkai Yu, Dong Shu, Chong Zhang, Lizhou Fan, Wenyue Hua, Suiyuan Zhu, Yanda Meng, **Zhenting Wang**, Mengnan Du, Yongfeng Zhang (Preprint)

### Computer Vision

* [LoR-VP: Low-Rank Visual Prompting for Efficient Vision Model Adaptation](https://dl.acm.org/doi/abs/10.1145/3394171.3413945)  
Can Jin, Ying Li, Mingyu Zhao, Shiyu Zhao, **Zhenting Wang**, Xiaoxiao He, Ligong Han, Tong Che, Dimitris N. Metaxas  
International Conference on Learning Representations 2024 (**ICLR 2025**)

* [Learning Selective Assignment Network for Scene-aware Vehicle Detection](https://zhentingwang.github.io)  
**Zhenting Wang**, Wei Li, Xiao Wu, Luhan Sheng  
IEEE International Conference on Image Processing 2022 (**ICIP 2022**)

* [CODAN: Counting-driven Attention Network for Vehicle Detection in Congested Scenes](https://dl.acm.org/doi/abs/10.1145/3394171.3413945)  
Wei Li, **Zhenting Wang**, Xiao Wu, Ji Zhang, Qiang Peng, Hongliang Li  
Proceedings of the 28th ACM International Conference on Multimedia (**MM 2020 Oral**)-->

<!--Teaching
======
* Guest Lecture, CS 431: Software Engineering, Rutgers University, Spring 2023
* Teaching Assistant, CS 461: Machine Learning Principles, Rutgers University, Fall 2024
* Teaching Assistant, CS 205: Introduction to Discrete Structures, Rutgers University, Fall 2022, Spring 2024
* Teaching Assistant, CS 213: Software Methodology, Rutgers University, Fall 2023
* Teaching Assistant, CS 431: Software Engineering, Rutgers University, Spring 2023-->
