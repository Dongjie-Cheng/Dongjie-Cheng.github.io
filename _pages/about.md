---
permalink: /
title: "Introduction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


* I’m a Junior student at Sichuan University. As the top-ranked student in my grade majoring in Artificial Intelligence, I was honored with the 2023 China National Scholarship for my academic excellence. 
* My research interests lie in emerging areas such as multimodal content generation and LLM (Large Language Models)-driven Retrieval-Augmented Generation (RAG).
* Currently, I serve as a research assistant in **Dr. Kang Li**'s Lab at the **West China Hospital – Big Data Center**, where my contributions span several projects, including the evaluation and improvement of the Segment Anything Model (SAM), and exploring evaluation methods for T2i (text-to-image) generation. 
* I am dedicated to conducting and publishing high-quality research as a pivotal step towards strengthening my application for a PhD program in the fall of 2025.

Current
======
* I am looking for remote internships, summer internships in 2024, and PhD opportunities in 2025.

Education
======
* B.S. in Artificial Intelligence, Sichuan University, Junior Year

Research Publication
======
Z.QIN, D,CHENG… ***The Good, The Bad, and The Hallucinated: Evaluating Hallucinations in Text-to-Image Models with Knowledge-Enhanced GraphQA Agent***  *Co-First Author, Submitted to IJCAI-2024*

CHENG, D., QIN, Z., JIANG, Z., ZHANG, S., LAO, Q., & LI, K. (2023). ***SAM on Medical Images: A Comprehensive Study on Three Prompt Modes***  *Co-First Author, ArXiv, abs/2305.00035.*

ZEKUN.J, DONGJIE.C… ***Enhancing SAM Zero-Shot Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation***  *Co-First Author, submitted to Big Data Mining and Analytics(IF=13.6), ArXiv, abs/2402.15759*

Experience
======
* **WEST CHINA HOSPITAL – BIG DATA CENTER	Chengdu,  Sichuan**
  * Research Assitant of **Dr.Kang Li** ’s Lab                                                        * February 22, 2023 - Present
  * Supervisor: **Dr.Kang Li**, **Dr.Qicheng Lao**
  


Projects
------
**SAM project**

In the SAM project, We proposed using large models to generate descriptions for segmentation targets, feeding theses descriptions to the detection model to produce bounding boxes for SAM, thereby achieving zero-shot segmentation. 
I was responsible for conceiving and implementing specific experiments. Firstly, I completed the evaluation of the SAM model on multiple modalities medical datasets. Then I verified the effectiveness of the improvement method driven by LLM (Large Language Models). 
The results show that the improved method performs well under zero-shot conditions, outperforming the Grounded-SAM baseline on most datasets. The project ultimately resulted in two papers, of which I am a co-first author.
  * ***SAM on Medical Images: A Comprehensive Study on Three Prompt Modes.***                 
  *	***Enhancing SAM Zero-Shot Performance on Multimodal Medical Images Using GPT-4 Generated Descriptive Prompts Without Human Annotation***


**T2i-Eval project**

In the T2i-Eval project, we proposed a method combining Scene Graph and Graph QA to score the quality of generated images, conducting a comprehensive evaluation of images from perspectives such as object omission, attribute inaccuracies, relational errors, and hallucinations.
I was responsible for generating evaluation dataset images, the specific design and experimentation of the Scene Graph part, achieving the construction of Scene Graphs through the use of GroundingDINO+BLIP VQA.
We constructed a human-evaluated dataset containing 12,000 images from 1,000 prompts and validated the effectiveness of our method. Compared with human evaluations, our Pearson and Kendall correlation coefficients surpassed those of T2ICompbench(Neurips 2023). This project ultimately resulted in one paper, for which I am a co-first author.
  * ***The Good, The Bad, and The Hallucinated: Evaluating Hallucinations in Text-to-Image Models with Knowledge-Enhanced GraphQA Agent***


Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
