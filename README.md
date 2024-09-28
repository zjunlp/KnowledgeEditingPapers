# Knowledge Editing for LLMs Papers

[![Awesome](https://awesome.re/badge.svg)](https://github.com/zjunlp/ModelEditingPapers) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/zjunlp/ModelEditingPapers?color=green) 
![](https://img.shields.io/badge/PRs-Welcome-red)

Must-read papers on [knowledge editing](https://arxiv.org/abs/2305.13172) for large language models.

## 🔔 News
- **New Reports**

    |     *Report*        |    Topic    | PPT Resource |
    | :-----------------: | :---------: | :------------: |
    | IJCAI2024 tutorial| Knowledge Editing for Large Language Models| [Google Drive](https://drive.google.com/file/d/1sg3Dy3gQo2bwOoLwWMFh57NfHROf3Ahg/view?usp=sharing)   |
  | CCL2024 tutorial| 大语言模型知识机理、融合与编辑| [BaiduPan](https://pan.baidu.com/s/14IFludc3KROrCdvSYrOfAw?pwd=shja) & [Google Drive](https://drive.google.com/file/d/1Tp7pWAl1MqMvNQUplPS411WQmmAmodcB/view?usp=sharing)   |
    | COLING2024 tutorial| Knowledge Editing for Large Language Models| [Google Drive](https://drive.google.com/file/d/1vFzRYjnzkuZaNdjdIxQwWbEybCY7YqY9/view?usp=sharing)   |
    | 北京智源大会| 大语言模型知识机理与编辑问题| [BaiduPan](https://pan.baidu.com/s/1X9n2LAkYYXFnPgkV_2b57Q?pwd=du6w)   |
    | VALSE2024 tutorial| Knowledge Mechanism and Editing for Large Language Models| [Google Drive](https://drive.google.com/file/d/19T-InKopH-VHKAtphy9M6H366dXnenQX/view?usp=sharing)   |
    | AAAI2024 tutorial | Knowledge Editing for Large Language Models    | [Google Drive](https://drive.google.com/file/d/1fkTbVeRJSWmU7fBDeNf1OhHEkLSofQde/view?usp=sharing)   |
<!-- - **2024-02-20 The AAAI2024 tutorial "*Knowledge Editing for Large Language Models*" has been canceled since speakers cannot present in person, we make this ppt[[Github](https://github.com/zjunlp/KnowledgeEditingPapers/blob/main/AAAI2024%40Tutorial_Knowledge%20Editing%20for%20LLMs.pdf)] [[Google Drive](https://drive.google.com/file/d/1fkTbVeRJSWmU7fBDeNf1OhHEkLSofQde/view?usp=sharing)] [[Baidu Pan](https://pan.baidu.com/s/1oJYgaMnxWIBE4kIcJuMSKg?pwd=p9j5)] available to the community**. -->
- **2024-09-26 Our paper: "[WISE: Rethinking the Knowledge Memory for Lifelong Model Editing of Large Language Models](https://arxiv.org/abs/2405.14768)" and "[Knowledge Circuits in Pretrained Transformers](https://arxiv.org/abs/2405.17969)" have been accepted by NeurIPS 2024. Our papers: "[Knowledge Mechanisms in Large Language Models: A Survey and Perspective](https://arxiv.org/abs/2407.15017)" and "[Editing Conceptual Knowledge for Large Language Models](https://arxiv.org/abs/2403.06259)" have been accepted by EMNLP 2024 Findings.**
- **2024-07-22 We release a new paper: "[Knowledge Mechanisms in Large Language Models: A Survey and Perspective](https://arxiv.org/abs/2407.15017)", which reviews how knowledge is acquired, utilized, and evolves in large language models.**
- **2024-05-16 Our paper "[Detoxifying Large Language Models via Knowledge Editing](https://arxiv.org/abs/2403.14472)" has been accepted by ACL 2024.**
- **2024-01-03  We release a new paper:"[A Comprehensive Study of Knowledge Editing for Large Language Models](https://arxiv.org/abs/2401.01286)" with a new benchmark [KnowEdit](https://huggingface.co/datasets/zjunlp/KnowEdit)! We are looking forward to any comments or discussions on this topic**
- **2024-12-09 Our paper "[Editing Language Model-based Knowledge Graph Embeddings?](https://arxiv.org/abs/2301.10405)" has been accepted by AAAI 2024.**
- **2023-11-18 We will provide a tutorial on *Knowledge Editing for Large Language Models* at COLING 2024.**
- **2023-10-25 We will provide a tutorial on *Knowledge Editing for Large Language Models* at AAAI 2024.**
- **2023-10-22 Our paper "[Can We Edit Multimodal Large Language Models?](https://arxiv.org/abs/2310.08475)" has been accepted by EMNLP 2023.**
- **2023-10-08 Our paper "[Editing Large Language Models: Problems, Methods, and Opportunities](https://arxiv.org/abs/2305.13172)" has been accepted by EMNLP 2023.**
- **2023-8-15 We release the paper "[EasyEdit: An Easy-to-use Knowledge Editing Framework for Large Language Models](https://arxiv.org/abs/2308.07269)."**
- **2023-07 We release [EasyEdit](https://github.com/zjunlp/EasyEdit), an easy-to-use knowledge editing framework for LLMs.**
- **2023-06 We will provide a tutorial on *[Editing Large Language Models](https://drive.google.com/file/d/1EW-cusC_llCM0wEshkIdYuYrvfBPCDRz/view?usp=sharing)* at AACL 2023.**
- **2023-05  We release a new analysis paper:"[Editing Large Language Models: Problems, Methods, and Opportunities](https://arxiv.org/abs/2305.13172)" based on this repository! We are looking forward to any comments or discussions on this topic :)**
- **2022-12 We create this repository to maintain a paper list on *Knowledge Editing*.**

---

## 🔍 Contents

- [🌟 Why Knowledge Editing?](#-why-knowledge-editing)
 - [Keywords](#keywords)
- [Comparisons of the different technologies](#comparisons-of-different-technologies)
- [📜 Papers](#-papers)
  - [Overview](#overview)
  - [Methods](#methods)
    - [Preserve Parameters](#preserve-parameters)
      - [Memory Based](#memory-based)
      - [Additional Parameters](#additional-parameters)
    - [Modify Parameters](#modify-parameters)
      - [Finetuning](#finetuning)
      - [Meta-learning](#meta-learning)
      - [Locate and edit](#locate-and-edit)
    - [More Related Papers](#more-related-papers)
  - [Analysis](#analysis)
- [🧰 Resources](#-resources)
    - [Benchmarks and Tasks](#benchmarks-and-tasks)
    - [Tools](#tools)
- [🎉 Contribution](#contribution)
  - [Contributors](#contributors)
  - [Contributing to this paper list](#contributing-to-this-paper-list)
  - [Acknowledgement](#acknowledgement)
- [🚩Citation ](#-citation)

---

## 🌟 Why Knowledge Editing?
Knowledge Editing is a compelling field of research that focuses on facilitating efficient modifications to the behavior of models, particularly **foundation models**. The aim is to implement these changes within a specified scope of interest without negatively affecting the model's performance across a broader range of inputs.

### Keywords 
Knowledge Editing has strong connections with following topics.
- Updating and fixing bugs for large language models
- Language models as knowledge base, locating knowledge in large language models
- Lifelong learning, unlearning and etc.
- Security and privacy for large language models

<div align=center><img src="./img/ke.png" width="100%" height="80%" /></div>

## Comparisons of different technologies

<div align=center><img src="./img/comparison.png" width="60%" height="48%" /></div>


## 📜 Resources
This is a collection of research and review papers of Knowledge Editing. Any suggestions and pull requests are welcome for better sharing of latest research progress.
### Tutorials

**Knowledge Editing for Large Language Models, AAAI 2024 Tutorial**  <br /> 
Ningyu Zhang, Jia-Chen Gu, Yunzhi Yao, Zhen Bi, Shumin Deng. [[Github](https://github.com/zjunlp/KnowledgeEditingPapers/blob/main/AAAI2024%40Tutorial_Knowledge%20Editing%20for%20LLMs.pdf)] [[Google Drive](https://drive.google.com/file/d/1fkTbVeRJSWmU7fBDeNf1OhHEkLSofQde/view?usp=sharing)] [[Baidu Pan](https://pan.baidu.com/s/1oJYgaMnxWIBE4kIcJuMSKg?pwd=p9j5)]

**Editing Large Language Models, AACL 2023 Tutorial**  <br /> 
Ningyu Zhang, Yunzhi Yao, Shumin Deng. [[Github](https://github.com/zjunlp/KnowledgeEditingPapers/blob/main/AACL2023%40Tutorial_Editing%20LLMs.pdf)] [[Google Drive](https://drive.google.com/file/d/1EW-cusC_llCM0wEshkIdYuYrvfBPCDRz/view?usp=sharing)] [[Baidu Pan](https://pan.baidu.com/s/1NupastGJUzcUIAjI64J1tw?pwd=i5an)]

### Surveys
**Knowledge Mechanisms in Large Language Models: A Survey and Perspective** (EMNLP 2024 Findings) <br />
Mengru Wang, Yunzhi Yao, Ziwen Xu, Shuofei Qiao, Shumin Deng, Peng Wang, Xiang Chen, Jia-Chen Gu, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen, Ningyu Zhang. [[paper](https://arxiv.org/abs/2407.15017)]

**A Comprehensive Study of Knowledge Editing for Large Language Models** <br /> 
Ningyu Zhang, Yunzhi Yao, Bozhong Tian, Peng Wang, Shumin Deng, Mengru Wang, Zekun Xi, Shengyu Mao, Jintian Zhang, Yuansheng Ni, Siyuan Cheng, Ziwen Xu, Xin Xu, Jia-Chen Gu, Yong Jiang, Pengjun Xie, Fei Huang, Lei Liang, Zhiqiang Zhang, Xiaowei Zhu, Jun Zhou, Huajun Chen.
[[paper](https://arxiv.org/abs/2401.01286)][[benchmark](https://huggingface.co/datasets/zjunlp/KnowEdit)][[code](https://github.com/zjunlp/EasyEdit)] 

**Editing Large Language Models: Problems, Methods, and Opportunities, EMNLP 2023 Main Conference Paper**  <br />
Yunzhi Yao, Peng Wang, Bozhong Tian, Siyuan Cheng, Zhoubo Li, Shumin Deng, Huajun Chen, Ningyu Zhang. [[paper](https://arxiv.org/abs/2305.13172)][[code](https://github.com/zjunlp/EasyEdit)] 

**Knowledge Editing for Large Language Models: A Survey** <br />
Song Wang, Yaochen Zhu, Haochen Liu, Zaiyi Zheng, Chen Chen, Jundong Li. [[paper](https://arxiv.org/abs/2310.16218)]

**A Survey on Knowledge Editing of Neural Networks** <br />
Vittorio Mazzia, Alessandro Pedrani, Andrea Caciolai, Kay Rottmann, Davide Bernardi. [[paper](https://arxiv.org/abs/2310.19704)]

**Knowledge Unlearning for LLMs: Tasks, Methods, and Challenges** <br />
Nianwen Si, Hao Zhang, Heyu Chang, Wenlin Zhang, Dan Qu, Weiqiang Zhang. [[paper](https://arxiv.org/abs/2311.15766)]
<div align=center><img src="./img/overview.jpg" width="100%" height="80%" /></div>

### Methods
#### Preserve Parameters

##### Memory-based

1. **Memory-Based Model Editing at Scale** (ICML 2022) <br />
    Eric Mitchell, Charles Lin, Antoine Bosselut, Christopher D. Manning, Chelsea Finn.
      [[paper](https://arxiv.org/abs/2206.06520)] [[code](https://github.com/eric-mitchell/serac)] [[demo](https://sites.google.com/view/serac-editing)]

2. **Fixing Model Bugs with Natural Language Patches**. (EMNLP 2022) <br />
   Shikhar Murty, Christopher D. Manning, Scott M. Lundberg, Marco Túlio Ribeiro.
   [[paper](https://arxiv.org/abs/2211.03318)] [[code](https://github.com/MurtyShikhar/LanguagePatching)]
3. **MemPrompt: Memory-assisted Prompt Editing with User Feedback**. (EMNLP 2022) <br />
  Aman Madaan, Niket Tandon, Peter Clark, Yiming Yang.
   [[paper](https://arxiv.org/abs/2201.06009)] [[code](https://github.com/madaan/memprompt)] [[page](https://memprompt.com/)] [[video](https://www.youtube.com/watch?v=Ld7R02bOiNQ&t=1s)]

4. **Large Language Models with Controllable Working Memory**. <br />
     Daliang Li, Ankit Singh Rawat, Manzil Zaheer, Xin Wang, Michal Lukasik, Andreas Veit, Felix Yu, Sanjiv Kumar.
    [[paper](https://arxiv.org/abs/2211.05110)]

5. **Can We Edit Factual Knowledge by In-Context Learning?** <br />
  Ce Zheng, Lei Li, Qingxiu Dong, Yuxuan Fan, Zhiyong Wu, Jingjing Xu, Baobao Chang.
  [[paper](https://arxiv.org/abs/2305.12740)]

6. **Can LMs Learn New Entities from Descriptions? Challenges in Propagating Injected Knowledge** <br />
  Yasumasa Onoe, Michael J.Q. Zhang, Shankar Padmanabhan, Greg Durrett, Eunsol Choi.
   [[paper](https://arxiv.org/abs/2305.01651)]

7. **MQUAKE: Assessing Knowledge Editing inLanguage Models via Multi-Hop Questions** <br>
  Zexuan Zhong, Zhengxuan Wu, Christopher D. Manning, Christopher Potts, Danqi Chen.<br />[[paper](https://arxiv.org/abs/2305.14795)] [[code](https://github.com/princeton-nlp/MQuAKE)]

8. **PokeMQA: Programmable knowledge editing for Multi-hop Question Answering** <br>
  Hengrui Gu, Kaixiong Zhou, Xiaotian Han, Ninghao Liu, Ruobing Wang, Xin Wang. <br /> [[paper](https://arxiv.org/abs/2312.15194)] [[code](https://github.com/Hengrui-Gu/PokeMQA)]

9. **Retrieval-augmented Multilingual Knowledge Editing** <br>
  Weixuan Wang, Barry Haddow, Alexandra Birch.
  [[paper](https://arxiv.org/abs/2312.13040)] [[code](https://github.com/Vicky-Wil/ReMaKE)]

10. **MEMORYLLM: Towards Self-Updatable Large Language Models** <br>
    Yu Wang, Xiusi Chen, Jingbo Shang, Julian McAuley. [[paper](https://arxiv.org/abs/2402.04624)]

11. **DeepEdit: Knowledge Editing as Decoding with Constraints** <br>
     Yiwei Wang,Muhao Chen,Nanyun Peng, Kai-Wei Chang. [[paper](https://arxiv.org/abs/2401.10471)]

12. **Stable Knowledge Editing in Large Language Models**. <br />
     Zihao Wei,Liang Pang,Hanxing Ding,Jingcheng Deng,Huawei Shen,Xueqi Cheng. [[paper](https://arxiv.org/abs/2402.13093)]

13. **Knowledge Editing on Black-box Large Language Models**. <br />
     Xiaoshuai Song, Zhengyang Wang, Keqing He, Guanting Dong, Jinxu Zhao, Weiran Xu. [[paper](https://arxiv.org/abs/2402.08631)]

14. **Learning to Edit: Aligning LLMs with Knowledge Editing**. <br />
     Yuxin Jiang, Yufei Wang, Chuhan Wu, Wanjun Zhong, Xingshan Zeng, Jiahui Gao, Liangyou Li, Xin Jiang, Lifeng Shang, Ruiming Tang, Qun Liu, Wei Wang. [[paper](https://arxiv.org/abs/2402.11905)]

15. **Robust and Scalable Model Editing for Large Language Models**. <br />
     Yingfa Chen, Zhengyan Zhang, Xu Han, Chaojun Xiao, Zhiyuan Liu, Chen Chen, Kuai Li, Tao Yang, Maosong Sun. [[paper](https://arxiv.org/abs/2403.17431)]

16. **Retrieval-Enhanced Knowledge Editing for Multi-Hop Question Answering in Language Models**. <br />
     Yucheng Shi, Qiaoyu Tan, Xuansheng Wu, Shaochen Zhong, Kaixiong Zhou, Ninghao Liu. [[paper](https://arxiv.org/abs/2403.19631)]

17. **In-Context Editing: Learning Knowledge from Self-Induced Distributions**. <br />
     Siyuan Qi, Bangcheng Yang, Kailin Jiang, Xiaobo Wang, Jiaqi Li, Yifan Zhong, Yaodong Yang, Zilong Zheng. [[paper](https://arxiv.org/abs/2406.11194)]

##### Additional Parameters
1. **Calibrating Factual Knowledge in Pretrained Language Models**. (EMNLP 2022) <br />
Qingxiu Dong, Damai Dai, Yifan Song, Jingjing Xu, Zhifang Sui, Lei Li.
   [[paper](https://arxiv.org/abs/2210.03329)] [[code](https://github.com/dqxiu/CaliNet)]

2. **Transformer-Patcher: One Mistake worth One Neuron**. (ICLR 2023) <br />
   Zeyu Huang, Yikang Shen, Xiaofeng Zhang, Jie Zhou, Wenge Rong, Zhang Xiong.
   [[paper](https://arxiv.org/abs/2301.09785)] [[code](https://github.com/ZeroYuHuang/Transformer-Patcher)]
3. **Aging with GRACE: Lifelong Model Editing with Discrete Key-Value Adaptors**. (NeurIPS 2023) <br />
   Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim, Marzyeh Ghassemi.
   [[paper](https://arxiv.org/abs/2211.11031)] [[code](https://github.com/thartvigsen/grace)]
4. **Neural Knowledge Bank for Pretrained Transformers** <br />
Damai Dai, Wenbin Jiang, Qingxiu Dong, Yajuan Lyu, Qiaoqiao She, Zhifang Sui. [[paper](http://arxiv.org/abs/2208.00399)]

6. **Rank-One Editing of Encoder-Decoder Models** <br />
Vikas Raunak, Arul Menezes. [[paper](https://arxiv.org/abs/2211.13317)]

8. **MELO: Enhancing Model Editing with Neuron-Indexed Dynamic LoRA.** (AAAI 2024) <br />
Lang Yu, Qin Chen, Jie Zhou, Liang He.  [[paper](https://arxiv.org/abs/2312.11795)] [[code](https://github.com/BruthYU/MELO)]

10. **MPN: Leveraging Multilingual Patch Neuron for Cross-lingual Model Editing**  <br />
Nianwen Si, Hao Zhang, Weiqiang Zhang.  [[paper](https://arxiv.org/abs/2401.03190)]

11. **SWEA: Changing Factual Knowledge in Large Language Models via Subject Word Embedding Altering**  <br />
Xiaopeng Li, Shasha Li, Bin Ji, Shezheng Song.  [[paper](https://arxiv.org/abs/2401.17809)]

12. **MEMoE: Enhancing Model Editing with Mixture of Experts Adaptors**  <br />
Renzhi Wang, Piji Li.  [[paper](https://arxiv.org/abs/2405.19086)]

13. **WISE: Rethinking the Knowledge Memory for Lifelong Model Editing of Large Language Models**. (NeurIPS 2024) <br />
Peng Wang, Zexi Li, Ningyu Zhang, Ziwen Xu, Yunzhi Yao, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen. [[paper](https://arxiv.org/abs/2405.14768)]

14. **MEMLA: Enhancing Multilingual Knowledge Editing with Neuron-Masked Low-Rank Adaptation**. <br />
Jiakuan Xie, Pengfei Cao, Yuheng Chen, Yubo Chen, Kang Liu, Jun Zhao. [[paper](https://arxiv.org/abs/2405.14768)]
##### Change LM's representation space

1. **Inspecting and Editing Knowledge Representations in Language Models** <br />
    Evan Hernandez, Belinda Z. Li, Jacob Andreas.
    [[paper](http://arxiv.org/abs/2304.00740)] [[code](https://github.com/evandez/REMEDI)]


#### Modify Parameters
##### Finetuning
1. **Plug-and-Play Adaptation for Continuously-updated QA**. (ACL 2022 Findings) <br />
Kyungjae Lee, Wookje Han, Seung-won Hwang, Hwaran Lee, Joonsuk Park, Sang-Woo Lee.
 [[paper](https://arxiv.org/abs/2204.12785)] [[code](https://github.com/wookjeHan/Plug-and-Play-Adaptation-for-Continuously-updated-QA)]

2. **Modifying Memories in Transformer Models**. <br />
Chen Zhu, Ankit Singh Rawat, Manzil Zaheer, Srinadh Bhojanapalli, Daliang Li, Felix Yu, Sanjiv Kumar.
 [[paper](https://arxiv.org/abs/2012.00363)]

3. **Forgetting before Learning: Utilizing Parametric Arithmetic for Knowledge
Updating in Large Language Models** <br /> 
Shiwen Ni, Dingwei Chen, Chengming Li, Xiping Hu, Ruifeng Xu and Min Yang. [[paper](https://arxiv.org/pdf/2311.08011.pdf)]

3. **LLM Surgery: Efficient Knowledge Unlearning and Editing in Large Language Models** <br /> 
Akshaj Kumar Veldanda, Shi-Xiong Zhang, Anirban Das, Supriyo Chakraborty, Stephen Rawls, Sambit Sahu, Milind Naphade. [[paper](https://arxiv.org/abs/2409.13054)]

##### Meta-learning

1. **Editing Factual Knowledge in Language Models**. (EMNLP 2021) <br />
Nicola De Cao, Wilker Aziz, Ivan Titov.
 [[paper](https://arxiv.org/abs/2104.08164)] [[code](https://github.com/nicola-decao/KnowledgeEditor)]

2. **Fast Model Editing at Scale**. (ICLR 2022) <br />
Eric Mitchell, Charles Lin, Antoine Bosselut, Chelsea Finn, Christopher D. Manning.
 [[paper](https://arxiv.org/abs/2110.11309)] [[code](https://github.com/eric-mitchell/mend)] [[page](https://sites.google.com/view/mend-editing)]
3. **Editable Neural Networks**. (ICLR 2020) <br />
Anton Sinitsin, Vsevolod Plokhotnyuk, Dmitry V. Pyrkin, Sergei Popov, Artem Babenko. [[paper](https://arxiv.org/abs/2004.00345)] [[code](https://github.com/xtinkt/editable)]

4. **Editing Language Model-based Knowledge Graph Embeddings** (AAAI 2024)  <br />
Siyuan Cheng, Ningyu Zhang, Bozhong Tian, Xi Chen, Qingbing Liu, Huajun Chen.
[[paper](https://arxiv.org/abs/2301.10405)] [[code](https://github.com/zjunlp/PromptKG/tree/main/deltaKG)]

5. **Massive Editing for Large Language Model via Meta Learning.** (ICLR 2024) <br />
Chenmien Tan1, Ge Zhang, Jie Fu. [[paper](https://arxiv.org/pdf/2311.04661.pdf)] [[code](https://github.com/ChenmienTan/malmen)]

##### Locate and edit
1. **Editing a classifier by rewriting its prediction rules**. (NeurIPS 2021) <br />
Shibani Santurkar, Dimitris Tsipras, Mahalaxmi Elango, David Bau, Antonio Torralba, Aleksander Madry.
 [[paper](https://proceedings.neurips.cc/paper/2021/hash/c46489a2d5a9a9ecfc53b17610926ddd-Abstract.html)] [[code](https://github.com/MadryLab/EditingClassifiers)]

2. **Language Anisotropic Cross-Lingual Model Editing**. <br />
Yang Xu, Yutai Hou, Wanxiang Che.
 [[paper](https://arxiv.org/abs/2205.12677)] 

3. **Repairing Neural Networks by Leaving the Right Past Behind**. <br />
Ryutaro Tanno, Melanie F. Pradier, Aditya Nori, Yingzhen Li.
 [[paper](https://arxiv.org/abs/2207.04806)]

4. **Locating and Editing Factual Associations in GPT**. (NeurIPS 2022) <br />
Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov.
[[paper](https://arxiv.org/abs/2202.05262)] [[code](https://github.com/kmeng01/rome)] [[page](https://rome.baulab.info/)] [[video](https://www.youtube.com/watch?v=_NMQyOu2HTo&t=0)]

5. **Mass-Editing Memory in a Transformer**. (ICLR 2023) <br />
Kevin Meng, Arnab Sen Sharma, Alex Andonian, Yonatan Belinkov, David Bau.
 [[paper](https://arxiv.org/abs/2210.07229)] [[code](https://github.com/kmeng01/memit)] [[page](https://memit.baulab.info/)] [[demo](https://memit.baulab.us/#/)]

6. **Editing models with task arithmetic**. (ICLR 2023) <br />
Gabriel Ilharco, Marco Tulio Ribeiro, Mitchell Wortsman, Ludwig Schmidt, Hannaneh Hajishirzi, Ali Farhadi.
[[paper](https://openreview.net/pdf?id=6t0Kwf8-jrj)]

7. **Editing Common Sense in Transformers**. (EMNLP 2023) <br />
Anshita Gupta, Debanjan Mondal, Akshay Krishna Sheshadri, Wenlong Zhao, Xiang Lorraine Li, Sarah Wiegreffe, Niket Tandon.
[[paper](https://arxiv.org/abs/2305.14956)]

8. **Do Language Models Have Beliefs? Methods for Detecting, Updating, and Visualizing Model Beliefs**. (EACL 2023) <br />
Peter Hase, Mona Diab, Asli Celikyilmaz, Xian Li, Zornitsa Kozareva, Veselin Stoyanov, Mohit Bansal, Srinivasan Iyer.
[[paper](https://arxiv.org/pdf/2111.13654.pdf)] [[code](https://github.com/peterbhase/SLAG-Belief-Updating)]

9. **Detecting Edit Failures In Large Language Models: An Improved Specificity Benchmark**. (ACL 2023 Findings)<br />
Jason Hoelscher-Obermaier, Julia Persson, Esben Kran, Ioannis Konstas, Fazl Barez.
[[paper](https://arxiv.org/abs/2305.17553)]

10. **Knowledge Neurons in Pretrained Transformers**.(ACL 2022) <br />
Damai Dai , Li Dong, Yaru Hao, Zhifang Sui, Baobao Chang, Furu Wei.[[paper](http://arxiv.org/abs/2104.08696)] [[code](https://github.com/Hunter-DDM/knowledge-neurons)] [[code by EleutherAI](https://github.com/EleutherAI/knowledge-neurons)]

11. **LEACE: Perfect linear concept erasure in closed form** .<br />
Nora Belrose, David Schneider-Joseph, Shauli Ravfogel, Ryan Cotterell, Edward Raff, Stella Biderman.
[[paper](https://arxiv.org/abs/2306.03819)]

12. **Transformer Feed-Forward Layers Are Key-Value Memories**. (EMNLP 2021) <br />
Mor Geva, Roei Schuster, Jonathan Berant, Omer Levy.  [[paper](https://arxiv.org/abs/2012.14913)]

13. **Transformer Feed-Forward Layers Build Predictions by Promoting Concepts in the Vocabulary Space**.(EMNLP 2022) <br />
Mor Geva, Avi Caciularu, Kevin Ro Wang, Yoav Goldberg. [[paper](https://arxiv.org/abs/2203.14680)]

14. **PMET: Precise Model Editing in a Transformer.** (AAAI 2024) <br />
Xiaopeng Li, Shasha Li, Shezheng Song, Jing Yang, Jun Ma, Jie Yu. [[paper](https://arxiv.org/abs/2308.08742)] [[code](https://github.com/xpq-tech/PMET.git)]

15. **Unlearning Bias in Language Models by Partitioning Gradients.** (ACL 2023 Findings) <br />
Charles Yu, Sullam Jeoung, Anish Kasi, Pengfei Yu, Heng Ji. [[paper](https://aclanthology.org/2023.findings-acl.375.pdf)] [[code](https://github.com/CharlesYu2000/PCGU-UnlearningBias)]

16. **DEPN: Detecting and Editing Privacy Neurons in Pretrained Language Models** (EMNLP 2023) <br />
Xinwei Wu, Junzhuo Li, Minghui Xu, Weilong Dong, Shuangzhi Wu, Chao Bian, Deyi Xiong. [[paper](https://arxiv.org/pdf/2310.20138.pdf)]

17. **Untying the Reversal Curse via Bidirectional Language Model Editing** <br />
Jun-Yu Ma, Jia-Chen Gu, Zhen-Hua Ling, Quan Liu, Cong Liu. [[paper](https://arxiv.org/pdf/2310.10322.pdf)]

18. **Trace and Edit Relation Associations in GPT** <br />
Jiahang Li,Taoyu Chen,Yuanli Wang. [[paper](https://arxiv.org/abs/2401.02976)]

19. **Consecutive Model Editing with Batch alongside HooK Layers** <br />
Shuaiyi Li,Yang Deng,Deng Cai,Hongyuan Lu,Liang Chen,Wai Lam. [[paper](https://arxiv.org/abs/2403.05330)]

20. **A Unified Framework for Model Editing** <br />
Akshat Gupta,Dev Sajnani,Gopala Anumanchipalli. [[paper](https://arxiv.org/abs/2403.14236)]

21. **Detoxifying Large Language Models via Knowledge Editing** <br />
Mengru Wang, Ningyu Zhang, Ziwen Xu, Zekun Xi, Shumin Deng, Yunzhi Yao, Qishen Zhang, Linyi Yang, Jindong Wang, Huajun Chen. [[paper](https://arxiv.org/abs/2403.14472)]

22. **Locating and Editing Factual Associations in Mamba** <br />
Arnab Sen Sharma,David Atkinson,David Bau. [[paper](https://arxiv.org/abs/2404.03646)]

23. **Large Language Model Bias Mitigation from the Perspective of Knowledge Editing** <br />
Ruizhe Chen, Yichen Li, Zikai Xiao, Zuozhu Liu. [[paper](https://arxiv.org/abs/2405.09341)]

24. **WilKE: Wise-Layer Knowledge Editor for Lifelong Knowledge Editing**  <br />
Chenhui Hu, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao.  [[paper](https://arxiv.org/abs/2402.10987)]

25. **ReFACT: Updating Text-to-Image Models by Editing the Text Encoder**  <br />
Dana Arad, Hadas Orgad, Yonatan Belinkov.  [[paper](https://arxiv.org/pdf/2303.08084)]

26. **Editing Implicit Assumptions in Text-to-Image Diffusion Models**  <br />
Hadas Orgad, Bahjat Kawar, Yonatan Belinkov.  [[paper](https://arxiv.org/pdf/2303.08084)]
#### More Related Papers

1. **FRUIT: Faithfully Reflecting Updated Information in Text**. (NAACL 2022) <br />
Robert L. Logan IV, Alexandre Passos, Sameer Singh, Ming-Wei Chang.
 [[paper](https://arxiv.org/pdf/2112.08634)] [[code](https://github.com/google-research/language/tree/master/language/fruit)]

2. **Entailer: Answering Questions with Faithful and Truthful Chains of Reasoning**. (EMNLP 2022) <br />
Oyvind Tafjord, Bhavana Dalvi Mishra, Peter Clark.
 [[paper](https://arxiv.org/abs/2210.12217)] [[code](https://github.com/allenai/entailment_bank)] [[video](https://www.youtube.com/watch?v=GYTJ_Pxva7Q)]

3. **Towards Tracing Factual Knowledge in Language Models Back to the Training Data**. <br />
Ekin Akyürek, Tolga Bolukbasi, Frederick Liu, Binbin Xiong, Ian Tenney, Jacob Andreas, Kelvin Guu.
 (EMNLP 2022) [[paper](https://arxiv.org/abs/2204.12785)]

4. **Prompting GPT-3 To Be Reliable**. <br />
Chenglei Si, Zhe Gan, Zhengyuan Yang, Shuohang Wang, Jianfeng Wang, Jordan Boyd-Graber, Lijuan Wang.
 [[paper](https://arxiv.org/abs/2210.09150)]

5.  **Patching open-vocabulary models by interpolating weights**. (NeurIPS 2022) <br />
Gabriel Ilharco, Mitchell Wortsman, Samir Yitzhak Gadre, Shuran Song, Hannaneh Hajishirzi, Simon Kornblith, Ali Farhadi, Ludwig Schmidt.
    [[paper](https://arxiv.org/abs/2208.05592)] [[code](https://github.com/mlfoundations/patching)]

6. **Decouple knowledge from paramters for plug-and-play language modeling**  (ACL2023 Findings) <br />
Xin Cheng, Yankai Lin, Xiuying Chen, Dongyan Zhao, Rui Yan.[[paper](http://arxiv.org/abs/2305.11564)] [[code](https://github.com/Hannibal046/PlugLM)]

7. **Backpack Language Models** <br />
John Hewitt, John Thickstun, Christopher D. Manning, Percy Liang. [[paper](https://arxiv.org/pdf/2305.16765.pdf)]

8. **Learning to Model Editing Processes**. (EMNLP 2022) <br />
Machel Reid, Graham Neubig. [[paper](https://aclanthology.org/2022.findings-emnlp.280.pdf)]

9. **Trends in Integration of Knowledge and Large Language Models: A Survey and Taxonomy of Methods, Benchmarks, and Applications**. <br />
Zhangyin Feng, Weitao Ma, Weijiang Yu, Lei Huang, Haotian Wang, Qianglong Chen, Weihua Peng, Xiaocheng Feng, Bing Qin, Ting liu. [[paper](https://arxiv.org/pdf/2311.05876.pdf)]

10. **DUnE: Dataset for Unified Editing**. (EMNLP 2023) <br />
Afra Feyza Akyürek, Eric Pan, Garry Kuwanto, Derry Wijaya. [[paper](https://arxiv.org/abs/2311.16087)]

11. **See the Unseen: Better Context-Consistent Knowledge-Editing by Noises**. <br />
Youcheng Huang, Wenqiang Lei, Zheng Zhang, Jiancheng Lv, Shuicheng Yan. [[paper](https://arxiv.org/abs/2401.07544)]

12. **Sowing the Wind, Reaping the Whirlwind: The Impact of Editing Language Models**. <br />
Rima Hazra, Sayan Layek, Somnath Banerjee, Soujanya Poria. [[paper](https://arxiv.org/pdf/2401.10647.pdf)]

13. **Model Editing with Canonical Examples**. <br />
John Hewitt, Sarah Chen, Lanruo Lora Xie. [[paper](https://arxiv.org/pdf/2402.06155.pdf)]

14. **EVEDIT: Event-based Knowledge Editing with Deductive Editing Boundaries**. <br />
Jiateng Liu,Pengfei Yu,Yuji Zhang,Sha Li,Zixuan Zhang,Heng Ji. [[paper](https://arxiv.org/abs/2402.11324)]

15. **Investigating Multi-Hop Factual Shortcuts in Knowledge Editing of Large  Language Models**. <br />
Tianjie Ju,Yijin Chen,Xinwei Yuan,Zhuosheng Zhang,Wei Du,Yubin Zheng,Gongshen Liu. [[paper](https://arxiv.org/abs/2402.11900)]

16. **Knowledge Graph Enhanced Large Language Model Editing**. <br />
Mengqi Zhang,Xiaotian Ye,Qiang Liu,Pengjie Ren,Shu Wu,Zhumin Chen. [[paper](https://arxiv.org/abs/2402.13593)]

17. **Editing Factual Knowledge and Explanatory Ability of Medical Large Language Models**. <br />
Derong Xu, Ziheng Zhang, Zhihong Zhu, Zhenxi Lin. [[paper](https://arxiv.org/abs/2402.18099)]

18. **KEBench: A Benchmark on Knowledge Editing for Large Vision-Language Models**. <br />
 Han Huang, Haitian Zhong, Qiang Liu, Shu Wu, Liang Wang, Tieniu Tan. [[paper](https://arxiv.org/pdf/2403.07350.pdf)]

19. **COLLABEDIT: TOWARDS NON-DESTRUCTIVE COLLABORATIVE KNOWLEDGE EDITING**. <br />
 Jiamu Zheng, Jinghuai Zhang, Futing Wang, Tianyu Du, Tao Lin. [[paper](https://openreview.net/pdf?id=PoVpff2Udw)]

20. **TAXI: Evaluating Categorical Knowledge Editing for Language Models**. <br />
 Derek Powell, Walter Gerych, Thomas Hartvigsen. [[paper](https://arxiv.org/pdf/2404.15004)]

21. **Large Scale Knowledge Washing**. <br />
 Yu Wang, Ruihan Wu, Zexue He, Xiusi Chen, Julian McAuley. [[paper](https://arxiv.org/abs/2405.16720)]

22. **Defending Large Language Models Against Jailbreak Attacks via Layer-specific Editing**. <br />
 Wei Zhao, Zhe Li, Yige Li, Ye Zhang, Jun Sun. [[paper](https://arxiv.org/abs/2406.02882)]

23. **Outdated Issue Aware Decoding for Factual Knowledge Editing**. <br />
 Zengkui Sun, Yijin Liu, Jiaan Wang, Fandong Meng, Jinan Xu, Yufeng Chen, Jie Zhou. [[paper](https://arxiv.org/abs/2405.18166)]

24. **Adaptive Token Biaser: Knowledge Editing via Biasing Key Entities**. <br />
 Baolong Bi, Shenghua Liu, Yiwei Wang, Lingrui Mei, Hongcheng Gao, Yilong Xu, Xueqi Cheng. [[paper](https://arxiv.org/abs/2406.12468)]

25. **Language Modeling with Editable External Knowledge**. <br />
 Belinda Z. Li, Emmy Liu, Alexis Ross, Abbas Zeitoun, Graham Neubig, Jacob Andreas. [[paper](https://arxiv.org/abs/2406.11830)]

26. **Safety Arithmetic: A Framework for Test-time Safety Alignment of Language Models by Steering Parameters and Activations**. <br />
 Rima Hazra, Sayan Layek, Somnath Banerjee, Soujanya Poria. [[paper](https://arxiv.org/abs/2406.11801)]

27. **Enhancing Data Privacy in Large Language Models through Private Association Editing**. <br />
 Kunquan Deng, Zeyu Huang, Chen Li, Chenghua Lin, Min Gao, Wenge Rong. [[paper](https://arxiv.org/abs/2407.00488)]

28. **PFME: A Modular Approach for Fine-grained Hallucination Detection and Editing of Large Language Models**. <br />
 Davide Venditti, Elena Sofia Ruzzetti, Giancarlo A. Xompero, Cristina Giannone, Andrea Favalli, Raniero Romagnoli, Fabio Massimo Zanzotto. [[paper](https://arxiv.org/abs/2406.18221)]

29. **SafeInfer: Context Adaptive Decoding Time Safety Alignment for Large Language Models**. <br />
 Somnath Banerjee, Soham Tripathy, Sayan Layek, Shanu Kumar, Animesh Mukherjee, Rima Hazra. [[paper](https://arxiv.org/abs/2406.12274)]

30. **Editing Implicit Assumptions in Text-to-Image Diffusion Models**. (ICCV 2023) <br />
 Hadas Orgad, Bahjat Kawar, Yonatan Belinkov. [[paper](https://arxiv.org/abs/2303.08084)]

31. **ReFACT: Updating Text-to-Image Models by Editing the Text Encoder**.  (NAAC 2024) <br />
Dana Arad, Hadas Orgad, Yonatan Belinkov. [[paper](https://arxiv.org/abs/2306.00738)]

32. **MC-MKE: A Fine-Grained Multimodal Knowledge Editing Benchmark Emphasizing Modality Consistency**. <br />
Junzhe Zhang, Huixuan Zhang, Xunjian Yin, Baizhou Huang, Xu Zhang, Xinyu Hu, Xiaojun Wan. [[paper](https://arxiv.org/abs/2406.13219)]

33. **LLM-Based Multi-Hop Question Answering with Knowledge Graph Integration in Evolving Environments**. <br />
Ruirui Chen, Weifeng Jiang, Chengwei Qin, Ishaan Singh Rawal, Cheston Tan, Dongkyu Choi, Bo Xiong, Bo Ai. [[paper](https://arxiv.org/abs/2408.15903)]

### Analysis
1. **Does Localization Inform Editing? Surprising Differences in Causality-Based Localization vs. Knowledge Editing in Language Models.** <br />
    Peter Hase, Mohit Bansal, Been Kim, Asma Ghandeharioun. [[paper](https://arxiv.org/pdf/2301.04213.pdf)] [[code](https://github.com/google/belief-localization)] 
2. **Dissecting Recall of Factual Associations in Auto-Regressive Language Models** <br />
    Mor Geva, Jasmijn Bastings, Katja Filippova, Amir Globerson.  [[paper](https://arxiv.org/abs/2304.14767)]
3. **Evaluating the Ripple Effects of Knowledge Editing in Language Models** <br />
    Roi Cohen, Eden Biran, Ori Yoran, Amir Globerson, Mor Geva. [[paper](https://arxiv.org/abs/2307.12976)]
4. **Edit at your own risk: evaluating the robustness of edited models to distribution shifts.** <br />
    Davis Brown, Charles Godfrey, Cody Nizinski, Jonathan Tu, Henry Kvinge. [[paper](https://arxiv.org/abs/2303.00046)]
5. **Journey to the Center of the Knowledge Neurons: Discoveries of Language-Independent Knowledge Neurons and Degenerate Knowledge Neurons.** (AAAI 2024) <br />
    Yuheng Chen, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao. [[paper](https://arxiv.org/abs/2308.13198)]
6. **Linearity of Relation Decoding in Transformer Language Models**<br />
    Evan Hernandez, Martin Wattenberg, Arnab Sen Sharma, Jacob Andreas, Tal Haklay, Yonatan Belinkov, Kevin Meng, David Bau. [[paper](https://arxiv.org/pdf/2308.09124.pdf)]
7. **KLoB: a Benchmark for Assessing Knowledge Locating Methods in Language Models**<br />
    Yiming Ju, Zheng Zhang. [[paper](http://export.arxiv.org/pdf/2309.16535)]
8. **Inference-Time Intervention: Eliciting Truthful Answers from a Language Model** (NeurIPS 2023) <br />
    Kenneth Li, Oam Patel, Fernanda Viégas, Hanspeter Pfister, Martin Wattenberg. [[paper](https://arxiv.org/abs/2306.03341)] [[code](https://github.com/likenneth/honest_llama)]
9. **Emptying the Ocean with a Spoon: Should We Edit Models?** (EMNLP 2023 Findings) <br />
    Yuval Pinter and Michael Elhadad. [[paper](https://arxiv.org/pdf/2310.11958.pdf)]
10. **Unveiling the Pitfalls of Knowledge Editing for Large Language Models** <br />
    Zhoubo Li, Ningyu Zhang, Yunzhi Yao, Mengru Wang, Xi Chen and Huajun Chen. [[paper](https://arxiv.org/pdf/2310.02129.pdf)]
11. **Editing Personality for LLMs** <br />
    Shengyu Mao, Ningyu Zhang, Xiaohan Wang, Mengru Wang, Yunzhi Yao, Yong Jiang, Pengjun Xie, Fei Huang and Huajun Chen. [[paper](https://arxiv.org/pdf/2310.02168.pdf)]
12. **Evaluating Dependencies in Fact Editing for Language Models: Specificity and Implication Awareness**（Findings of EMNLP2023） <br />
    Zichao Li, Ines Arous, Siva Reddy, Jackie C.K. Cheung [[paper](https://arxiv.org/pdf/2312.01858.pdf)]
13. **Finding and Editing Multi-Modal Neurons in Pre-Trained Transformer** <br />
    Haowen Pan,Yixin Cao,Xiaozhi Wang,Xun Yang. [[paper](https://arxiv.org/abs/2311.07470)]
14. **Assessing Knowledge Editing in Language Models via Relation Perspective** <br />
    Yifan Wei,Xiaoyan Yu,Huanhuan Ma,Fangyu Lei,Yixuan Weng,Ran Song,Kang Liu. [[paper](https://arxiv.org/abs/2311.09053)]
15. **History Matters: Temporal Knowledge Editing in Large Language Model**（AAAI 2024） <br />
    Xunjian Yin,Jin Jiang,Liming Yang,Xiaojun Wan. [[paper](https://arxiv.org/abs/2312.05497)]
16. **Cross-Lingual Knowledge Editing in Large Language Models**  <br />
    Jiaan Wang, Yunlong Liang, Zengkui Sun, Yuxuan Cao, Jiarong Xu. [[paper](https://arxiv.org/pdf/2309.08952.pdf)]
17. **Large Language Models Relearn Removed Concepts** <br />
    Michelle Lo, Shay B. Cohen, Fazl Barez [[paper](https://arxiv.org/abs/2401.01814)]
18. **Model Editing Can Hurt General Abilities of Large Language Models** <br />
    Jia-Chen Gu, Hao-Xiang Xu, Jun-Yu Ma, Pan Lu, Zhen-Hua Ling, Kai-Wei Chang, Nanyun Peng [[paper](https://arxiv.org/pdf/2401.04700.pdf)]
19. **Model Editing at Scale leads to Gradual and Catastrophic Forgetting** <br />
    Akshat Gupta, Anurag Rao, Gopala Anumanchipalli. [[paper](https://arxiv.org/abs/2401.07453)]
20. **Propagation and Pitfalls: Reasoning-based Assessment of Knowledge Editing through Counterfactual Tasks** <br />
    Wenyue Hua, Jiang Guo, Mingwen Dong, Henghui Zhu, Patrick Ng, Zhiguo Wang. [[paper](https://arxiv.org/abs/2401.17585)]
21. **Long-form evaluation of model editing** <br />
      Domenic Rosati, Robie Gonzales, Jinkun Chen, Xuemin Yu. [[paper](https://arxiv.org/pdf/2402.09394.pdf)]
22. **The Butterfly Effect of Model Editing: Few Edits Can Trigger Large Language Models Collapse** <br />
    Wanli Yang, Fei Sun, Xinyu Ma, Xun Liu, Dawei Yin, Xueqi Cheng. [[paper](https://arxiv.org/pdf/2402.09656.pdf)]
23. **The Da Vinci Code of Large Pre-trained Language Models: Deciphering Degenerate Knowledge Neurons** <br />
 Yuheng Chen,Pengfei Cao,Yubo Chen,Yining Wang,Shengping Liu,Kang Liu,Jun Zhao. [[paper](https://arxiv.org/abs/2402.13731)]
24. **Navigating the Dual Facets: A Comprehensive Evaluation of Sequential Memory Editing in Large Language Models** <br />
 Zihao Lin, Mohammad Beigi, Hongxuan Li, Yufan Zhou, Yuxiang Zhang, Qifan Wang, Wenpeng Yin, Lifu Huang. [[paper](https://www.arxiv.org/abs/2402.11122)]
25. **“Flex Tape Can’t Fix That”:Bias and Misinformation in Edited Language Models** <br />
 Karina Halevy, Anna Sotnikova, Badr AlKhamissi, Syrielle Montariol, Antoine Bosselut. [[paper](https://arxiv.org/pdf/2403.00180)]
26. **The Missing Piece in Model Editing: A Deep Dive into the Hidden Damage Brought By Model Editing** <br />
 Jianchen Wang,Zhouhong Gu,Zhuozhi Xiong,Hongwei Feng,Yanghua Xiao. [[paper](https://arxiv.org/abs/2403.07825)]
27. **Beyond Memorization: The Challenge of Random Memory Access in Language Models** <br />
 Tongyao Zhu,Qian Liu,Liang Pang,Zhengbao Jiang,Min-Yen Kan,Min Lin. [[paper](https://arxiv.org/abs/2403.07805)]
28. **Interpreting Key Mechanisms of Factual Recall in Transformer-Based Language Models** <br />
 Ang Lv, Kaiyi Zhang, Yuhan Chen, Yulong Wang, Lifeng Liu, Ji-Rong Wen, Jian Xie, Rui Yan. [[paper](https://arxiv.org/abs/2403.19521)]
29. **MLaKE: Multilingual Knowledge Editing Benchmark for Large Language Models** <br />
 Zihao Wei,Jingcheng Deng,Liang Pang,Hanxing Ding,Huawei Shen,Xueqi Cheng. [[paper](https://arxiv.org/abs/2404.04990)]
30. **Is Your LLM Outdated? Benchmarking LLMs & Alignment Algorithms for Time-Sensitive Knowledge** <br />
 Seyed Mahed Mousavi, Simone Alghisi, Giuseppe Riccardi. [[paper](https://arxiv.org/abs/2404.08700)]
31. **Neighboring Perturbations of Knowledge Editing on Large Language Models**（ICML 2024）<br />
 Jun-Yu Ma, Jia-Chen Gu, Ningyu Zhang, Zhen-Hua Ling. [[paper](https://arxiv.org/pdf/2401.17623)]
32. **Event-level Knowledge Editing**<br />
 Hao Peng, Xiaozhi Wang, Chunyang Li, Kaisheng Zeng, Jiangshan Duo, Yixin Cao, Lei Hou, Juanzi Li. [[paper](https://arxiv.org/abs/2402.13093)]
33. **Updating Language Models with Unstructured Facts: Towards Practical Knowledge Editing**<br />
 Xiaobao Wu, Liangming Pan, William Yang Wang, Anh Tuan Luu. [[paper](https://arxiv.org/abs/2402.18909)]
34. **Detecting Edited Knowledge in Language Models**<br />
 Paul Youssef, Zhixue Zhao, Jörg Schlötterer, Christin Seifert. [[paper](https://arxiv.org/abs/2405.02765)]
35. **Perturbation-Restrained Sequential Model Editing**<br />
 Jun-Yu Ma, Hong Wang, Hao-Xiang Xu, Zhen-Hua Ling, Jia-Chen Gu. [[paper](https://arxiv.org/abs/2405.16821)]
36. **Leveraging Logical Rules in Knowledge Editing: A Cherry on the Top**<br />
 Keyuan Cheng, Muhammad Asif Ali, Shu Yang, Gang Lin, Yuxuan Zhai, Haoyang Fei, Ke Xu, Lu Yu, Lijie Hu, Di Wang. [[paper](https://arxiv.org/abs/2405.15452)]
37. **Model Editing by Standard Fine-Tuning**<br />
 Govind Gangadhar, Karl Stratos. [[paper](https://arxiv.org/abs/2402.11078v3)]
38. **AI-native Memory: A Pathway from LLMs Towards AGI**<br />
 Jingbo Shang, Zai Zheng, Xiang Ying, Felix Tao, Mindverse Team. [[paper](https://arxiv.org/abs/2406.18312)]
39. **Intrinsic Evaluation of Unlearning Using Parametric Knowledge Traces**<br />
 Yihuai Hong, Lei Yu, Shauli Ravfogel, Haiqin Yang, Mor Geva. [[paper](https://arxiv.org/abs/2406.11614)]
40. **Can Editing LLMs Inject Harm?**<br />
 Canyu Chen, Baixiang Huang, Zekun Li, Zhaorun Chen, Shiyang Lai, Xiongxiao Xu, Jia-Chen Gu, Jindong Gu, Huaxiu Yao, Chaowei Xiao, Xifeng Yan, William Yang Wang, Philip Torr, Dawn Song, Kai Shu. [[paper](https://arxiv.org/abs/2407.20224)]
41. **Editing Conceptual Knowledge for Large Language Models** (EMNLP 2024 Findings) <br />
 Xiaohan Wang, Shengyu Mao, Ningyu Zhang, Shumin Deng, Yunzhi Yao, Yue Shen, Lei Liang, Jinjie Gu, Huajun Chen. [[paper](https://arxiv.org/abs/2403.06259)]
42. **Knowledge Circuits in Pretrained Transformers** (NeurIPS 2024) <br />
 Yunzhi Yao, Ningyu Zhang, Zekun Xi, Mengru Wang, Ziwen Xu, Shumin Deng, Huajun Chen. [[paper](https://arxiv.org/abs/2405.17969)]
## 🧰 Resources

### Benchmarks and Tasks

|     Edit Type      | Benchmarks \& Datasets                                                  |
| :-----------------------: | ------------------------------------------------------------ |
| **Fact Knowledge**  | [ZSRE](https://github.com/nicola-decao/KnowledgeEditor), [ZSRE plus](https://arxiv.org/abs/2305.13172), [CounterFact](https://rome.baulab.info/),[CounterFact plus](https://arxiv.org/abs/2305.13172), [CounterFact+](https://arxiv.org/abs/2305.17553),[ECBD](https://github.com/yasumasaonoe/entity_knowledge_propagation), [MQUAKE](https://github.com/yasumasaonoe/entity_knowledge_propagation),[DepEdit](https://arxiv.org/abs/2312.01858)  |
|  **Multi-Lingual**   | [Bi-ZsRE](https://arxiv.org/pdf/2309.08952.pdf),[Eva-KELLM](https://arxiv.org/pdf/2308.09954.pdf), [MzsRE](https://arxiv.org/abs/2312.13040),[CROLIN-MQUAKE](https://www.arxiv.org/abs/2407.10275) |
|  **Sentiment**   | [Convsent](https://arxiv.org/abs/2206.06520) |
|  **Bias**   | [Bias in Bios](https://arxiv.org/pdf/2304.00740.pdf) |
|  **Hallucination**   | [WikiBio](https://github.com/Thartvigsen/GRACE/tree/main) |
|  **Commonsense**   | [MEMIT<sub>csk</sub>](https://arxiv.org/abs/2305.14956) |
|  **concept** |[ConceptEdit](https://arxiv.org/abs/2403.06259), [CONCEPTVECTORS](https://arxiv.org/abs/2406.11614) |
|  **Reasoning**   | [Eva-KELLM](https://arxiv.org/pdf/2308.09954.pdf) |
|  **Privacy Infomation Protect**   | [PrivQA](https://arxiv.org/abs/2310.02224), [Knowledge Sanitation](https://arxiv.org/pdf/2309.11852.pdf),[Enron](https://arxiv.org/pdf/2310.20138.pdf) |
|  **Unified Benchmark**   | [DUnE](https://arxiv.org/pdf/2311.16087.pdf) |
|  **Toxic Information**   | [RealToxicityPrompts](https://arxiv.org/abs/2009.11462),[Toxicity Unlearning](https://arxiv.org/pdf/2308.08090.pdf)|
|  **MultiModal**   | [MMEdit](https://arxiv.org/abs/2310.08475) [VLKEB](https://arxiv.org/abs/2403.07350), [MC-MKE](https://arxiv.org/abs/2406.13219)|
<!-- |   **Logical Reasoning**   | [ProofWriter](https://arxiv.org/abs/2012.13048), [EntailmentBank](https://arxiv.org/abs/2104.08661), [RuleTaker](https://www.ijcai.org/proceedings/2020/537), [CLUTRR](https://aclanthology.org/D19-1458/) |
| **Multimodal Reasoning**  | [SCIENCEQA](https://scienceqa.github.io/)                    |
| **Code**  |[CodeUpdateArena](https://www.arxiv.org/pdf/2407.06249)
|        **Others**         | [BIG-bench](https://doi.org/10.48550/arXiv.2206.04615), [SCAN](http://proceedings.mlr.press/v80/lake18a.html), [Chain-of-Thought Hub](https://arxiv.org/abs/2305.17306) | -->



### Tools
[EasyEdit](https://github.com/zjunlp/EasyEdit): An Easy-to-use Knowledge Editing Framework for Large Language Models.

[FastEdit](https://github.com/hiyouga/FastEdit): Editing large language models within 10 seconds
## Citation

Please cite our paper if find our work useful.

```bibtex

@article{zhang2024comprehensive,
  title={A Comprehensive Study of Knowledge Editing for Large Language Models},
  author={Zhang, Ningyu and Yao, Yunzhi and Tian, Bozhong and Wang, Peng and Deng, Shumin and Wang, Mengru and Xi, Zekun and Mao, Shengyu and Zhang, Jintian and Ni, Yuansheng and others},
  journal={arXiv preprint arXiv:2401.01286},
  year={2024}
}

@article{DBLP:journals/corr/abs-2305-13172,
  author       = {Yunzhi Yao and
                  Peng Wang and
                  Bozhong Tian and
                  Siyuan Cheng and
                  Zhoubo Li and
                  Shumin Deng and
                  Huajun Chen and
                  Ningyu Zhang},
  title        = {Editing Large Language Models: Problems, Methods, and Opportunities},
  journal      = {CoRR},
  volume       = {abs/2305.13172},
  year         = {2023},
  url          = {https://doi.org/10.48550/arXiv.2305.13172},
  doi          = {10.48550/arXiv.2305.13172},
  eprinttype    = {arXiv},
  eprint       = {2305.13172},
  timestamp    = {Tue, 30 May 2023 17:04:46 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2305-13172.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
## 🎉Contribution
### Contributors

<a href="https://github.com/zjunlp/ModelEditingPapers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=zjunlp/ModelEditingPapers" />
</a>

### Contributing to this paper list
-  There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.
### Acknowledgement
- We would like to express our gratitude to [Longhui Yu](https://yulonghui.github.io/) for the kind reminder about the missing papers.
