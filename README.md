# Interactive NLP Papers🤖+👨‍💼📚🤗⚒️🌏 

Must-read papers on [Interactive NLP](https://arxiv.org/abs/2305.13246): a new paradigm of NLP.



## Content

- [What is Interactive NLP?](#what-is-interactive-nlp)
- [Keywords Convention](#keywords-convention)
- [Paper](#paper)
  - [Surveys and Position Papers](#surveys-and-position-papers)
  - [Human-LM Interaction](#human-lm-interaction)
  - [KB-LM Interaction](#kb-lm-interaction)
  - [Model/Tool-LM Interaction](#model-tool-lm-interaction)
  - [Environment-LM Interaction](#environment-lm-interaction)
  - [Evaluation](#evaluation)
  - [Application](#application)
- [Related Projects](#related-projects)
- [Contribution](#contribution)
  - [Contributors](#contributors)
  - [Contributing to this paper list](#contributing-to-this-paper-list)



## What is Interactive NLP?

**Interactive Natural Language Processing (iNLP)** considers language models as agents capable of observing, acting, and receiving feedback in a loop with external objects such as humans, knowledge bases, tools, models, and environments, where: 

- **Observation** involves all kinds of inputs to language models. 
- **Action** involves all kinds of outputs of language models such as text generation, requesting for external objects, text editing, etc. 
- **Feedback** involves feedback messages passed from external objects to language models such as scoring from humans.

<img src="assets/overview.png" width="60%">

In iNLP, language models can interact with four kinds of objects (i.e., entities): 

- interact with **humans** for better understanding and addressing user needs, personalizing responses, aligning with human values, and improving the overall user experience;
- interact with **knowledge bases** for enriching language representations with factual knowledge, enhancing the contextual relevance of responses, and dynamically leveraging external information to generate more accurate and informed responses;
- interact with **models/tools** for effectively decomposing and addressing complex tasks, leveraging specialized expertise for specific subtasks, and fostering the simulation of social behaviors;
- interact with **environments** for learning grounded representations of language, and effectively tackling embodied tasks such as reasoning, planning, and decision-making in response to environmental observations.



## Keywords Convention

![img](https://img.shields.io/badge/-InstructGPT-blue) The abbreviation of the work.

![img](https://img.shields.io/badge/-Prompting%20Chaining-orange) The interaction method used by the work.

![img](https://img.shields.io/badge/-formal%20language-lightgrey) The interaction interface used by the work.

![img](https://img.shields.io/badge/Other-green) Other important information of the work.



## Paper

### 🔭Surveys and Position Papers

- **[Interactive Natural Language Processing](https://arxiv.org/abs/2305.13246)**, 2023.05 ![img](https://img.shields.io/badge/Interactive_Learning-green)

  *Zekun Wang, Ge Zhang, Kexin Yang, Ning Shi, Wangchunshu Zhou, Shaochun Hao, Guangzheng Xiong, Yizhi Li, Mong Yuan Sim, Xiuying Chen, Qingqing Zhu, Zhenzhu Yang, Adam Nik, Qi Liu, Chenghua Lin, Shi Wang, Ruibo Liu, Wenhu Chen, Ke Xu, Dayiheng Liu, Yike Guo, Jie Fu*.

- **[Tool Learning with Foundation Models](https://arxiv.org/abs/2304.08354)**, 2023.04 ![img](https://img.shields.io/badge/-Tool--use-green) 

  *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun*.

- **[Augmented Language Models: a Survey](https://arxiv.org/abs/2302.07842)**, 2023.02 ![img](https://img.shields.io/badge/-Reasoning-green) ![img](https://img.shields.io/badge/-Tool--use-green)

  *Grégoire Mialon, Roberto Dessì, Maria Lomeli, Christoforos Nalmpantis, Ram Pasunuru, Roberta Raileanu, Baptiste Rozière, Timo Schick, Jane Dwivedi-Yu, Asli Celikyilmaz, Edouard Grave, Yann LeCun, Thomas Scialom*.

- **[Foundation Models for Decision Making: Problems, Methods, and Opportunities](https://arxiv.org/abs/2303.04129)**, 2023.03 ![img](https://img.shields.io/badge/-Tool--use-green) ![img](https://img.shields.io/badge/-Decision%20Making-green)

  *Sherry Yang, Ofir Nachum, Yilun Du, Jason Wei, Pieter Abbeel, Dale Schuurmans*.

### 👨‍💼Human-LM Interaction

- **[Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)**, 2022.03 ![img](https://img.shields.io/badge/-InstructGPT-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe*.

- **[Deep reinforcement learning from human preferences](https://arxiv.org/abs/1706.03741)**, 2017.06 ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Paul Christiano, Jan Leike, Tom B. Brown, Miljan Martic, Shane Legg, Dario Amodei*.

- **[Improving alignment of dialogue agents via targeted human judgements](https://arxiv.org/abs/2209.14375)**, 2022.09 ![img](https://img.shields.io/badge/-Sparrow-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Amelia Glaese, Nat McAleese, Maja Trębacz, John Aslanides, Vlad Firoiu, Timo Ewalds, Maribeth Rauh, Laura Weidinger, Martin Chadwick, Phoebe Thacker, Lucy Campbell-Gillingham, Jonathan Uesato, Po-Sen Huang, Ramona Comanescu, Fan Yang, Abigail See, Sumanth Dathathri, Rory Greig, Charlie Chen, Doug Fritz, Jaume Sanchez Elias, Richard Green, Soňa Mokrá, Nicholas Fernando, Boxi Wu, Rachel Foley, Susannah Young, Iason Gabriel, William Isaac, John Mellor, Demis Hassabis, Koray Kavukcuoglu, Lisa Anne Hendricks, Geoffrey Irving*.

- **[AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts](https://arxiv.org/abs/2110.01691)**, 2021.10 ![img](https://img.shields.io/badge/-AI%20Chains-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Configuration-green)

  *Tongshuang Wu, Michael Terry, Carrie J. Cai*.

- **[Interactive Text Generation](https://arxiv.org/abs/2303.00908)**, 2023.03 ![img](https://img.shields.io/badge/-ITG-blue) ![img](https://img.shields.io/badge/-Imitation%20Learning-orange) ![img](https://img.shields.io/badge/-Edits-lightgrey) ![img](https://img.shields.io/badge/Simulation-green)

  *Felix Faltings, Michel Galley, Baolin Peng, Kianté Brantley, Weixin Cai, Yizhe Zhang, Jianfeng Gao, Bill Dolan*.

- **[PromptChainer: Chaining Large Language Model Prompts through Visual Programming](https://arxiv.org/abs/2203.06566)**, 2022.03 ![img](https://img.shields.io/badge/-PromptChainer-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Configuration-green)

  *Tongshuang Wu, Ellen Jiang, Aaron Donsbach, Jeff Gray, Alejandra Molina, Michael Terry, Carrie J Cai*.

- **[RRHF: Rank Responses to Align Language Models with Human Feedback without tears](https://arxiv.org/abs/2304.05302)**, 2023.04 ![img](https://img.shields.io/badge/-RRHF-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Zheng Yuan, Hongyi Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, Fei Huang*.

- **[RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment](https://arxiv.org/abs/2304.06767)**, 2023.04 ![img](https://img.shields.io/badge/-RAFT-blue) ![img](https://img.shields.io/badge/Feedback-green)

  *Hanze Dong, Wei Xiong, Deepanshu Goyal, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, Tong Zhang*.

- **[Interactive Language: Talking to Robots in Real Time](https://arxiv.org/abs/2210.06407)**, 2022.10 ![img](https://img.shields.io/badge/-Interactive%20Language-blue) ![img](https://img.shields.io/badge/-Imitation%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Chat-green)

  *Corey Lynch, Ayzaan Wahid, Jonathan Tompson, Tianli Ding, James Betker, Robert Baruch, Travis Armstrong, Pete Florence*.

- **[Improving Grounded Language Understanding in a Collaborative Environment by Interacting with Agents Through Help Feedback](https://arxiv.org/abs/2304.10750)**, 2023.04 ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Chat,%20Feedback-green)

  *Nikhil Mehta, Milagro Teruel, Patricio Figueroa Sanz, Xin Deng, Ahmed Hassan Awadallah, Julia Kiseleva*.

- **[Is Reinforcement Learning (Not) for Natural Language Processing: Benchmarks, Baselines, and Building Blocks for Natural Language Policy Optimization](https://arxiv.org/abs/2210.01241)**, 2022.10 ![img](https://img.shields.io/badge/-RL4LMs-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Rajkumar Ramamurthy, Prithviraj Ammanabrolu, Kianté Brantley, Jack Hessel, Rafet Sifa, Christian Bauckhage, Hannaneh Hajishirzi, Yejin Choi*.

- **[Improving Multimodal Interactive Agents with Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2211.11602)**, 2022.11 ![img](https://img.shields.io/badge/-IBT-blue) ![img](https://img.shields.io/badge/-Imitation%20Learning,%20Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Josh Abramson, Arun Ahuja, Federico Carnevale, Petko Georgiev, Alex Goldin, Alden Hung, Jessica Landon, Jirka Lhotka, Timothy Lillicrap, Alistair Muldal, George Powell, Adam Santoro, Guy Scully, Sanjana Srivastava, Tamara von Glehn, Greg Wayne, Nathaniel Wong, Chen Yan, Rui Zhu*.

- **[Towards Teachable Reasoning Systems: Using a Dynamic Memory of User Feedback for Continual System Improvement](https://arxiv.org/abs/2204.13074)**, 2022.04 ![img](https://img.shields.io/badge/-TeachMe-blue) ![img](https://img.shields.io/badge/-Continual%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Feedback-green)

  *Bhavana Dalvi Mishra, Oyvind Tafjord, Peter Clark*.

- **[MemPrompt: Memory-assisted Prompt Editing with User Feedback](https://aclanthology.org/2022.emnlp-main.183.pdf)**, 2022.12 ![img](https://img.shields.io/badge/-MemPrompt-blue) ![img](https://img.shields.io/badge/-Active%20Learning-orange) ![img](https://img.shields.io/badge/-Edits-lightgrey) ![img](https://img.shields.io/badge/Personalization,%20Feedback-green)

  *Aman Madaan, Niket Tandon, Peter Clark, Yiming Yang*.

- **[Constitutional Al:learning from ai feedback](https://arxiv.org/abs/2212.08073)**, 2022.12 ![img](https://img.shields.io/badge/-Constitutional%20AI-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Feedback-green)

  *Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, Andy Jones, Anna Chen, Anna Goldie, Azalia Mirhoseini, Cameron McKinnon, Carol Chen, Catherine Olsson, Christopher Olah, Danny Hernandez, Dawn Drain, Deep Ganguli, Dustin Li, Eli Tran-Johnson, Ethan Perez, Jamie Kerr, Jared Mueller, Jeffrey Ladish, Joshua Landau, Kamal Ndousse, Kamile Lukosuite, Liane Lovitt, Michael Sellitto, Nelson Elhage, Nicholas Schiefer, Noemi Mercado, Nova DasSarma, Robert Lasenby, Robin Larson, Sam Ringer, Scott Johnston, Shauna Kravec, Sheer El Showk, Stanislav Fort, Tamera Lanham, Timothy Telleen-Lawton, Tom Conerly, Tom Henighan, Tristan Hume, Samuel R. Bowman, Zac Hatfield-Dodds, Ben Mann, Dario Amodei, Nicholas Joseph, Sam McCandlish, Tom Brown, Jared Kaplan*.

- **[Craft an Iron Sword: Dynamically Generating Interactive Game Characters by Prompting Large Language Models Tuned on Code](https://aclanthology.org/2022.wordplay-1.3/)**, 2022.01 ![img](https://img.shields.io/badge/Game,%20Chat-green)

  *Volum, Ryan and Rao, Sudha and Xu, Michael and DesGarennes, Gabriel A and Brockett, Chris and Van Durme, Benjamin and Deng, Olivia and Malhotra, Akanksha and Dolan, Bill*.

- **[LaMP: When Large Language Models Meet Personalization](https://arxiv.org/abs/2304.11406)**, 2023.04 ![img](https://img.shields.io/badge/-LaMP-blue) ![img](https://img.shields.io/badge/Personalization-green)

  *Alireza Salemi, Sheshera Mysore, Michael Bendersky, Hamed Zamani*.

- **[Languages are Rewards: Hindsight Finetuning using Human Feedback](https://arxiv.org/abs/2302.02676)**, 2023.02 ![img](https://img.shields.io/badge/-Chain%20of%20Hindsight-blue) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Feedback-green)

  *Hao Liu, Carmelo Sferrazza, Pieter Abbeel*.

- **[InternChat: Solving Vision-Centric Tasks by Interacting with Chatbots Beyond Language](https://arxiv.org/abs/2305.05662)**, 2023.05 ![img](https://img.shields.io/badge/-InternChat-blue) ![img](https://img.shields.io/badge/-Instruction%20Tuning-orange) ![img](https://img.shields.io/badge/Chat-green)

  *Zhaoyang Liu, Yinan He, Wenhai Wang, Weiyun Wang, Yi Wang, Shoufa Chen, Qinglong Zhang, Yang Yang, Qingyun Li, Jiashuo Yu, Kunchang Li, Zhe Chen, Xue Yang, Xizhou Zhu, Yali Wang, Limin Wang, Ping Luo, Jifeng Dai, Yu Qiao*.

- **[Improving Code Generation by Training with Natural Language Feedback](https://arxiv.org/abs/2303.16749)**, 2023.03 ![img](https://img.shields.io/badge/-ILF-blue) ![img](https://img.shields.io/badge/-Imitation%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Feedback-green)

  *Angelica Chen, Jérémy Scheurer, Tomasz Korbak, Jon Ander Campos, Jun Shern Chan, Samuel R. Bowman, Kyunghyun Cho, Ethan Perez*.


### 📚KB-LM Interaction
- **[Atlas: Few-shot learning with retrieval augmented language models](https://arxiv.org/pdf/2208.03299.pdf)**, 2022.08 ![img](https://img.shields.io/badge/-Atlas-blue) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Gautier Izacard, Patrick Lewis, Maria Lomeli, Lucas Hosseini, Fabio Petroni, Timo Schick, Jane Dwivedi-Yu, Armand Joulin, Sebastian Riedel, Edouard Grave*
  
- **[MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge](https://openreview.net/pdf?id=rc8o_j8I8PX)**, 2022.09 ![img](https://img.shields.io/badge/-MineDojo-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Internet%20Knowledge-green)

  *Linxi Fan, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, Anima Anandkumar*

- **[WebGPT: Browser-assisted question-answering with human feedback](https://arxiv.org/pdf/2112.09332.pdf)**, 2021.12 ![img](https://img.shields.io/badge/-WebGPT-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Internet%20Knowledge-green)
  
  *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess, John Schulman*
  
- **[Improving language models by retrieving from trillions of tokens](https://arxiv.org/pdf/2112.04426.pdf)**, 2022.07 ![img](https://img.shields.io/badge/-Retro-blue) ![img](https://img.shields.io/badge/-Message%20Fusion-orange) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Sebastian Borgeaud, Arthur Mensch, Jordan Hoffmann, Trevor Cai, Eliza Rutherford, Katie Millican, George van den Driessche, Jean-Baptiste Lespiau, Bogdan Damoc, Aidan Clark, Diego de Las Casas, Aurelia Guy, Jacob Menick, Roman Ring, Tom Hennigan, Saffron Huang, Loren Maggiore, Chris Jones, Albin Cassirer, Andy Brock, Michela Paganini, Geoffrey Irving, Oriol Vinyals, Simon Osindero, Karen Simonyan, Jack W. Rae, Erich Elsen, Laurent Sifre*
  
- **[REALM: retrieval-augmented language model pre-training](https://dl.acm.org/doi/pdf/10.5555/3524938.3525306)**, 2020.07 ![img](https://img.shields.io/badge/-REALM-blue) ![img](https://img.shields.io/badge/-Message%20Fusion-orange) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat, Ming-Wei Chang*
  
- **[KELM: Knowledge Enhanced Pre-Trained Language Representations with Message Passing on Hierarchical Relational Graphs](https://openreview.net/pdf?id=FkG-sX5CE_)**, 2022.04 ![img](https://img.shields.io/badge/-KELM-blue) ![img](https://img.shields.io/badge/-Message%20Fusion-orange) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Yinquan Lu, Haonan Lu, Guirong Fu, Qun Liu*
  
- **[K-Adapter: Infusing Knowledge into Pre-Trained Models with Adapters](https://aclanthology.org/2021.findings-acl.121.pdf)**, 2021.06 ![img](https://img.shields.io/badge/-K--Adapter-blue) ![img](https://img.shields.io/badge/-Parameter%20Efficient%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Ruize Wang, Duyu Tang, Nan Duan, Zhongyu Wei, Xuanjing Huang, Jianshu Ji, Guihong Cao, Daxin Jiang, Ming Zhou*
  
- **[Binding Language Models in Symbolic Languages](https://arxiv.org/pdf/2210.02875.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-Binder-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Zhoujun Cheng, Tianbao Xie, Peng Shi, Chengzu Li, Rahul Nadkarni, Yushi Hu, Caiming Xiong, Dragomir Radev, Mari Ostendorf, Luke Zettlemoyer, Noah A. Smith, Tao Yu*
  
- **[Teaching language models to support answers with verified quotes](https://arxiv.org/pdf/2203.11147.pdf)**, 2022.03 ![img](https://img.shields.io/badge/-GopherCite-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Internet%20Knowledge-green)
  
  *Jacob Menick, Maja Trebacz, Vladimir Mikulik, John Aslanides, Francis Song, Martin Chadwick, Mia Glaese, Susannah Young, Lucy Campbell-Gillingham, Geoffrey Irving, Nat McAleese*
  
- **[ERNIE: Enhanced Representation through Knowledge Integration](https://arxiv.org/pdf/1904.09223)**, 2019.04 ![img](https://img.shields.io/badge/-ERNIE-blue) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Yu Sun, Shuohuan Wang, Yukun Li, Shikun Feng, Xuyi Chen, Han Zhang, Xin Tian, Danxiang Zhu, Hao Tian, Hua Wu*
  
- **[K-BERT: Enabling Language Representation with Knowledge Graph](https://ojs.aaai.org/index.php/AAAI/article/view/5681/5537)**, 2020.02 ![img](https://img.shields.io/badge/-K--BERT-blue) ![img](https://img.shields.io/badge/-Message%20Fusion-orange) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Qi Ju, Haotang Deng, Ping Wang*
  
- **[Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401)**, 2020.12 ![img](https://img.shields.io/badge/-RAG-blue) ![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela*
  
- **[DocPrompting: Generating Code by Retrieving the Docs](https://openreview.net/pdf?id=ZTCxT2t2Ru)**, 2023.05 ![img](https://img.shields.io/badge/-DocPrompting-blue) ![img](https://img.shields.io/badge/-Standard%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/-Internet%20Knowledge-green)
  
  *Shuyan Zhou, Uri Alon, Frank F. Xu, Zhiruo Wang, Zhengbao Jiang, Graham Neubig*
  
- **[Recitation-Augmented Language Models](https://openreview.net/pdf?id=-cqvvvb-NkI)**, 2023.05 ![img](https://img.shields.io/badge/-RECITE-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange)![img](https://img.shields.io/badge/-Corpus%20Knowledge-green)
  
  *Zhiqing Sun, Xuezhi Wang, Yi Tay, Yiming Yang, Denny Zhou*
  
- **[Mind's Eye: Grounded Language Model Reasoning through Simulation](https://openreview.net/pdf?id=4rXMRuoJlai)**, 2023.05 ![img](https://img.shields.io/badge/-Mind%E2%80%99s%20Eye-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey)
  
  *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M Dai*
  
- **[Don't Generate, Discriminate: A Proposal for Grounding Language Models to Real-World Environments](https://arxiv.org/pdf/2212.09736)**, 2023.10 ![img](https://img.shields.io/badge/-Pangu-blue) ![img](https://img.shields.io/badge/-Message%20Fusion-orange) ![img](https://img.shields.io/badge/-Internet%20Knowledge-green)
  
  *Yu Gu, Xiang Deng, Yu Su*
  
- **[Check Your Facts and Try Again: Improving Large Language Models with External Knowledge and Automated Feedback](https://arxiv.org/pdf/2302.12813)**, 2023.02 ![img](https://img.shields.io/badge/-LLM--Augmenter-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Internet%20Knowledge-green)
  
  *Baolin Peng, Michel Galley, Pengcheng He, Hao Cheng, Yujia Xie, Yu Hu, Qiuyuan Huang, Lars Liden, Zhou Yu, Weizhu Chen, Jianfeng Gao*

### 🤖Model/🛠Tool-LM Interaction

- **[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)**, 2023.04 ![img](https://img.shields.io/badge/-Generative%20Agents-blue) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Society-green)

  *Joon Sung Park, Joseph C. O'Brien, Carrie J. Cai, Meredith Ringel Morris, Percy Liang, Michael S. Bernstein*.

- **[ReAct: Synergizing reasoning and acting in language models](https://arxiv.org/abs/2210.03629)**, 2022.10 ![img](https://img.shields.io/badge/-ReAct-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought,%20Tool--use-green)

  *Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao*.

- **[Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models](https://arxiv.org/abs/2303.04671)**, 2023.05 ![img](https://img.shields.io/badge/-Visual%20ChatGPT-blue) ![img](https://img.shields.io/badge/Chain%20of%20Thought,%20Tool--use-green)

  *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan*.

- **[HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face](https://arxiv.org/abs/2303.17580)**, 2023.05 ![img](https://img.shields.io/badge/-HuggingGPT-blue) ![img](https://img.shields.io/badge/Tool--use-green)

  *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang*.

- **[CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society](https://arxiv.org/abs/2303.17760)**, 2023.03 ![img](https://img.shields.io/badge/-CAMEL-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Society-green)

  *Guohao Li, Hasan Abed Al Kader Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem*.

- **[Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language](https://arxiv.org/abs/2204.00598)**, 2022.05 ![img](https://img.shields.io/badge/-Socratic%20Model-blue) ![img](https://img.shields.io/badge/Communication-green)

  *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence*.

- **[MindCraft: Theory of Mind Modeling for Situated Dialogue in Collaborative Tasks](https://arxiv.org/abs/2109.06275)**, 2021.09 ![img](https://img.shields.io/badge/-MindCraft-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Theory%20of%20Mind,%20Communication-green)

  *Cristian-Paul Bara, Sky CH-Wang, Joyce Chai*.

- **[Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://arxiv.org/abs/2211.12588)**, 2022.11 ![img](https://img.shields.io/badge/-PoT%20Prompting-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use,%20Chain%20of%20Thought-green)

  *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen*.

- **[Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)**, 2023.02 ![img](https://img.shields.io/badge/-Toolformer-blue) ![img](https://img.shields.io/badge/Tool--use-green)

  *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom*.

- **[ART: Automatic multi-step reasoning and tool-use for large language models](https://arxiv.org/abs/2303.09014)**, 2023.03 ![img](https://img.shields.io/badge/-ART-blue) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use,%20Chain%20of%20Thought-green)

  *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro*.

- **[Small Models are valuable Plug-ins for large language models](https://arxiv.org/pdf/2305.08848.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-SuperICL-blue) ![img](https://img.shields.io/badge/-Standard%20Prompting-orange)

  *Canwen Xu, Yichong Xu, Shuohang Wang, Yang Liu, Chenguang Zhu, Julian McAuley*.

- **[LEAST-TO-MOST PROMPTINGENABLESCOMPLEXREASONING IN LARGE LANGUAGE MODELS](https://arxiv.org/abs/2205.10625)**, 2022.05 ![img](https://img.shields.io/badge/-least--to--most%20prompting-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi*.

- **[Decomposed Prompting: A Modular Approach for Solving Complex Tasks](https://arxiv.org/abs/2210.02406)**, 2022.10 ![img](https://img.shields.io/badge/-Decomposed%20Prompting-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Tushar Khot, Harsh Trivedi, Matthew Finlayson, Yao Fu, Kyle Richardson, Peter Clark, Ashish Sabharwal*.

- **[ViperGPT: Visual Inference via Python Execution for Reasoning](https://arxiv.org/pdf/2303.08128.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-ViperGPT-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Dídac Surís,  Sachit Menon, Carl Vondrick*.

- **[See,Think,Confirm:Interactive Prompting Between Vision and Language Models for Knowledge-based Visual Reasoning](https://arxiv.org/pdf/2301.05226.pdf)**, 2023.01 ![img](https://img.shields.io/badge/-IPVR-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Tool--use-green)

  *Zhenfang Chen, Qinhong Zhou, Yikang Shen, Yining Hong, Hao Zhang, Chuang Gan*.

- **[Large Language Models Are Reasoning Teachers](https://arxiv.org/abs/2212.10071)**, 2022.12 ![img](https://img.shields.io/badge/-Fine--tune--CoT-blue) ![img](https://img.shields.io/badge/-Semi--Supervised%20Fine--Tuning,%20Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Namgyu Ho, Laura Schmid, Se-Young Yun*.

- **[STaR:Self-Taught ReasonerBootstrapping Reasoning With Reasoning](https://arxiv.org/pdf/2203.14465.pdf)**, 2022.03 ![img](https://img.shields.io/badge/-STaR-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting,%20Semi--Supervised%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman*.

- **[Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/pdf/2305.10601.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-ToT-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan*.

- **[Search-in-the-Chain: Towards Accurate, Credible and Traceable Large Language Models for Knowledge-intensive Tasks](https://arxiv.org/pdf/2304.14732v4.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-SearChain-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Tool--use,%20Chain%20of%20Thought-green)

  *Shicheng Xu, Liang Pang, HuaWei Shen, Xueqi Cheng, Tat-Seng Chua*.

- **[RECURRENTGPT: Interactive Generation of (Arbitrarily) Long Text](https://arxiv.org/pdf/2305.13304v1.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-RecurrentGPT-blue) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Wangchunshu Zhou, Yuchen Eleanor Jiang, Peng Cui, Tiannan Wang, Zhenxin Xiao, Yifan Hou, Ryan Cotterell, Mrinmaya Sachan*.

- **[PAL: Program-aided Language Models](https://arxiv.org/pdf/2211.10435v2.pdf)**, 2022.11 ![img](https://img.shields.io/badge/-PAL-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought,%20Tool--use-green)

  *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, PengFei Liu, Yiming Yang, Jamie Callan, Graham Neubig*.

- **[Internet-augmented language models through few-shot prompting for open-domain question answering](https://arxiv.org/pdf/2203.05115v2.pdf)**, 2023.05 ![img](https://img.shields.io/badge/Tool--use-green)

  *Angeliki Lazaridou, Elena Gribovskaya, Wojciech Stokowiec, Nikolai Grigorev*.

- **[Recitation-Augmented Language Models](https://arxiv.org/pdf/2210.01296v2.pdf)**, 2022.10 ![img](https://img.shields.io/badge/-RECITE-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Zhiqing Sun, Xuezhi Wang, Yi Tay, Yiming Yang, Denny Zhou*.

- **[Iteratively Prompt Pre-trained Language Models for Chain of Thought](https://arxiv.org/pdf/2203.08383v3.pdf)**, 2022.03 ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Boshi Wang, Xiang Deng, Huan Sun*.

- **[MEASURING AND NARROWING THE COMPOSITIONALITY GAP IN LANGUAGE MODELS](https://arxiv.org/pdf/2210.03350v2.pdf)**, 2022.10 ![img](https://img.shields.io/badge/-self--ask-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Tool--use,%20Chain%20of%20Thought-green)

  *Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith, Mike Lewis*.

- **[Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/pdf/2303.17651v1.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-self--refine-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Self--Interaction-green)

  *Aman Madaan, Niket Tandon, Prakhar Gupta, Skyler Hallinan, Luyu Gao, Sarah Wiegreffe, Uri Alon, Nouha Dziri, Shrimai Prabhumoye, Yiming Yang, Sean Welleck, Bodhisattwa Prasad Majumder, Shashank Gupta, Amir Yazdanbakhsh, Peter Clark*.

- **[LEVER: Learning to Verify Language-to-Code Generation with Execution](https://arxiv.org/pdf/2302.08468v1.pdf)**, 2023.02 ![img](https://img.shields.io/badge/-LEVER-blue) ![img](https://img.shields.io/badge/-Standard%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Ansong Ni, Srini Iyer, Dragomir Radev, Ves Stoyanov, Wen-tau Yih, Sida I. Wang, Xi Victoria Lin*.

- **[Computational Language Acquisition with Theory of Mind](https://arxiv.org/pdf/2303.01502v1.pdf)**, 2023.03 ![img](https://img.shields.io/badge/Theory%20of%20Mind-green)

  *Andy Liu, Hao Zhu, Emmy Liu, Yonatan Bisk, Graham Neubig*.

- **[Few-shot Language Coordination by Modeling Theory of Mind](https://arxiv.org/pdf/2107.05697v1.pdf)**, 2021.07 ![img](https://img.shields.io/badge/Theory%20of%20Mind-green)

  *Hao Zhu, Graham Neubig, Yonatan Bisk*.

- **[OpenAGI: When LLM Meets Domain Experts](https://arxiv.org/pdf/2304.04370v2.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-OpenAGI-blue) ![img](https://img.shields.io/badge/-Standard%20Prompting,%20Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Yingqiang Ge, Wenyue Hua, Jianchao Ji, Juntao Tan, Shuyuan Xu, Yongfeng Zhang*.

- **[MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action](https://arxiv.org/pdf/2303.11381v1.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-MM--ReAct-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Tool--use-green)

  *Zhengyuan Yang, Linjie Li, JianFeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang*.

- **[Prompt, Generate, then Cache: Cascade of Foundation Models makes Strong Few-shot Learners](https://arxiv.org/pdf/2303.02151v1.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-CaFo-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language,%20Machine%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Renrui Zhang, Xiangfei Hu, Bohao Li, Siyuan Huang, Hanqiu Deng, Hongsheng Li, Yu Qiao, Peng Gao*.

- **[Principle-Driven Self-Alignment of Language Models from Scratch with Minimal Human Supervision](https://arxiv.org/pdf/2305.03047v1.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-SELF--ALIGN-blue) ![img](https://img.shields.io/badge/-Instruction%20Tuning,Semi--Supervised%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Alignment-green)

  *Zhiqing Sun, Yikang Shen, Qinhong Zhou, Hongxin Zhang, Zhenfang Chen, David Cox, Yiming Yang, Chuang Gan*.

- **[Think Before You Act: Unified Policy for Interleaving Language Reasoning with Actions](https://arxiv.org/pdf/2304.11063v1.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Natural%20Language,%20Machine%20Language-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Lina Mezghani, Piotr Bojanowski, Karteek Alahari, Sainbayar Sukhbaatar*.

- **[TALM: Tool Augmented Language Models](https://arxiv.org/pdf/2205.12255v1.pdf)**, 2022.05 ![img](https://img.shields.io/badge/-TALM-blue) ![img](https://img.shields.io/badge/-Instruction%20Tuning,Semi--Supervised%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Aaron Parisi, Yao Zhao, Noah Fiedel*.

- **[Successive Prompting for Decomposing Complex Questions](https://arxiv.org/pdf/2212.04092v1.pdf)**, 2022.12 ![img](https://img.shields.io/badge/-Successive%20Prompting-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Dheeru Dua, Shivanshu Gupta, Sameer Singh, Matt Gardner*.

- **[REFINER: Reasoning Feedback on Intermediate Representations](https://arxiv.org/pdf/2304.01904v1.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-REFINER-blue) ![img](https://img.shields.io/badge/-Semi--Supervised%20Fine--Tuning,%20Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought,%20Reasoning-green)

  *Debjit Paul, Mete Ismayilzada, Maxime Peyrard, Beatriz Borges, Antoine Bosselut, Robert West, Boi Faltings*.

- **[LeTI: Learning to Generate from Textual Interactions](https://arxiv.org/pdf/2305.10314v1.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-LeTI-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Xingyao Wang, Hao Peng, Reyhaneh Jabbarvand, Heng Ji*.

- **[InternGPT: Solving Vision-Centric Tasks by Interacting with Chatbots Beyond Language](https://arxiv.org/pdf/2305.05662v3.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-InternGPT-blue) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Zhaoyang Liu, Yinan He, Wenhai Wang, Weiyun Wang, Yi Wang, Shoufa Chen, Qinglong Zhang, Yang Yang, Qingyun Li, Jiashuo Yu, Kunchang Li, Zhe Chen, Xue Yang, Xizhou Zhu, Yali Wang, LiMin Wang, Ping Luo, Jifeng Dai, Yu Qiao*.

- **[Human-level play in the game of Diplomacy by combining language models with strategic reasoning](https://www.science.org/doi/10.1126/science.ade9097)**, 2022.11 ![img](https://img.shields.io/badge/-Cicero-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Decision%20Making-green)

  *Anton Bakhtin, Noam Brown, Emily Dinan, Gabriele Farina, Colin Flaherty, Daniel Fried, Andrew Goff, Jonathan Gray, Hengyan Hu, Athul Paul Jacob, Mojtaba Komeili, Karthik Konath, Minae Kwon, Adam Lerer, Mike Lewis, Alexander H. Miller, Sash Mitts, Aditya Renduchintala, Stephen Roller, Dirk Rowe, Weiyan Shi, Joe Spisak, Alexander Wei, David Wu, Hugh Zhang, Markus Zijlstra*.

- **[Generating Sequences by Learning to Self-Correct](https://arxiv.org/abs/2211.00053)**, 2022.10 ![img](https://img.shields.io/badge/-Self--Correction-blue) ![img](https://img.shields.io/badge/-Semi--Supervised%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/-Natural%20Language,%20Edits-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Sean Welleck, Ximing Lu, Peter West, Faeze Brahman, Tianxiao Shen, Daniel Khashabi, Yejin Choi*.

- **[ChatGPT-steered Editing Instructor for Customization of Abstractive Summarization](https://arxiv.org/pdf/2305.02483v1.pdf)**, 2023.05 ![img](https://img.shields.io/badge/-Semi--Supervised%20Fine--Tuning,%20Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language,%20Edits-lightgrey) ![img](https://img.shields.io/badge/Chain%20of%20Thought-green)

  *Wen Xiao, Yujia Xie, Giuseppe Carenini, Pengcheng He*.

- **[ChatGPT Asks, BLIP-2 Answers: Automatic Questioning Towards Enriched Visual Descriptions](https://arxiv.org/pdf/2303.06594v1.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-ChatCaptioner-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Deyao Zhu, Jun Chen, Kilichbek Haydarov, Xiaoqian Shen, Wenxuan Zhang, Mohamed Elhoseiny*.

- **[Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models](https://arxiv.org/pdf/2304.09842v2.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-Chameleon-blue) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Tool--use-green)

  *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao*.

- **[Baize: An Open-Source Chat Model with Parameter-Efficient Tuning on Self-Chat Data](https://arxiv.org/pdf/2304.01196v3.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-Baize-blue) ![img](https://img.shields.io/badge/-Parameter--Efficient%20Fine--Tuning,%20Semi--Supervised%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Chat-green)

  *Canwen Xu, Daya Guo, Nan Duan, Julian McAuley*.


### 🌎Environment-LM Interaction
- **[BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://arxiv.org/abs/2301.12597)**, 2023.01 ![img](https://img.shields.io/badge/-BLIP--2-blue) ![img](https://img.shields.io/badge/-Semi--Supervised%20Fine--Tuning-orange) ![img](https://img.shields.io/badge/-Machine%20Language-lightgrey) ![img](https://img.shields.io/badge/Modality%20Grounding-green)

  *Junnan Li, Dongxu Li, Silvio Savarese, Steven Hoi*.

- **[Do As I Can, Not As I Say: Grounding Language in Robotic Affordances](https://arxiv.org/abs/2204.01691)**, 2022.04 ![img](https://img.shields.io/badge/-SayCan-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Michael Ahn, Anthony Brohan, Noah Brown, Yevgen Chebotar, Omar Cortes, Byron David, Chelsea Finn, Chuyuan Fu, Keerthana Gopalakrishnan, Karol Hausman, Alex Herzog, Daniel Ho, Jasmine Hsu, Julian Ibarz, Brian Ichter, Alex Irpan, Eric Jang, Rosario Jauregui Ruano, Kyle Jeffrey, Sally Jesmonth, Nikhil J Joshi, Ryan Julian, Dmitry Kalashnikov, Yuheng Kuang, Kuang-Huei Lee, Sergey Levine, Yao Lu, Linda Luu, Carolina Parada, Peter Pastor, Jornell Quiambao, Kanishka Rao, Jarek Rettinghouse, Diego Reyes, Pierre Sermanet, Nicolas Sievers, Clayton Tan, Alexander Toshev, Vincent Vanhoucke, Fei Xia, Ted Xiao, Peng Xu, Sichun Xu, Mengyuan Yan, Andy Zeng*.

- **[RT-1: Robotics Transformer for Real-World Control at Scale](https://arxiv.org/abs/2212.06817)**, 2022.12 ![img](https://img.shields.io/badge/-RT--1-blue)![img](https://img.shields.io/badge/Foundation%20Model-green)

  *Anthony Brohan, Noah Brown, Justice Carbajal, Yevgen Chebotar, Joseph Dabis, Chelsea Finn, Keerthana Gopalakrishnan, Karol Hausman, Alex Herzog, Jasmine Hsu, Julian Ibarz, Brian Ichter, Alex Irpan, Tomas Jackson, Sally Jesmonth, Nikhil J Joshi, Ryan Julian, Dmitry Kalashnikov, Yuheng Kuang, Isabel Leal, Kuang-Huei Lee, Sergey Levine, Yao Lu, Utsav Malla, Deeksha Manjunath, Igor Mordatch, Ofir Nachum, Carolina Parada, Jodilyn Peralta, Emily Perez, Karl Pertsch, Jornell Quiambao, Kanishka Rao, Michael Ryoo, Grecia Salazar, Pannag Sanketi, Kevin Sayed, Jaspiar Singh, Sumedh Sontakke, Austin Stone, Clayton Tan, Huong Tran, Vincent Vanhoucke, Steve Vega, Quan Vuong, Fei Xia, Ted Xiao, Peng Xu, Sichun Xu, Tianhe Yu, Brianna Zitkovich*.

- **[PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/abs/2303.03378)**, 2023.03 ![img](https://img.shields.io/badge/-PaLM--E-blue)![img](https://img.shields.io/badge/Foundation%20Model-green)

  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence*.

- **[Grounded decoding: Guiding text generation with grounded models for robot control](https://arxiv.org/abs/2303.00855)**, 2023.03 ![img](https://img.shields.io/badge/Grounded%20Decoding-blue) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Wenlong Huang, Fei Xia, Dhruv Shah, Danny Driess, Andy Zeng, Yao Lu, Pete Florence, Igor Mordatch, Sergey Levine, Karol Hausman, Brian Ichter*.

- **[Inner monologue: Embodied reasoning through planning with language models.](https://arxiv.org/abs/2207.05608)**, 2022.07 ![img](https://img.shields.io/badge/Inner%20Monologue-blue)![img](https://img.shields.io/badge/Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Wenlong Huang, Fei Xia, Ted Xiao, Harris Chan, Jacky Liang, Pete Florence, Andy Zeng, Jonathan Tompson, Igor Mordatch, Yevgen Chebotar, Pierre Sermanet, Noah Brown, Tomas Jackson, Linda Luu, Sergey Levine, Karol Hausman, Brian Ichter*.

- **[Code as Policies: Language Model Programs for Embodied Control](https://arxiv.org/abs/2209.07753)**, 2022.09 ![img](https://img.shields.io/badge/Code%20as%20Policies-blue)![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey)

  *Jacky Liang, Wenlong Huang, Fei Xia, Peng Xu, Karol Hausman, Brian Ichter, Pete Florence, Andy Zeng*.

- **[Open-vocabulary Queryable Scene Representations for Real World Planning](https://arxiv.org/abs/2209.09874)**, 2022.09 ![img](https://img.shields.io/badge/-NLMap-blue) ![img](https://img.shields.io/badge/-Active%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Boyuan Chen, Fei Xia, Brian Ichter, Kanishka Rao, Keerthana Gopalakrishnan, Michael S. Ryoo, Austin Stone, Daniel Kappler*.

- **[Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks](https://arxiv.org/abs/2303.16563)**, 2023.03 ![img](https://img.shields.io/badge/-Plan4MC-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Haoqi Yuan, Chi Zhang, Hongcheng Wang, Feiyang Xie, Penglin Cai, Hao Dong, Zongqing Lu*.

- **[MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge](https://arxiv.org/abs/2206.08853)**, 2022.06 ![img](https://img.shields.io/badge/-MineDojo-blue) ![img](https://img.shields.io/badge/-Active%20Learning,%20Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Linxi Fan, Guanzhi Wang, Yunfan Jiang, Ajay Mandlekar, Yuncong Yang, Haoyi Zhu, Andrew Tang, De-An Huang, Yuke Zhu, Anima Anandkumar*.

- **[Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language](https://arxiv.org/abs/2204.00598)**, 2022.04 ![img](https://img.shields.io/badge/Socratic%20Models-blue)![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language%20,%20Shared%20Memory-lightgrey) ![img](https://img.shields.io/badge/Modality%20Grounding-green)

  *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence*.

- **[Interactive Language: Talking to Robots in Real Time](https://arxiv.org/abs/2210.06407)**, 2022.10 ![img](https://img.shields.io/badge/Interactive%20Language-blue)![img](https://img.shields.io/badge/-Imitation%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Corey Lynch, Ayzaan Wahid, Jonathan Tompson, Tianli Ding, James Betker, Robert Baruch, Travis Armstrong, Pete Florence*.

- **[LM-Nav: Robotic Navigation with Large Pre-Trained Models of Language, Vision, and Action](https://arxiv.org/abs/2207.04429)**, 2022.07 ![img](https://img.shields.io/badge/LM--Nav-blue)![img](https://img.shields.io/badge/-Prompt%20Chaining-orange)

  *Dhruv Shah, Blazej Osinski, Brian Ichter, Sergey Levine*.

- **[WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents](https://arxiv.org/abs/2207.01206)**, 2022.07 ![img](https://img.shields.io/badge/WebShop-blue)![img](https://img.shields.io/badge/-Reinforcement%20Learning,%20Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language,%20Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding,%20Tool--use-green)

  *Shunyu Yao, Howard Chen, John Yang, Karthik Narasimhan*.

- **[Improving Multimodal Interactive Agents with Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2211.11602)**, 2022.11 ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange)

  *Josh Abramson, Arun Ahuja, Federico Carnevale, Petko Georgiev, Alex Goldin, Alden Hung, Jessica Landon, Jirka Lhotka, Timothy Lillicrap, Alistair Muldal, George Powell, Adam Santoro, Guy Scully, Sanjana Srivastava, Tamara von Glehn, Greg Wayne, Nathaniel Wong, Chen Yan, Rui Zhu*.

- **[VIMA: General Robot Manipulation with Multimodal Prompts](https://arxiv.org/abs/2210.03094)**, 2022.10 ![img](https://img.shields.io/badge/-VIMA-blue) ![img](https://img.shields.io/badge/-Message%20Fusion-orange) ![img](https://img.shields.io/badge/Foundation%20Model-green)

  *Yunfan Jiang, Agrim Gupta, Zichen Zhang, Guanzhi Wang, Yongqiang Dou, Yanjun Chen, Li Fei-Fei, Anima Anandkumar, Yuke Zhu, Linxi Fan*.

- **[PIGLeT: Language Grounding Through Neuro-Symbolic Interaction in a 3D World](https://arxiv.org/abs/2106.00188)**, 2021.06 ![img](https://img.shields.io/badge/-PIGLeT-blue) ![img](https://img.shields.io/badge/-Standard%20Prompting-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Rowan Zellers, Ari Holtzman, Matthew Peters, Roozbeh Mottaghi, Aniruddha Kembhavi, Ali Farhadi, Yejin Choi*.

- **[Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents](https://arxiv.org/abs/2302.01560)**, 2023.02 ![img](https://img.shields.io/badge/-Prompt%20Chaining,%20Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Formal%20Language,%20Natural%20Language-lightgrey)

  *Zihao Wang, Shaofei Cai, Anji Liu, Xiaojian Ma, Yitao Liang*.

- **[ProgPrompt: Generating Situated Robot Task Plans using Large Language Models](https://arxiv.org/abs/2209.11302)**, 2022.09 ![img](https://img.shields.io/badge/-ProgPrompt-blue) ![img](https://img.shields.io/badge/-Elicitive%20Prompting,%20Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Ishika Singh, Valts Blukis, Arsalan Mousavian, Ankit Goyal, Danfei Xu, Jonathan Tremblay, Dieter Fox, Jesse Thomason, Animesh Garg*.

- **[Plan,Eliminate,and Track-Language Models are Good Teachers for Embodied Agents.](https://arxiv.org/abs/2305.02412)**, 2023.05 ![img](https://img.shields.io/badge/-Standard%20Prompting,%20Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Yue Wu, So Yeon Min, Yonatan Bisk, Ruslan Salakhutdinov, Amos Azaria, Yuanzhi Li, Tom Mitchell, Shrimai Prabhumoye*.

- **[Collaborating with language models for embodied reasoning](https://arxiv.org/abs/2302.00763)**, 2023.02 ![img](https://img.shields.io/badge/Planner--Actor--Reporter-blue)![img](https://img.shields.io/badge/-Reinforcement%20Learning,%20Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Ishita Dasgupta, Christine Kaeser-Chen, Kenneth Marino, Arun Ahuja, Sheila Babayan, Felix Hill, Rob Fergus*.

- **[Open-World Object Manipulation using Pre-trained Vision-Language Models](https://arxiv.org/abs/2303.00905)**, 2023.03 ![img](https://img.shields.io/badge/-MOO-blue)

  *Austin Stone, Ted Xiao, Yao Lu, Keerthana Gopalakrishnan, Kuang-Huei Lee, Quan Vuong, Paul Wohlhart, Brianna Zitkovich, Fei Xia, Chelsea Finn, Karol Hausman*.

- **[Mind's Eye: Grounded Language Model Reasoning through Simulation](https://arxiv.org/abs/2210.05359)**, 2022.10 ![img](https://img.shields.io/badge/-Elicitive%20Prompting-orange) ![img](https://img.shields.io/badge/-Formal%20Language-lightgrey)

  *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai*.

- **[Guiding Pretraining in Reinforcement Learning with Large Language Models](https://arxiv.org/abs/2302.06692)**, 2023.02 ![img](https://img.shields.io/badge/-ELLM-blue) ![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey)

  *Yuqing Du, Olivia Watkins, Zihan Wang, Cédric Colas, Trevor Darrell, Pieter Abbeel, Abhishek Gupta, Jacob Andreas*.

- **[Grounding Large Language Models in Interactive Environments with Online Reinforcement Learning](https://arxiv.org/abs/2302.02662)**, 2023.02 ![img](https://img.shields.io/badge/-GLAM-blue)![img](https://img.shields.io/badge/-Reinforcement%20Learning-orange) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Affordance%20Grounding-green)

  *Thomas Carta, Clément Romac, Thomas Wolf, Sylvain Lamprier, Olivier Sigaud, Pierre-Yves Oudeyer*.

- **[Don't Generate, Discriminate: A Proposal for Grounding Language Models to Real-World Environments](https://arxiv.org/abs/2212.09736)**, 2022.12 ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange)

  *Yu Gu, Xiang Deng, Yu Su*.


### 👍Evaluation
- **[Evaluating Human-Language Model Interaction](https://arxiv.org/pdf/2212.09746.pdf)**, 2022.12 ![img](https://img.shields.io/badge/-HALIE-blue) ![img](https://img.shields.io/badge/Human--LM%20Interaction-green)

  *Mina Lee, Megha Srivastava, Amelia Hardy, John Thickstun, Esin Durmus, Ashwin Paranjape, Ines Gerard-Ursin, Xiang Lisa Li, Faisal Ladhak, Frieda Rong, Rose E. Wang, Minae Kwon, Joon Sung Park, Hancheng Cao, Tony Lee, Rishi Bommasani, Michael Bernstein, Percy Lia*.

- **[ReCEval: Evaluating Reasoning Chains via Correctness and Informativeness](https://arxiv.org/pdf/2304.10703.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-ReCEval-blue) ![img](https://img.shields.io/badge/-Prompt%20Chaining-orange) ![img](https://img.shields.io/badge/CoT-green)

  *Archiki Prasad, Swarnadeep Saha, Xiang Zhou, Mohit Bansa*.

- **[Evaluating Verifiability in Generative Search Engines](https://arxiv.org/pdf/2304.09848.pdf)**, 2023.04 

  *Liu, Nelson F., Zhang, Tianyi, Liang, Percy Lian*.

- **[Multi-Party Chat: Conversational Agents in Group Settings with Humans and Models](https://arxiv.org/pdf/2304.13835.pdf)**, 2023.04 ![img](https://img.shields.io/badge/-Multi--Party%20Chat-blue) ![img](https://img.shields.io/badge/Communicative%20Agents-green)

  *Jimmy Wei, Kurt Shuster, Arthur Szlam, Jason Weston, Jack Urbanek, Mojtaba Komeili*.

- **[Behavior-1k: A benchmark for embodied ai with 1,000 everyday activities and realistic simulation](https://proceedings.mlr.press/v205/li23a/li23a.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-Behavior--1k-blue) ![img](https://img.shields.io/badge/Embodied%20AI-green)

  *Chengshu Li, Ruohan Zhang, Josiah Wong, Cem Gokmen, Sanjana Srivastava, Roberto Martín-Martín, Chen Wang, Gabrael Levine, Michael Lingelbach, Jiankai Sun, Mona Anvari, Minjune Hwang, Manasi Sharma, Arman Aydin, Dhruva Bansal, Samuel Hunter, Kyu-Young Kim, Alan Lou, Caleb R Matthews, Ivan Villa-Renteria, Jerry Huayang Tang, Claire Tang, Fei Xia, Silvio Savarese, Hyowon Gweon, Karen Liu, Jiajun Wu, Li Fei-Fei*.

- **[ORBIT: A Unified Simulation Framework for Interactive Robot Learning Environments](https://arxiv.org/pdf/2301.04195.pdf)**, 2023.01 ![img](https://img.shields.io/badge/-ORBIT-blue) ![img](https://img.shields.io/badge/Embodied%20AI-green)

  *Mayank Mittal, Calvin Yu, Qinxi Yu, Jingzhou Liu, Nikita Rudin, David Hoeller, Jia Lin Yuan, Pooria Poorsarvi Tehrani, Ritvik Singh, Yunrong Guo, Hammad Mazhar, Ajay Mandlekar, Buck Babich, Gavriel State, Marco Hutter, Animesh Garg*.

- **[Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering](https://arxiv.org/pdf/2209.09513.pdf)**, 2022.09 ![img](https://img.shields.io/badge/-ScienceQA-blue) ![img](https://img.shields.io/badge/CoT-green)

  *Pan Lu, Swaroop Mishra, Tony Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, Ashwin Kalyan*.

- **[Alexa Arena: A User-Centric Interactive Platform for Embodied AI](https://arxiv.org/pdf/2303.01586.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-Alexa%20Arena-blue) ![img](https://img.shields.io/badge/Embodied%20AI-green)

  *Qiaozi Gao, Govind Thattai, Xiaofeng Gao, Suhaila Shakiah, Shreyas Pansare, Vasu Sharma, Gaurav Sukhatme, Hangjie Shi, Bofei Yang, Desheng Zheng, Lucy Hu, Karthika Arumugam, Shui Hu, Matthew Wen, Dinakar Guthy, Cadence Chung, Rohan Khanna, Osman Ipek, Leslie Ball, Kate Bland, Heather Rocker, Yadunandana Rao, Michael Johnston, Reza Ghanadan, Arindam Mandal, Dilek Hakkani Tur, Prem Natarajan*.

- **[CB2: Collaborative Natural Language Interaction Research Platform](https://arxiv.org/pdf/2303.08127.pdf)**, 2023.03 ![img](https://img.shields.io/badge/-CB2-blue) ![img](https://img.shields.io/badge/-Natural%20Language-lightgrey) ![img](https://img.shields.io/badge/Collaborative%20Behavior-green)

  *Jacob Sharf, Mustafa Omer Gul, Yoav Artzi*.

- **[An AI Dungeon Master’s Guide: Learning to Converse and Guide with Intents and Theory-of-Mind in Dungeons and Dragons](https://arxiv.org/pdf/2212.10060.pdf)**, 2022.12 ![img](https://img.shields.io/badge/Game,%20Theory--of--Mind-green)

  *Pei Zhou, Andrew Zhu, Jennifer Hu, Jay Pujara, Xiang Ren, Chris Callison-Burch, Yejin Choi, Prithviraj Ammanabrolu*.



### 🎨Application



## Related Projects

- **[ToolLearningPapers](https://github.com/thunlp/)**
- **[BMTools](https://github.com/OpenBMB/BMTools)**
- **[AgentVerse](https://github.com/OpenBMB/AgentVerse)**
- **[ChatArena](https://github.com/chatarena/chatarena)**
- **[ChatGPT Plugins](https://platform.openai.com/docs/plugins/)**
- **[LangChain](https://github.com/hwchase17/langchain)**
- **[AutoGPT](https://github.com/Significant-Gravitas/Auto-GPT)**
- **[BabyAGI](https://github.com/yoheinakajima/babyagi)**



## Contribution

### Contributors

[   ![img](https://contrib.rocks/image?repo=InteractiveNLP-Team/awesome-InteractiveNLP-papers) ](https://github.com/InteractiveNLP-Team/awesome-InteractiveNLP-papers/graphs/contributors)

### Contributing to this paper list

- There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=InteractiveNLP-Team/awesome-InteractiveNLP-papers&type=Date)](https://star-history.com/#InteractiveNLP-Team/awesome-InteractiveNLP-papers&Date)

## Citation
If you find this paper list helpful, please consider citing our paper:

```latex
@article{wang2023interactive,
  title={Interactive Natural Language Processing},
  author={Wang, Zekun and Zhang, Ge and Yang, Kexin and Shi, Ning and Zhou, Wangchunshu and Hao, Shaochun and Xiong, Guangzheng and Li, Yizhi and Sim, Mong Yuan and Chen, Xiuying and others},
  journal={arXiv preprint arXiv:2305.13246},
  year={2023}
}
```
