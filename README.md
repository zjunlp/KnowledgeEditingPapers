# Model Editing Papers

[![Awesome](https://awesome.re/badge.svg)](https://github.com/zjunlp/ModelEditingPapers) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/zjunlp/ModelEditingPapers?color=green) 
![](https://img.shields.io/badge/PRs-Welcome-red)

Must-read papers on [model editing](https://arxiv.org/abs/2305.13172) with foundation models.

## 🔔 News
- **2023-05  We release a new analysis paper:"[Editing Large Language Models: Problems, Methods, and Opportunities](https://arxiv.org/abs/2305.13172)" based on this repository! We are looking forward to any comments or discussions on this topic :)**
- **2022-12 We create this repository to maintain a paper list on *Model Editing*.**

---

## 🔍 Contents

- [🌟 Why Model Editing?](#why-model-editing)
- [Keywords](#keywords)
- [📜 Papers](#papers)
  - [Overview](#survey-and-analysis)
  - [Methods](#methods)
    - [Preserve Parameters](#preserve-parameters)
      - [Memory Based](#memory-based)
      - [Additional Parameters](#additional-parameters)
    - [Modify Parameters](#modify-parameters)
      - [Finetuning](#finetuning)
      - [Meta-learning](#meta-learning)
      - [Locate and edit](#locate-and-edit)
    - [More Related Papers](#more-related-papers)
- [🧰 Resources](#-resources)
    - [Benchmarks and Tasks](#benchmarks-and-tasks)
    - [Tools](#tools)
- [🎉 Contribution](#contribution)
  - [Contributors](#contributors)
  - [Contributing to this paper list](#contributing-to-this-paper-list)
  - [Acknowledgement](#)
- [🚩Citation ](#-citation)

---

## 🌟 Why Model Editing?
Model Editing is a compelling field of research that focuses on facilitating efficient modifications to the behavior of models, particularly **foundation models**. The aim is to implement these changes within a specified scope of interest without negatively affecting the model's performance across a broader range of inputs.

### Keywords 
Model Editing has strong connections with following topics.
- Updating and fixing bugs for large language models
- Language models as knowledge base, locating knowledge in large language models
- Lifelong learning, unlearning and etc.
- Security and privacy for large language models

## 📜 Papers
This is a collection of research and review papers of Model Editing. Any suggestions and pull requests are welcome for better sharing of latest research progress.

### Suvery and Analysis

**Editing Large Language Models: Problems, Methods, and Opportunities**. [[paper](https://arxiv.org/abs/2305.13172)] 
<div align=center><img src="./img/overview.jpg" width="100%" height="80%" /></div>

**Does Localization Inform Editing? Surprising Differences in Causality-Based Localization vs. Knowledge Editing in Language Models.** 
Peter Hase, Mohit Bansal, Been Kim, Asma Ghandeharioun.<br />[[paper](https://arxiv.org/pdf/2301.04213.pdf)] [[code](https://github.com/google/belief-localization)] 
### Methods
#### Preserve Parameters

##### Memory-based

1. Eric Mitchell, Charles Lin, Antoine Bosselut, Christopher D. Manning, Chelsea Finn.<br />
**Memory-Based Model Editing at Scale**. (ICML 2022) [[paper](https://arxiv.org/abs/2206.06520)] [[code](https://github.com/eric-mitchell/serac)] [[demo](https://sites.google.com/view/serac-editing)]

2. Shikhar Murty, Christopher D. Manning, Scott M. Lundberg, Marco Túlio Ribeiro.<br />
  **Fixing Model Bugs with Natural Language Patches**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2211.03318)] [[code](https://github.com/MurtyShikhar/LanguagePatching)]
3. Aman Madaan, Niket Tandon, Peter Clark, Yiming Yang.<br />
  **MemPrompt: Memory-assisted Prompt Editing with User Feedback**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2201.06009)] [[code](https://github.com/madaan/memprompt)] [[page](https://memprompt.com/)] [[video](https://www.youtube.com/watch?v=Ld7R02bOiNQ&t=1s)]
4. Daliang Li, Ankit Singh Rawat, Manzil Zaheer, Xin Wang, Michal Lukasik, Andreas Veit, Felix Yu, Sanjiv Kumar.<br />
  **Large Language Models with Controllable Working Memory**. [[paper](https://arxiv.org/abs/2211.05110)]

5. Ce Zheng, Lei Li, Qingxiu Dong, Yuxuan Fan, Zhiyong Wu, Jingjing Xu, Baobao Chang.<br />
**Can We Edit Factual Knowledge by In-Context Learning?**.[[paper](https://arxiv.org/abs/2305.12740)]
6. Yasumasa Onoe, Michael J.Q. Zhang, Shankar Padmanabhan, Greg Durrett, Eunsol Choi.<br />
**Can LMs Learn New Entities from Descriptions? Challenges in Propagating Injected Knowledge** .[[paper](https://arxiv.org/abs/2305.01651)]
7. Zexuan Zhong, Zhengxuan Wu, Christopher D. Manning, Christopher Potts, Danqi Chen.<br />
**MQUAKE: Assessing Knowledge Editing inLanguage Models via Multi-Hop Questions** .[[paper](https://arxiv.org/abs/2305.14795)]

##### Additional Parameters
1. Qingxiu Dong, Damai Dai, Yifan Song, Jingjing Xu, Zhifang Sui, Lei Li.<br />
  **Calibrating Factual Knowledge in Pretrained Language Models**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2210.03329)] [[code](https://github.com/dqxiu/CaliNet)]
2. Zeyu Huang, Yikang Shen, Xiaofeng Zhang, Jie Zhou, Wenge Rong, Zhang Xiong.<br />
  **Transformer-Patcher: One Mistake worth One Neuron**. (ICLR 2023) [[paper](https://arxiv.org/abs/2301.09785)] [[code](https://github.com/ZeroYuHuang/Transformer-Patcher)]
3. Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim, Marzyeh Ghassemi.<br />
  **Aging with GRACE: Lifelong Model Editing with Discrete Key-Value Adaptors**. [[paper](https://arxiv.org/abs/2211.11031)] [[code](https://github.com/thartvigsen/grace)]
4. Damai Dai, Wenbin Jiang, Qingxiu Dong, Yajuan Lyu, Qiaoqiao She, Zhifang Sui.<br />
  **Neural Knowledge Bank for Pretrained Transformers**.[[paper](http://arxiv.org/abs/2208.00399)]
5. Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim, Marzyeh Ghassemi.<br />
  **Aging with GRACE: Lifelong Model Editing with Discrete Key-Value Adapters**.[[paper](https://arxiv.org/abs/2211.11031)]
##### Change LM's representation space

1. Evan Hernandez, Belinda Z. Li, Jacob Andreas.<br />
  **Inspecting and Editing Knowledge Representations in Language Models**.[[paper](http://arxiv.org/abs/2304.00740)] [[code](https://github.com/evandez/REMEDI)]



#### Modify Parameters
##### Finetuning
1. Kyungjae Lee, Wookje Han, Seung-won Hwang, Hwaran Lee, Joonsuk Park, Sang-Woo Lee.<br />
**Plug-and-Play Adaptation for Continuously-updated QA**. (ACL 2022 Findings) [[paper](https://arxiv.org/abs/2204.12785)] [[code](https://github.com/wookjeHan/Plug-and-Play-Adaptation-for-Continuously-updated-QA)]
2. Chen Zhu, Ankit Singh Rawat, Manzil Zaheer, Srinadh Bhojanapalli, Daliang Li, Felix Yu, Sanjiv Kumar.<br />
**Modifying Memories in Transformer Models**.  [[paper](https://arxiv.org/abs/2012.00363)]

##### Meta-learning

1. Nicola De Cao, Wilker Aziz, Ivan Titov.<br />
**Editing Factual Knowledge in Language Models**. (EMNLP 2021) [[paper](https://arxiv.org/abs/2104.08164)] [[code](https://github.com/nicola-decao/KnowledgeEditor)]

2. Eric Mitchell, Charles Lin, Antoine Bosselut, Chelsea Finn, Christopher D. Manning.<br />
**Fast Model Editing at Scale**. (ICLR 2022) [[paper](https://arxiv.org/abs/2110.11309)] [[code](https://github.com/eric-mitchell/mend)] [[page](https://sites.google.com/view/mend-editing)]
3. Anton Sinitsin, Vsevolod Plokhotnyuk, Dmitry V. Pyrkin, Sergei Popov, Artem Babenko.<br />
**Editable Neural Networks**. (ICLR 2020) [[paper](https://arxiv.org/abs/2004.00345)] [[code](https://github.com/xtinkt/editable)]
##### Locate and edit

1. Shibani Santurkar, Dimitris Tsipras, Mahalaxmi Elango, David Bau, Antonio Torralba, Aleksander Madry.<br />
**Editing a classifier by rewriting its prediction rules**. (NeurIPS 2021) [[paper](https://proceedings.neurips.cc/paper/2021/hash/c46489a2d5a9a9ecfc53b17610926ddd-Abstract.html)] [[code](https://github.com/MadryLab/EditingClassifiers)]


2. Yang Xu, Yutai Hou, Wanxiang Che.<br />
**Language Anisotropic Cross-Lingual Model Editing**. [[paper](https://arxiv.org/abs/2205.12677)] 

3. Ryutaro Tanno, Melanie F. Pradier, Aditya Nori, Yingzhen Li.<br />
**Repairing Neural Networks by Leaving the Right Past Behind**. [[paper](https://arxiv.org/abs/2207.04806)]

4. Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov.<br />
**Locating and Editing Factual Associations in GPT**. (NeurIPS 2022) [[paper](https://arxiv.org/abs/2202.05262)] [[code](https://github.com/kmeng01/rome)] [[page](https://rome.baulab.info/)] [[video](https://www.youtube.com/watch?v=_NMQyOu2HTo&t=0)]

5. Kevin Meng, Arnab Sen Sharma, Alex Andonian, Yonatan Belinkov, David Bau.<br />
**Mass-Editing Memory in a Transformer**. [[paper](https://arxiv.org/abs/2210.07229)] [[code](https://github.com/kmeng01/memit)] [[page](https://memit.baulab.info/)] [[demo](https://memit.baulab.us/#/)]

6. Gabriel Ilharco, Marco Tulio Ribeiro, Mitchell Wortsman, Ludwig Schmidt, Hannaneh Hajishirzi, Ali Farhadi.<br />
**Editing models with task arithmetic** .[[paper](https://openreview.net/pdf?id=6t0Kwf8-jrj)]

7. Anshita Gupta, Debanjan Mondal, Akshay Krishna Sheshadri, Wenlong Zhao, Xiang Lorraine Li, Sarah Wiegreffe, Niket Tandon.<br />
**Editing Commonsense Knowledge in GPT** .[[paper](https://arxiv.org/abs/2305.14956)]

8. Peter Hase, Mona Diab, Asli Celikyilmaz, Xian Li, Zornitsa Kozareva, Veselin Stoyanov, Mohit Bansal, Srinivasan Iyer.<br />
  **Do Language Models Have Beliefs? Methods for Detecting, Updating, and Visualizing Model Beliefs**. [[paper](https://arxiv.org/pdf/2111.13654.pdf)] [[code](https://github.com/peterbhase/SLAG-Belief-Updating)]

9. Jason Hoelscher-Obermaier, Julia Persson, Esben Kran, Ioannis Konstas, Fazl Barez.<br />
**Detecting Edit Failures In Large Language Models: An Improved Specificity Benchmark** .[[paper](https://arxiv.org/abs/2305.17553)]

10. Damai Dai , Li Dong, Yaru Hao, Zhifang Sui, Baobao Chang, Furu Wei.<br />**Knowledge Neurons in Pretrained Transformers**.(ACL 2022)[[paper](http://arxiv.org/abs/2104.08696)] [[code](https://github.com/Hunter-DDM/knowledge-neurons)] [[code by EleutherAI](https://github.com/EleutherAI/knowledge-neurons)]

11. Nora Belrose, David Schneider-Joseph, Shauli Ravfogel, Ryan Cotterell, Edward Raff, Stella Biderman.<br />
**LEACE: Perfect linear concept erasure in closed form** .[[paper](https://arxiv.org/abs/2306.03819)]


#### More Related Papers

1. Robert L. Logan IV, Alexandre Passos, Sameer Singh, Ming-Wei Chang.<br />
**FRUIT: Faithfully Reflecting Updated Information in Text**. (NAACL 2022) [[paper]()] [[code]()]

2. Oyvind Tafjord, Bhavana Dalvi Mishra, Peter Clark.<br />
**Entailer: Answering Questions with Faithful and Truthful Chains of Reasoning**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2210.12217)] [[code](https://github.com/allenai/entailment_bank)] [[video](https://www.youtube.com/watch?v=GYTJ_Pxva7Q)]

3. Ekin Akyürek, Tolga Bolukbasi, Frederick Liu, Binbin Xiong, Ian Tenney, Jacob Andreas, Kelvin Guu.<br />
**Towards Tracing Factual Knowledge in Language Models Back to the Training Data**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2204.12785)]

4. Chenglei Si, Zhe Gan, Zhengyuan Yang, Shuohang Wang, Jianfeng Wang, Jordan Boyd-Graber, Lijuan Wang.<br />
**Prompting GPT-3 To Be Reliable**. [[paper](https://arxiv.org/abs/2210.09150)]

5. Gabriel Ilharco, Mitchell Wortsman, Samir Yitzhak Gadre, Shuran Song, Hannaneh Hajishirzi, Simon Kornblith, Ali Farhadi, Ludwig Schmidt.<br />
  **Patching open-vocabulary models by interpolating weights**. (NeurIPS 2022) [[paper](https://arxiv.org/abs/2208.05592)] [[code](https://github.com/mlfoundations/patching)]

6. Xin Cheng, Yankai Lin, Xiuying Chen, Dongyan Zhao, Rui Yan.<br />**Decouple knowledge from paramters for plug-and-play language modeling**. (ACL2023 Findings)[[paper](http://arxiv.org/abs/2305.11564)] [[code](https://github.com/Hannibal046/PlugLM)]

## 🧰 Resources

### Benchmarks and Tasks

## Contribution
### Contributors

<a href="https://github.com/zjunlp/ModelEditingPapers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zjunlp/ModelEditingPapers" />
</a>

### Contributing to this paper list
-  There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.
