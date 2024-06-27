permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

* I’m **Dongjie Cheng(程东杰)**, a Junior student at Sichuan University. As the top-ranked student in my grade majoring in Artificial Intelligence last year, I was honored with the **2023 China National Scholarship** for my academic excellence. 
* My research interests lie in emerging areas such as LLM+X(Anything), multimodal content generation. I also always maintain an open mind and am willing to learn new things.
* I used to serve as a research assistant in **Dr. Kang Li**'s Lab at the **West China Hospital – Big Data Center**, where my contributions span several projects, including the evaluation and improvement of the Segment Anything Model (SAM), and exploring evaluation methods for T2i (text-to-image) generation. I am also doing a remote internship at **Dr. Huaxiu Yao**'s Lab, mainly exploring the fine-tuning, alignment, and hallucination mitigation of large multimodal models. Up to now, I have mainly been responsible for and participated in four publications, three of which have been made available on arXiv. <a href='https://scholar.google.com/citations?user=s6x7gQcAAAAJ'><img src="https://img.shields.io/badge/Citations-67-blue.svg?logo=google-scholar"></a>
* I am dedicated to conducting and publishing high-quality research as a pivotal step towards strengthening my application for a PhD program in the fall of 2025.

# 🪧 Current
* I am looking for PhD opportunities in 2025.
* Currently, I am exploring multimodal reasoning, alignment in VLMs.

# 📖 Education
* B.S. in Artificial Intelligence, **Sichuan University**, Junior Year <img src="../images/scu.png" width="5%" height="5%" alt="校徽" align="right">
* GPA: **3.88/4**, **91.83/100**
* Rank: **4/48**
* Last Year's Comprehensive Rank: **1/48**
* CET-6: **636**

# 📝 Research Publication
- ***Calibrated self-rewarding vision language models*** *Co-First Author, [Arxiv, abs/2405.14622](https://arxiv.org/pdf/2405.14622) Submitted to NeurIPS-2024 Main Track*

- ***Evaluating Hallucination in Text-to-Image Diffusion Models with Scene-Graph based Question-Answering Agent***  *Co-First Author, Submitted to NeurIPS-2024 D&B Track*

- ***SAM on Medical Images: A Comprehensive Study on Three Prompt Modes***  *Co-First Author, [ArXiv, abs/2305.00035](https://arxiv.org/pdf/2305.00035), Cited by: 65*

- ***Enhancing SAM Zero-Shot Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation***  *Co-First Author, Submitted to Big Data Mining and Analytics (JCR Q1), [ArXiv, abs/2402.15759](https://arxiv.org/pdf/2402.15759)*

# 💻 Experience

## WEST CHINA HOSPITAL – BIG DATA CENTER	Chengdu,  Sichuan
* Research Assitant of **Dr.Kang Li** ’s Lab
* February 22, 2023 - Present
* Supervisor: **Dr.Kang Li**, **Dr.Qicheng Lao**
  


# 🧩 Projects
## 🎙 **VLM project**
<div class='paper-box'><div class='paper-box-image'><img src='../images/csr.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
  
  📝 ***[Calibrated Self-Rewarding Vision Language Models](https://arxiv.org/pdf/2405.14622)***
  
  🔗 [**Project**](https://dongjie-cheng.github.io/CSR.html)
- Our work addresses misalignment challenges in LVLMs by proposing the Calibrated Self-Rewarding (CSR) approach, which enables the model to self-improve by iteratively generating candidate responses, evaluating the reward for each response, and curating preference data for fine-tuning. In the reward modeling, we employ a step-wise strategy and incorporate visual constraints into the self-rewarding process to place greater emphasis on visual input. Empirical results demonstrate that CSR enhances performance and reduces hallucinations across ten benchmarks and tasks, achieving substantial improvements over existing methods by 7.62%. Our empirical results are further supported by rigorous theoretical analysis, under mild assumptions, verifying the effectiveness of introducing visual constraints into the self-rewarding paradigm.
- I was responsible for the specific implementation and optimization of the CSR method, as well as core tasks such as DPO training and SFT training for VLM.
</div>
</div>

## 👨‍⚕️ **SAM project**

<div class='paper-box'><div class='paper-box-image'><img src='../images/tvsam.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
  
  📝 ***[SAM on Medical Images: A Comprehensive Study on Three Prompt Modes.](https://arxiv.org/pdf/2305.00035)***
  📝 ***[Enhancing SAM Zero-Shot Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation](https://arxiv.org/pdf/2402.15759)***
  
  🔗 [**Project**](https://github.com/JZK00/TV-SAM)
- In the SAM project, We proposed using large models to generate descriptions for segmentation targets, feeding theses descriptions to the detection model to produce bounding boxes for SAM, thereby achieving zero-shot segmentation. 
- I was responsible for conceiving and implementing specific experiments. Firstly, I completed the evaluation of the SAM model on multiple modalities medical datasets. Then I verified the effectiveness of the improvement method driven by LLM (Large Language Models). 
- The results show that the improved method performs well under zero-shot conditions, outperforming the Grounded-SAM baseline on most datasets. The project ultimately resulted in two papers, of which I am a co-first author. 
</div>
</div>

## 📏 **T2i-Eval project**

  📝 ***Evaluating Hallucination in Text-to-Image Diffusion Models with Scene-Graph based Question-Answering Agent***
  
- In the T2i-Eval project, we proposed a method combining Scene Graph and Graph QA to score the quality of generated images, conducting a comprehensive evaluation of images from perspectives such as object omission, attribute inaccuracies, relational errors, and hallucinations.
- I was responsible for generating evaluation dataset images, the specific design and experimentation of the Scene Graph part, achieving the construction of Scene Graphs through the use of GroundingDINO+BLIP VQA.
- We constructed a human-evaluated dataset containing 12,000 images from 1,000 prompts and validated the effectiveness of our method. Compared with human evaluations, our Pearson and Kendall correlation coefficients surpassed those of T2ICompbench(Neurips 2023). This project ultimately resulted in one paper, for which I am a co-first author.
  

# 🎖 Honors & Awards
* <div style="display: flex; justify-content: space-between; align-items: center;"><div>National Scholarship (Awarded yearly to the first ranked student in my major)</div><div>2023.11</div></div>

* <div style="display: flex; justify-content: space-between; align-items: center;"><div>Third Prize, “China Software Cup - Finals”</div><div>2023.08</div></div>

* <div style="display: flex; justify-content: space-between; align-items: center;"><div>Second Prize, “RoboMaster - North Region Competition”</div><div>2023.06</div></div>

# 🔭 Interests
- 🎹 Piano (Amateur Level 10, Issued by Shanghai Conservatory of Music)
- ✏️ Sketch & Quick Sketch (Amateur Level 4&6)
- 🌄 Hiking
- ⚽ Football (I'm a big fan of BVB) <img src="../images/bvb.png" width="1em" height="1em" alt="bvb" style="vertical-align: middle;">


* <div style="display: flex; justify-content: space-between; align-items: center;"><div>Provincial Second Prize, “National College Mathematics Competition”</div><div>2021.12</div></div>


