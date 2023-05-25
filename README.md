# Model Editing Papers

[![Awesome](https://awesome.re/badge.svg)](https://github.com/zjunlp/ModelEditingPapers) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/zjunlp/ModelEditingPapers?color=green) 
![](https://img.shields.io/badge/PRs-Welcome-red)

Must-read papers on [model editing](https://arxiv.org/abs/2305.13172) with foundation models.

## Content

- [Why Model Editing?](#why-model-editing)
- [Keywords](#keywords)
- [Papers](#papers)
  - [Overview](#survey-and-analysis)
  - [Preserve Parameters](#preserve-parameters)
  - [Modify Parameters](#modify-parameters)
  - [More Related Papers](#more-related-papers)
- [Contribution](#contribution)
  - [Contributors](#contributors)
  - [Contributing to this paper list](#contributing-to-this-paper-list)


## Why Model Editing?
Model Editing is a compelling field of research that focuses on facilitating efficient modifications to the behavior of models, particularly **foundation models**. The aim is to implement these changes within a specified scope of interest without negatively affecting the model's performance across a broader range of inputs.

## Keywords 
Model Editing has strong connections with following topics.
- Updating and fixing bugs for large language models
- Language models as knowledge base, locating knowledge in large language models
- Lifelong learning, unlearning and etc.
- Security and privacy for large language models

## Papers
This is a collection of research and review papers of Model Editing. Any suggestions and pull requests are welcome for better sharing of latest research progress.

### Suvery and Analysis

**Editing Large Language Models: Problems, Methods, and Opportunities**. [[paper](https://arxiv.org/abs/2305.13172)] 
<div align=center><img src="./img/overview.jpg" width="100%" height="80%" /></div>

### Preserve Parameters

#### Memory-based

- Eric Mitchell, Charles Lin, Antoine Bosselut, Christopher D. Manning, Chelsea Finn.<br />
**Memory-Based Model Editing at Scale**. (ICML 2022) [[paper](https://arxiv.org/abs/2206.06520)] [[code](https://github.com/eric-mitchell/serac)] [[demo](https://sites.google.com/view/serac-editing)]

- Shikhar Murty, Christopher D. Manning, Scott M. Lundberg, Marco Túlio Ribeiro.<br />
  **Fixing Model Bugs with Natural Language Patches**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2211.03318)] [[code](https://github.com/MurtyShikhar/LanguagePatching)]
- Aman Madaan, Niket Tandon, Peter Clark, Yiming Yang.<br />
  **MemPrompt: Memory-assisted Prompt Editing with User Feedback**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2201.06009)] [[code](https://github.com/madaan/memprompt)] [[page](https://memprompt.com/)] [[video](https://www.youtube.com/watch?v=Ld7R02bOiNQ&t=1s)]
- Daliang Li, Ankit Singh Rawat, Manzil Zaheer, Xin Wang, Michal Lukasik, Andreas Veit, Felix Yu, Sanjiv Kumar.<br />
  **Large Language Models with Controllable Working Memory**. [[paper](https://arxiv.org/abs/2211.05110)]
- Qingxiu Dong, Damai Dai, Yifan Song, Jingjing Xu, Zhifang Sui, Lei Li.<br />
  **Calibrating Factual Knowledge in Pretrained Language Models**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2210.03329)] [[code](https://github.com/dqxiu/CaliNet)]
- Zeyu Huang, Yikang Shen, Xiaofeng Zhang, Jie Zhou, Wenge Rong, Zhang Xiong.<br />
  **Transformer-Patcher: One Mistake worth One Neuron**. (ICLR 2023) [[paper](https://arxiv.org/abs/2301.09785)] [[code](https://github.com/ZeroYuHuang/Transformer-Patcher)]
- Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim, Marzyeh Ghassemi.<br />
  **Aging with GRACE: Lifelong Model Editing with Discrete Key-Value Adaptors**. [[paper](https://arxiv.org/abs/2211.11031)] [[code](https://github.com/thartvigsen/grace)]

#### Change LM's representation space

- Evan Hernandez, Belinda Z. Li, Jacob Andreas.<br />
  **Measuring and Manipulating Knowledge Representations in Language Models**.[[paper](http://arxiv.org/abs/2304.00740)] [[code](https://github.com/evandez/REMEDI)]

#### Memory extension

- Damai Dai, Wenbin Jiang, Qingxiu Dong, Yajuan Lyu, Qiaoqiao She, Zhifang Sui.<br />
  **Neural Knowledge Bank for Pretrained Transformers**.[[paper](http://arxiv.org/abs/2208.00399)]


#### In Context Edit
- Ce Zheng, Lei Li, Qingxiu Dong, Yuxuan Fan, Zhiyong Wu, Jingjing Xu, Baobao Chang.<br />
**Can We Edit Factual Knowledge by In-Context Learning?**.[[paper](https://arxiv.org/abs/2305.12740)]
- Yasumasa Onoe, Michael J.Q. Zhang, Shankar Padmanabhan, Greg Durrett, Eunsol Choi.<br />
**Can LMs Learn New Entities from Descriptions? Challenges in Propagating Injected Knowledge** .[[paper](https://arxiv.org/abs/2305.01651)]

### Modify Parameters

#### Meta-learning

- Nicola De Cao, Wilker Aziz, Ivan Titov.<br />
**Editing Factual Knowledge in Language Models**. (EMNLP 2021) [[paper](https://arxiv.org/abs/2104.08164)] [[code](https://github.com/nicola-decao/KnowledgeEditor)]

- Eric Mitchell, Charles Lin, Antoine Bosselut, Chelsea Finn, Christopher D. Manning.<br />
**Fast Model Editing at Scale**. (ICLR 2022) [[paper](https://arxiv.org/abs/2110.11309)] [[code](https://github.com/eric-mitchell/mend)] [[page](https://sites.google.com/view/mend-editing)]

#### Locate and edit

- Anton Sinitsin, Vsevolod Plokhotnyuk, Dmitry V. Pyrkin, Sergei Popov, Artem Babenko.<br />
**Editable Neural Networks**. (ICLR 2020) [[paper](https://arxiv.org/abs/2004.00345)] [[code](https://github.com/xtinkt/editable)]

- Shibani Santurkar, Dimitris Tsipras, Mahalaxmi Elango, David Bau, Antonio Torralba, Aleksander Madry.<br />
**Editing a classifier by rewriting its prediction rules**. (NeurIPS 2021) [[paper](https://proceedings.neurips.cc/paper/2021/hash/c46489a2d5a9a9ecfc53b17610926ddd-Abstract.html)] [[code](https://github.com/MadryLab/EditingClassifiers)]

- Kyungjae Lee, Wookje Han, Seung-won Hwang, Hwaran Lee, Joonsuk Park, Sang-Woo Lee.<br />
**Plug-and-Play Adaptation for Continuously-updated QA**. (ACL 2022) [[paper](https://arxiv.org/abs/2204.12785)] [[code](https://github.com/wookjeHan/Plug-and-Play-Adaptation-for-Continuously-updated-QA)]

- Yang Xu, Yutai Hou, Wanxiang Che.<br />
**Language Anisotropic Cross-Lingual Model Editing**. [[paper](https://arxiv.org/abs/2205.12677)] 

- Ryutaro Tanno, Melanie F. Pradier, Aditya Nori, Yingzhen Li.<br />
**Repairing Neural Networks by Leaving the Right Past Behind**. [[paper](https://arxiv.org/abs/2207.04806)]

- Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov.<br />
**Locating and Editing Factual Associations in GPT**. (NeurIPS 2022) [[paper](https://arxiv.org/abs/2202.05262)] [[code](https://github.com/kmeng01/rome)] [[page](https://rome.baulab.info/)] [[video](https://www.youtube.com/watch?v=_NMQyOu2HTo&t=0)]

- Kevin Meng, Arnab Sen Sharma, Alex Andonian, Yonatan Belinkov, David Bau.<br />
**Mass-Editing Memory in a Transformer**. [[paper](https://arxiv.org/abs/2210.07229)] [[code](https://github.com/kmeng01/memit)] [[page](https://memit.baulab.info/)] [[demo](https://memit.baulab.us/#/)]

- Peter Hase, Mona Diab, Asli Celikyilmaz, Xian Li, Zornitsa Kozareva, Veselin Stoyanov, Mohit Bansal, Srinivasan Iyer.<br />
  **Do Language Models Have Beliefs? Methods for Detecting, Updating, and Visualizing Model Beliefs**. [[paper](https://arxiv.org/pdf/2111.13654.pdf)] [[code](https://github.com/peterbhase/SLAG-Belief-Updating)]

- Peter Hase, Mohit Bansal, Been Kim, Asma Ghandeharioun.<br />
  **Does Localization Inform Editing? Surprising Differences in Causality-Based Localization vs. Knowledge Editing in Language Models.** [[paper](https://arxiv.org/pdf/2301.04213.pdf)] [[code](https://github.com/google/belief-localization)] 

- Damai Dai , Li Dong, Yaru Hao, Zhifang Sui, Baobao Chang, Furu Wei.<br />**Knowledge Neurons in Pretrained Transformers**.(ACL 2022)[[paper](http://arxiv.org/abs/2104.08696)] [[code](https://github.com/Hunter-DDM/knowledge-neurons)] [[code by EleutherAI](https://github.com/EleutherAI/knowledge-neurons)]


### More Related Papers

- Robert L. Logan IV, Alexandre Passos, Sameer Singh, Ming-Wei Chang.<br />
**FRUIT: Faithfully Reflecting Updated Information in Text**. (NAACL 2022) [[paper]()] [[code]()]

- Oyvind Tafjord, Bhavana Dalvi Mishra, Peter Clark.<br />
**Entailer: Answering Questions with Faithful and Truthful Chains of Reasoning**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2210.12217)] [[code](https://github.com/allenai/entailment_bank)] [[video](https://www.youtube.com/watch?v=GYTJ_Pxva7Q)]

- Ekin Akyürek, Tolga Bolukbasi, Frederick Liu, Binbin Xiong, Ian Tenney, Jacob Andreas, Kelvin Guu.<br />
**Towards Tracing Factual Knowledge in Language Models Back to the Training Data**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2204.12785)]

- Chenglei Si, Zhe Gan, Zhengyuan Yang, Shuohang Wang, Jianfeng Wang, Jordan Boyd-Graber, Lijuan Wang.<br />
**Prompting GPT-3 To Be Reliable**. [[paper](https://arxiv.org/abs/2210.09150)]

- Gabriel Ilharco, Mitchell Wortsman, Samir Yitzhak Gadre, Shuran Song, Hannaneh Hajishirzi, Simon Kornblith, Ali Farhadi, Ludwig Schmidt.<br />
  **Patching open-vocabulary models by interpolating weights**. (NeurIPS 2022) [[paper](https://arxiv.org/abs/2208.05592)] [[code](https://github.com/mlfoundations/patching)]

- Xin Cheng, Yankai Lin, Xiuying Chen, Dongyan Zhao, Rui Yan.<br />**Decouple knowledge from paramters for plug-and-play language modeling**. (ACL2023 Findings)[[paper](http://arxiv.org/abs/2305.11564)] [[code](https://github.com/Hannibal046/PlugLM)]

## Contribution
### Contributors

<a href="https://github.com/zjunlp/
ModelEditingPapers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zjunlp/ModelEditingPapers" />
</a>
### Contributing to this paper list

-  There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.
