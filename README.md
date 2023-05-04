# Model Editing Papers

![](https://img.shields.io/github/last-commit/zjunlp/ModelEditingPapers?color=green) ![](https://img.shields.io/badge/paper%20numbers-20-yellow) ![visitors](https://visitor-badge.glitch.me/badge?page_id=zjunlp.ModelEditingPapers&left_color=grey&right_color=orange)

Model Editing is an interesting research area, which helps large models (especially large pre-trained models) generate expected output and perform more controllable without re-training. Model Editing has strong connections with following topics.

- Fixing model bugs and model patching
- Language models as knowledge base
- Locating facts in language models
- Lifelong learning, continual learning and etc.

This is a collection of research and review papers of Model Editing. Any suggestions and pull requests are welcome for better sharing of latest research progress.

### Preserve Parameter

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
**CaliNet: Calibrating Factual Knowledge in Pretrained Language Models**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2210.03329)] [[code](https://github.com/dqxiu/CaliNet)]

- Zeyu Huang, Yikang Shen, Xiaofeng Zhang, Jie Zhou, Wenge Rong, Zhang Xiong.<br />
**Transformer-Patcher: One Mistake worth One Neuron**. (ICLR 2023) [[paper](https://arxiv.org/abs/2301.09785)] [[code](https://github.com/ZeroYuHuang/Transformer-Patcher)]

### Modify Parameter

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

- Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim, Marzyeh Ghassemi.<br />
**Aging with GRACE: Lifelong Model Editing with Discrete Key-Value Adaptors**. [[paper](https://arxiv.org/abs/2211.11031)] [[code](https://github.com/thartvigsen/grace)]

- Peter Hase, Mohit Bansal, Been Kim, Asma Ghandeharioun.<br />
**Does Localization Inform Editing? Surprising Differences in Causality-Based Localization vs. Knowledge Editing in Language Models.** [[paper](https://arxiv.org/pdf/2301.04213.pdf)] [[code](https://github.com/google/belief-localization)]

### More Papers Related

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
