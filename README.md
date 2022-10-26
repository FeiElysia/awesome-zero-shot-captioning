# Zero/Few-Shot Captioning

While Vision-Language Model have achieved impressive performance on various of multimodal tasks, image captioning is still an open question to be solved, especially when we deploy image captioning model to the real world where the data distribution may deviate from training datasets completely. Zero/Few-shot captioning is a promising way to bridge this gap. Here is a curated reading list for zero/few-shot captioning. As works in this field is deficient, we have to contain some works which do not elaborately design for zero/few-shot captioning but test zero/few-shot performance in image captioning, works training with very little data and works for video captioning to enlarge this reading list. we are also thinking about whether to add some influential works about unsupervised image captioning and works concentrating on captioning of novel objects. Feel free to comment or drop us a line if you have any suggestion.

Note that instead of following the timeline of papers accepted by conference or journal, we curate these papers following the time when the initial version of papers are submitted on ArXiv.


## Reading List

## 2022

1. [MAPL: Parameter-Efficient Adaptation of Unimodal Pre-Trained Models for Vision-Language Few-Shot Prompting](https://arxiv.org/abs/2210.07179)

   *Oscar Mañas, Pau Rodriguez, Saba Ahmadi, Aida Nematzadeh, Yash Goyal, Aishwarya Agrawal*

   `arXiv preprint`
   
   `mapping network`  `parameter-efficient`

2. [Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language](https://arxiv.org/abs/2204.00598)

   *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence*

   `arXiv preprint` [[code](https://github.com/google-research/google-research/tree/master/socraticmodels)]
   
   `training-free`  `intermodule communication`

3. [Language Models Can See: Plugging Visual Controls in Text Generation](https://arxiv.org/abs/2205.02655)

   *Yixuan Su, Tian Lan, Yahui Liu, Fangyu Liu, Dani Yogatama, Yan Wang, Lingpeng Kong, Nigel Collier*

   `arXiv preprint` [[code](https://github.com/yxuansu/MAGIC)]
   
   `training-free`  `new decoding scheme`
   
4. [Flamingo: a Visual Language Model for Few-Shot Learning](https://arxiv.org/abs/2204.14198)

   *Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, Antoine Miech, Iain Barr, Yana Hasson, Karel Lenc, Arthur Mensch, Katie Millican, Malcolm Reynolds, Roman Ring, Eliza Rutherford, Serkan Cabi, Tengda Han, Zhitao Gong, Sina Samangooei, Marianne Monteiro, Jacob Menick, Sebastian Borgeaud, Andrew Brock, Aida Nematzadeh, Sahand Sharifzadeh, Mikolaj Binkowski, Ricardo Barreira, Oriol Vinyals, Andrew Zisserman, Karen Simonyan*

   `arXiv preprint`
   
   `free-form visual inputs`  `frozen LM conditioned by visual representations`  `in-context learning`

5. [CM3: A Causal Masked Multimodal Model of the Internet](https://arxiv.org/abs/2201.07520)

   *Armen Aghajanyan, Bernie Huang, Candace Ross, Vladimir Karpukhin, Hu Xu, Naman Goyal, Dmytro Okhonko, Mandar Joshi, Gargi Ghosh, Mike Lewis, Luke Zettlemoyer*

   `arXiv preprint`
   
   `causally masked objective`  `large-scale HTML data`
   
6. [Zero-Shot Video Captioning with Evolving Pseudo-Tokens (vedio captioning)](https://arxiv.org/abs/2207.11100)

   *Yoad Tewel, Yoav Shalev, Roy Nadler, Idan Schwartz, Lior Wolf*

   `arXiv preprint` [[code](https://github.com/YoadTew/zero-shot-video-to-text)]
   
   `pseudo-tokens`  `iterative generation`
   
## 2021

1. [Uni-Perceiver: Pre-training Unified Architecture for Generic Perception for Zero-shot and Few-shot Tasks]()

   *Xizhou Zhu, Jinguo Zhu, Hao Li, Xiaoshi Wu, Xiaogang Wang, Hongsheng Li, Xiaohua Wang, Jifeng Dai*

   `CVPR 2022`
   
   `unified model`  `modal-agnostic inputs`
   
2. [ZeroCap: Zero-Shot Image-to-Text Generation for Visual-Semantic Arithmetic](https://arxiv.org/abs/2111.14447)

   *Yoad Tewel, Yoav Shalev, Idan Schwartz, Lior Wolf*

   `CVPR 2022` [[code](https://github.com/YoadTew/zero-shot-image-to-text)]
   
   `training-free`  `image-guided context cache adjusting during inference`
   
3. [Scaling Up Vision-Language Pre-training for Image Captioning]()

   *Xiaowei Hu, Zhe Gan, Jianfeng Wang, Zhengyuan Yang, Zicheng Liu, Yumao Lu, Lijuan Wang*

   `arXiv preprint`
   
   `scaling up model`  `scaling up pre-training datasets`  `testing zero-shot performance`
   
4. [SimVLM: Simple Visual Language Model Pretraining with Weak Supervision]()

   *Zirui Wang, Jiahui Yu, Adams Wei Yu, Zihang Dai, Yulia Tsvetkov, Yuan Cao*

   `ICLR 2022`
   
   `weak supervision`  `pre-training end-to-end`  `testing zero-shot performance`
   
5. [VisualGPT: Data-efficient Adaptation of Pretrained Language Models for Image Captioning](https://arxiv.org/abs/2102.10407)

   *Jun Chen, Han Guo, Kai Yi, Boyang Li, Mohamed Elhoseiny*

   `CVPR 2022` [[code](https://github.com/Vision-CAIR/VisualGPT)]
   
   `data-efficient`
