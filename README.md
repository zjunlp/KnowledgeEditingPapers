# Paper Collection of Model Editing

Model Editing is an interesting research area, which helps large models (especially large pre-trained models) generate expected output and perform more controllable without re-training. Model Editing has strong connections with following topics.

- Fixing model bugs and model patching
- Language models as knowledge base
- Locating facts in language models
- Lifelong learning, continual learning and etc.

This is a collection of research and review papers of Model Editing. Any suggestions and pull requests are welcome for better sharing of latest research progress.

## Papers

### Update Model Parameters

- Anton Sinitsin, Vsevolod Plokhotnyuk, Dmitry V. Pyrkin, Sergei Popov, Artem Babenko.
**Editable Neural Networks**. (ICLR 2020) [[paper](https://arxiv.org/abs/2004.00345)] [[code](https://github.com/xtinkt/editable)]

- Shibani Santurkar, Dimitris Tsipras, Mahalaxmi Elango, David Bau, Antonio Torralba, Aleksander Madry.
**Editing a classifier by rewriting its prediction rules**. (NeurIPS 2021) [[paper](https://proceedings.neurips.cc/paper/2021/hash/c46489a2d5a9a9ecfc53b17610926ddd-Abstract.html)] [[code](https://github.com/MadryLab/EditingClassifiers)]

- Nicola De Cao, Wilker Aziz, Ivan Titov.
**Editing Factual Knowledge in Language Models**. (EMNLP 2021) [[paper](https://arxiv.org/abs/2104.08164)] [[code](https://github.com/nicola-decao/KnowledgeEditor)]

- Kyungjae Lee, Wookje Han, Seung-won Hwang, Hwaran Lee, Joonsuk Park, Sang-Woo Lee.
**Plug-and-Play Adaptation for Continuously-updated QA**. (ACL 2022) [[paper](https://arxiv.org/abs/2204.12785)] [[code](https://github.com/wookjeHan/Plug-and-Play-Adaptation-for-Continuously-updated-QA)]

- Yang Xu, Yutai Hou, Wanxiang Che.
**Language Anisotropic Cross-Lingual Model Editing**. [[paper](https://arxiv.org/abs/2205.12677)] 

- Ryutaro Tanno, Melanie F. Pradier, Aditya Nori, Yingzhen Li.
**Repairing Neural Networks by Leaving the Right Past Behind**. [[paper](https://arxiv.org/abs/2207.04806)] []

- Eric Mitchell, Charles Lin, Antoine Bosselut, Chelsea Finn, Christopher D. Manning.
**Fast Model Editing at Scale**. (ICLR 2022) [[paper](https://arxiv.org/abs/2110.11309)] [[code](https://github.com/eric-mitchell/mend)] [[page](https://sites.google.com/view/mend-editing)]

- Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov.
**Locating and Editing Factual Associations in GPT**. (NeurIPS 2022) [[paper](https://arxiv.org/abs/2202.05262)] [[code](https://github.com/kmeng01/rome)] [[page](https://rome.baulab.info/)] [[video](https://www.youtube.com/watch?v=_NMQyOu2HTo&t=0)]

- Kevin Meng, Arnab Sen Sharma, Alex Andonian, Yonatan Belinkov, David Bau.
**Mass-Editing Memory in a Transformer**. [[paper](https://arxiv.org/abs/2210.07229)] [[code](https://github.com/kmeng01/memit)] [[page](https://memit.baulab.info/)] [[demo](https://memit.baulab.us/#/)]

- Peter Hase, Mona Diab, Asli Celikyilmaz, Xian Li, Zornitsa Kozareva, Veselin Stoyanov, Mohit Bansal, Srinivasan Iyer.
**Do Language Models Have Beliefs? Methods for Detecting, Updating, and Visualizing Model Beliefs**. [[paper](https://arxiv.org/pdf/2111.13654.pdf)] [[code](https://github.com/peterbhase/SLAG-Belief-Updating)]

- Thomas Hartvigsen, Swami Sankaranarayanan, Hamid Palangi, Yoon Kim, Marzyeh Ghassemi.
**Aging with GRACE: Lifelong Model Editing with Discrete Key-Value Adaptors**. [[paper](https://arxiv.org/abs/2211.11031)] [[code](https://github.com/thartvigsen/grace)]

### Model Gating and Memory Enhanced

- Eric Mitchell, Charles Lin, Antoine Bosselut, Christopher D. Manning, Chelsea Finn.
**Memory-Based Model Editing at Scale**. (ICML 2022) [[paper](https://arxiv.org/abs/2206.06520)] [[code](https://github.com/eric-mitchell/serac)] [[demo](https://sites.google.com/view/serac-editing)]

- Shikhar Murty, Christopher D. Manning, Scott M. Lundberg, Marco Túlio Ribeiro.
**Fixing Model Bugs with Natural Language Patches**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2211.03318)] [[code](https://github.com/MurtyShikhar/LanguagePatching)]

- Aman Madaan, Niket Tandon, Peter Clark, Yiming Yang.
MemPrompt.
**Memory-assisted Prompt Editing with User Feedback**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2201.06009)] [[code](https://github.com/madaan/memprompt)] [[page](https://memprompt.com/)] [[video](https://www.youtube.com/watch?v=Ld7R02bOiNQ&t=1s)]

- Daliang Li, Ankit Singh Rawat, Manzil Zaheer, Xin Wang, Michal Lukasik, Andreas Veit, Felix Yu, Sanjiv Kumar.
**Large Language Models with Controllable Working Memory**. [[paper](https://arxiv.org/abs/2211.05110)]

### More Papers Related

- Robert L. Logan IV, Alexandre Passos, Sameer Singh, Ming-Wei Chang.
**FRUIT: Faithfully Reflecting Updated Information in Text**. (NAACL 2022) [[paper]()] [[code]()]

- Oyvind Tafjord, Bhavana Dalvi Mishra, Peter Clark.
**Entailer: Answering Questions with Faithful and Truthful Chains of Reasoning**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2210.12217)] [[code](https://github.com/allenai/entailment_bank)] [[video](https://www.youtube.com/watch?v=GYTJ_Pxva7Q)]

- Ekin Akyürek, Tolga Bolukbasi, Frederick Liu, Binbin Xiong, Ian Tenney, Jacob Andreas, Kelvin Guu.
**Towards Tracing Factual Knowledge in Language Models Back to the Training Data**. (EMNLP 2022) [[paper](https://arxiv.org/abs/2204.12785)]

- Chenglei Si, Zhe Gan, Zhengyuan Yang, Shuohang Wang, Jianfeng Wang, Jordan Boyd-Graber, Lijuan Wang.
**Prompting GPT-3 To Be Reliable**. [[paper](https://arxiv.org/abs/2210.09150)]

- Gabriel Ilharco, Mitchell Wortsman, Samir Yitzhak Gadre, Shuran Song, Hannaneh Hajishirzi, Simon Kornblith, Ali Farhadi, Ludwig Schmidt.
**Patching open-vocabulary models by interpolating weights**. (NeurIPS 2022) [[paper](https://arxiv.org/abs/2208.05592)] [[code](https://github.com/mlfoundations/patching)]

