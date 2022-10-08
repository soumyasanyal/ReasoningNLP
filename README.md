# ReasoningNLP
Paper list on reasoning in NLP.

## Languague Model Reasoning
1. **Show Your Work: Scratchpads for Intermediate Computation with Language Models** arXiv (2021)

   *Maxwell Nye, Anders Johan Andreassen, Guy Gur-Ari, Henryk Michalewski, Jacob Austin, David Bieber, David Dohan, Aitor Lewkowycz, Maarten Bosma, David Luan, Charles Sutton, Augustus Odena* [[pdf](https://arxiv.org/pdf/2112.00114.pdf)]

2. **Chain of Thought Prompting Elicits Reasoning in Large Language Models** arXiv (2022)

   *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou* [[pdf](https://arxiv.org/pdf/2201.11903.pdf)] [[project](https://github.com/jasonwei20/chain-of-thought-prompting)]

3. **STaR: Bootstrapping Reasoning With Reasoning** arXiv (2022)

   *Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman* [[pdf](https://arxiv.org/pdf/2203.14465.pdf)]

4. **Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning** arXiv (2022)

   *Antonia Creswell, Murray Shanahan, Irina Higgins* [[pdf](https://arxiv.org/pdf/2205.09712.pdf)]

5. **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models** arXiv (2022)

   *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Olivier Bousquet, Quoc Le, Ed Chi* [[pdf](https://arxiv.org/pdf/2205.10625.pdf)]

6. **Large Language Models are Zero-Shot Reasoners** arXiv (2022)

   *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa* [[pdf](https://arxiv.org/pdf/2205.11916.pdf)] [[project](https://github.com/kojima-takeshi188/zero_shot_cot)]

7. **Faithful Reasoning Using Large Language Models** arXiv (2022)

   *Antonia Creswell, Murray Shanahan* [[pdf](https://arxiv.org/pdf/2208.14271.pdf)]


### Effect & Concern
1. **Language models show human-like content effects on reasoning** arXiv (2022)

   *Ishita Dasgupta, Andrew K. Lampinen, Stephanie C. Y. Chan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, Felix Hill* [[pdf](https://arxiv.org/pdf/2207.07051.pdf)]

2. **On the Paradox of Learning to Reason from Data** arXiv (2022)

    *Honghua Zhang, Liunian Harold Li, Tao Meng, Kai-Wei Chang, Guy Van den Broeck* [[pdf](https://arxiv.org/pdf/2205.11502.pdf)] [[project](https://github.com/joshuacnf/paradox-learning2reason)]













## Knowledge Graph Reasoning
**Knowledge graph completion** task aims to complete the graph, while **multi-hop reasoning over KG** is the task querying in incomplete graphs, both of which require reasoning over knowledge graphs. **Temporal knowledge graph reasoning** aims to predict links in future with the past quadruples. 

### Knowledge Graph Completion
1. **Collaborative Policy Learning for Open Knowledge Graph Reasoning** EMNLP (2019)

   *Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1269.pdf)] [[project](https://github.com/shanzhenren/CPL)]


2. **DIVINE: A Generative Adversarial Imitation Learning Framework for Knowledge Graph Reasoning** EMNLP (2019)

   *Ruiping Li, Xiang Cheng* [[pdf](https://aclanthology.org/D19-1266.pdf)] [[project](https://github.com/BUPT-Data-Intelligence-Lab/DIVINE)]

3. **Learning Collaborative Agents with Rule Guidance for Knowledge Graph Reasoning** EMNLP (2020)

   *Deren Lei, Gangrong Jiang, Xiaotao Gu, Kexuan Sun, Yuning Mao, Xiang Ren* [[pdf](https://aclanthology.org/2020.emnlp-main.688.pdf)] [[project](https://github.com/derenlei/KG-RuleGuider)]

4. **Incorporating Graph Attention Mechanism into Knowledge Graph Reasoning Based on Deep Reinforcement Learning** EMNLP (2019)

   *Heng Wang, Shuangyin Li, Rong Pan, Mingzhi Mao* [[pdf](https://aclanthology.org/D19-1264.pdf)] [[project](https://aclanthology.org/attachments/D19-1264.Attachment.zip)]

5. **Dynamically Pruned Message Passing Networks for Large-scale Knowledge Graph Reasoning** ICLR Poster (2020)

   *Xiaoran Xu, Wei Feng, Yunsheng Jiang, Xiaohui Xie, Zhiqing Sun, Zhi-Hong Deng* [[pdf](https://openreview.net/pdf?id=rkeuAhVKvB)] [[project](https://github.com/netpaladinx/DPMPN)]

6. **Inductive Relation Prediction by Subgraph Reasoning** ICML (2020)

   *Komal K. Teru, Etienne G. Denis, William L. Hamilton* [[pdf](https://proceedings.mlr.press/v119/teru20a/teru20a.pdf)] [[project](https://github.com/kkteru/grail)]

7. **Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations** EMNLP (2019)

   *Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu* [[pdf](https://aclanthology.org/D19-1334.pdf)] [[project](https://github.com/THU-KEG/MetaKGR)]

8. **Dynamic Anticipation and Completion for Multi-Hop Reasoning over Sparse Knowledge Graph** EMNLP (2020)

   *Xin Lv, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu, Wei Zhang, Yichi Zhang, Hao Kong, Suhui Wu* [[pdf](https://aclanthology.org/2020.emnlp-main.459.pdf)] [[project](https://github.com/THU-KEG/DacKGR)]

9. **UniKER: A Unified Framework for Combining Embedding and Definite Horn Rule Reasoning for Knowledge Graph Inference** EMNLP (2021)

   *Kewei Cheng, Ziqing Yang, Ming Zhang, Yizhou Sun* [[pdf](https://aclanthology.org/2021.emnlp-main.769.pdf)]

10. **Is Multi-Hop Reasoning Really Explainable? Towards Benchmarking Reasoning Interpretability** EMNLP (2021)
   
      *Xin Lv, Yixin Cao, Lei Hou, Juanzi Li, Zhiyuan Liu, Yichi Zhang, Zelin Dai* [[pdf](https://aclanthology.org/2021.emnlp-main.700.pdf)] [[project](https://github.com/THU-KEG/BIMR)]

11. **GMH: A General Multi-hop Reasoning Model for KG Completion** EMNLP (2021)

      *Yao Zhang, Hongru Liang, Adam Jatowt, Wenqiang Lei, Xin Wei, Ning Jiang, Zhenglu Yang* [[pdf](https://aclanthology.org/2021.emnlp-main.276.pdf)]

12. **Neural-Symbolic Commonsense Reasoner with Relation Predictors** ACL (2021)
   
      *Farhad Moghimifar, Lizhen Qu, Yue Zhuo, Gholamreza Haffari, Mahsa Baktashmotlagh* [[pdf](https://aclanthology.org/2021.acl-short.100.pdf)] [[project](https://github.com/farhadmfar/commonsense_reasoner)]


### Multi-Hop Reasoning over KG
1. **Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings** ICLR Poster (2020)

   *Hongyu Ren, Weihua Hu, Jure Leskovec* [[pdf](https://openreview.net/pdf?id=BJgr4kSFDS)] [[project](http://snap.stanford.edu/query2box)]

2. **Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs** NIPS (2020)

   *Hongyu Ren, Jure Leskovec* [[pdf](https://papers.nips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf)] [[project](http://snap.stanford.edu/betae)]

3. **Probabilistic Entity Representation Model for Reasoning over Knowledge Graphs** NIPS (2021)

   *Nurendra Choudhary, Nikhil Rao, Sumeet Katariya, Karthik Subbian, Chandan K. Reddy* [[pdf](https://papers.nips.cc/paper/2021/file/c4d2ce3f3ebb5393a77c33c0cd95dc93-Paper.pdf)] [[project](https://github.com/Akirato/PERM-GaussianKG)]

4. **ConE: Cone Embeddings for Multi-Hop Reasoning over Knowledge Graphs** NIPS (2021)

   *Zhanqiu Zhang, Jie Wang, Jiajun Chen, Shuiwang Ji, Feng Wu* [[pdf](https://papers.nips.cc/paper/2021/file/a0160709701140704575d499c997b6ca-Paper.pdf)] [[project](https://github.com/MIRALab-USTC/QE-ConE)]

5. **Complex Query Answering with Neural Link Predictors** ICLR Oral (2021)

   *Erik Arakelyan, Daniel Daza, Pasquale Minervini, Michael Cochez* [[pdf](https://openreview.net/pdf?id=Mos9F9kDwkz)] [[project](https://github.com/uclnlp/cqd)]


### Temporal Knowledge Graph Reasoning
1. **Explainable Subgraph Reasoning for Forecasting on Temporal Knowledge Graphs** ICLR Poster (2021)

   *Zhen Han, Peng Chen, Yunpu Ma, Volker Tresp* [[pdf](https://openreview.net/pdf?id=pGIHq1m7PU)] [[project](https://github.com/TemporalKGTeam/xERTE)]

2. **Search from History and Reason for Future: Two-stage Reasoning on Temporal Knowledge Graphs** ACL (2021)

   *Zixuan Li, Xiaolong Jin, Saiping Guan, Wei Li, Jiafeng Guo, Yuanzhuo Wang, Xueqi Cheng* [[pdf](https://aclanthology.org/2021.acl-long.365.pdf)]

3. **Complex Evolutional Pattern Learning for Temporal Knowledge Graph Reasoning** ACL (2022)

   *Zixuan Li, Saiping Guan, Xiaolong Jin, Weihua Peng, Yajuan Lyu, Yong Zhu, Long Bai, Wei Li, Jiafeng Guo, Xueqi Cheng* [[pdf](https://aclanthology.org/2022.acl-short.32.pdf)] [[project](https://github.com/Lee-zix/CEN)]



### Others
1. **Quantum Embedding of Knowledge for Reasoning** NIPS (2019)

   *Dinesh Garg, Shajith Ikbal, Santosh K. Srivastava, Harit Vishwakarma, Hima P. Karanam, L. Venkata Subramaniam* [[pdf](https://papers.nips.cc/paper/2019/file/cb12d7f933e7d102c52231bf62b8a678-Paper.pdf)] [[project](https://github.com/IBM/e2r)]

2. **Scalable Neural Methods for Reasoning With a Symbolic Knowledge Base** ICLR Poster (2020)

   *William W. Cohen, Haitian Sun, R. Alex Hofer, Matthew Siegler* [[pdf](https://openreview.net/pdf?id=BJlguT4YPr)]

3. **Probabilistic Logic Neural Networks for Reasoning** NIPS (2019)

   *Meng Qu, Jian Tang* [[pdf](https://papers.nips.cc/paper/2019/file/13e5ebb0fa112fe1b31a1067962d74a7-Paper.pdf)]

4. **RNNLogic: Learning Logic Rules for Reasoning on Knowledge Graphs** ICLR Poster (2021)

   *Meng Qu, Junkun Chen, Louis-Pascal A. C. Xhonneux, Yoshua Bengio, Jian Tang* [[pdf](https://openreview.net/pdf?id=tGZu6DlbreV)] [[project](https://github.com/DeepGraphLearning/RNNLogic)]

5. **Efficient Probabilistic Logic Reasoning with Graph Neural Networks** ICLR Poster (2020)

   *Yuyu Zhang, Xinshi Chen, Yuan Yang, Arun Ramamurthy, Bo Li, Yuan Qi, Le Song* [[pdf](https://openreview.net/pdf?id=rJg76kStwH)]

6. **Probabilistic Box Embeddings for Uncertain Knowledge Graph Reasoning** NAACL (2021)

   *Xuelu Chen, Michael Boratko, Muhao Chen, Shib Sankar Dasgupta, Xiang Lorraine Li, Andrew McCallum* [[pdf](https://aclanthology.org/2021.naacl-main.68.pdf)] [[project](https://github.com/stasl0217/beurre)]













## Language Rulebase Reasoning
Facts and rules are explicitly provided as natural language texts, and Transformers are used as soft reasoners over them. 

1. **Transformers as Soft Reasoners over Language** IJCAI (2020)

   *Peter Clark, Oyvind Tafjord, Kyle Richardson* [[pdf](https://www.ijcai.org/proceedings/2020/0537.pdf)] [[project](https://allenai.org/data/ruletaker)]

2. **PRover: Proof Generation for Interpretable Reasoning over Rules** EMNLP (2020)

   *Swarnadeep Saha, Sayan Ghosh, Shashank Srivastava, Mohit Bansal* [[pdf](https://aclanthology.org/2020.emnlp-main.9.pdf)] [[project](https://github.com/swarnaHub/PRover)]

3. **multiPRover: Generating Multiple Proofs for Improved Interpretability in Rule Reasoning** NAACL (2021)

   *Swarnadeep Saha, Prateek Yadav, Mohit Bansal* [[pdf](https://aclanthology.org/2021.naacl-main.287.pdf)] [[project](https://github.com/swarnaHub/multiPRover)]

4. **ProofWriter: Generating Implications, Proofs, and Abductive Statements over Natural Language** ACL findings (2021)

   *Oyvind Tafjord, Bhavana Dalvi, Peter Clark* [[pdf](https://aclanthology.org/2021.findings-acl.317.pdf)] [[project](https://allenai.org/data/proofwriter)]

5. **Interpretable Proof Generation via Iterative Backward Reasoning** NAACL (2022)

   *Hanhao Qu, Yu Cao, Jun Gao, Liang Ding, Ruifeng Xu* [[pdf](https://aclanthology.org/2022.naacl-main.216.pdf)] [[project](https://github.com/find-knowledge/IBR)]

6. **FaiRR: Faithful and Robust Deductive Reasoning over Natural Language** ACL (2022)

   *Soumya Sanyal, Harman Singh, Xiang Ren* [[pdf](https://aclanthology.org/2022.acl-long.77.pdf)] [[project](https://github.com/INK-USC/FaiRR)]

7. **Explainable Multi-hop Verbal Reasoning Through Internal Monologue** NAACL (2021)

   *Zhengzhong Liang, Steven Bethard, Mihai Surdeanu* [[pdf](https://aclanthology.org/2021.naacl-main.97.pdf)] [[project](https://github.com/clulab/releases/tree/master/naacl2021-evr)]














## Mathematical Reasoning
Mathematics is a game of symbols and symbol manipulation rules full of reasoning, which makes it a natural problem to test AI's ability of reasoning. **Math word problem** aims to answer mathematical questions described by natural language text. **Automated theorem proving** focuses on theoretical proving. **Numerical reasoning** aims to solve problems that requires numerical calculation (e.g. addition, sorting and counting) over numerical evidence scattered in text or tables. 

### Math Word Problem
1. **Semantically-Aligned Equation Generation for Solving and Reasoning Math Word Problems** NAACL (2019)

   *Ting-Rui Chiang, Yun-Nung Chen* [[pdf](https://aclanthology.org/N19-1272.pdf)] [[project](https://github/MiuLab/E2EMathSolver)]

2. **Measuring and Improving BERT's Mathematical Abilities by Predicting the Order of Reasoning** ACL (2021)

   *Piotr Piekos, Mateusz Malinowski, Henryk Michalewski* [[pdf](https://aclanthology.org/2021.acl-short.49.pdf)]

3. **Learning to Reason Deductively: Math Word Problem Solving as Complex Relation Extraction** ACL (2022)

   *Zhanming Jie, Jierui Li, Wei Lu* [[pdf](https://aclanthology.org/2022.acl-long.410.pdf)] [[project](https://github.com/allanj/Deductive-MWP)]


### Automated Theorem Proving
1. **Mathematical Reasoning via Self-supervised Skip-tree Training** ICLR Spotlight (2021)

   *Markus Norman Rabe, Dennis Lee, Kshitij Bansal, Christian Szegedy* [[pdf](https://openreview.net/pdf?id=YmqAnY0CMEy)]

2. **LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning** ICML (2021)

   *Yuhuai Wu, Markus N. Rabe, Wenda Li, Jimmy Ba, Roger B. Grosse, Christian Szegedy* [[pdf](http://proceedings.mlr.press/v139/wu21c/wu21c.pdf)] [[project](https://github.com/tonywu95/LIME)]



### Numerical Reasoning
1. **A Multi-Type Multi-Span Network for Reading Comprehension that Requires Discrete Reasoning** EMNLP (2019)

   *Minghao Hu, Yuxing Peng, Zhen Huang, Dongsheng Li* [[pdf](https://aclanthology.org/D19-1170.pdf)] [[project](https://github.com/huminghao16/MTMSN)]

2. **NumNet: Machine Reading Comprehension with Numerical Reasoning** EMNLP (2019)

   *Qiu Ran, Yankai Lin, Peng Li, Jie Zhou, Zhiyuan Liu* [[pdf](https://aclanthology.org/D19-1251.pdf)] [[project](https://github.com/ranqiu92/NumNet)]

3. **Question Directed Graph Attention Network for Numerical Reasoning over Text** EMNLP (2020)

   *Kunlong Chen, Weidi Xu, Xingyi Cheng, Zou Xiaochuan, Yuyu Zhang, Le Song, Taifeng Wang, Yuan Qi, Wei Chu* [[pdf](https://aclanthology.org/2020.emnlp-main.549.pdf)]

4. **Injecting Numerical Reasoning Skills into Language Models** ACL (2020)

   *Mor Geva, Ankit Gupta, Jonathan Berant* [[pdf](https://aclanthology.org/2020.acl-main.89.pdf)] [[project](https://github.com/ag1988/injecting_numeracy)]

5. **Neural Module Networks for Reasoning over Text** ICLR Poster (2020)

   *Nitish Gupta, Kevin Lin, Dan Roth, Sameer Singh, Matt Gardner* [[pdf](https://openreview.net/pdf?id=SygWvAVFPr)] [[project](http://cogcomp.org/page/publication_view/899)]

6. **OPERA: Operation-Pivoted Discrete Reasoning over Text** NAACL (2022)

   *Yongwei Zhou, Junwei Bao, Chaoqun Duan, Haipeng Sun, Jiahui Liang, Yifan Wang, Jing Zhao, Youzheng Wu, Xiaodong He, Tiejun Zhao* [[pdf](https://aclanthology.org/2022.naacl-main.119.pdf)] [[project](https://github.com/JD-AI-Research-NLP/OPERA)]

7. **Turning Tables: Generating Examples from Semi-structured Tables for Endowing Language Models with Reasoning Skills** ACL (2022)

   *Ori Yoran, Alon Talmor, Jonathan Berant* [[pdf](https://aclanthology.org/2022.acl-long.416.pdf)] [[project](https://github.com/oriyor/turning_tables)]

8. **FORTAP: Using Formulas for Numerical-Reasoning-Aware Table Pretraining** ACL (2022)

   *Zhoujun Cheng, Haoyu Dong, Ran Jia, Pengfei Wu, Shi Han, Fan Cheng, Dongmei Zhang* [[pdf](https://aclanthology.org/2022.acl-long.82.pdf)] [[project](https://github.com/microsoft/TUTA_table_understanding)]

9. **Incorporating External Knowledge to Enhance Tabular Reasoning** NAACL (2021)

   *J. Neeraja, Vivek Gupta, Vivek Srikumar* [[pdf](https://aclanthology.org/2021.naacl-main.224.pdf)] [[project](https://github.com/utahnlp/knowledge_infotabs)]

10. **Right for the Right Reason: Evidence Extraction for Trustworthy Tabular Reasoning** ACL (2022)

      *Vivek Gupta, Shuo Zhang, Alakananda Vempala, Yujie He, Temma Choji, Vivek Srikumar* [[pdf](https://aclanthology.org/2022.acl-long.231.pdf)] [[project](https://tabevidence.github.io/)]

11. **Numerical reasoning in machine reading comprehension tasks: are we there yet?** EMNLP (2021)

      *Hadeel Al-Negheimish, Pranava Madhyastha, Alessandra Russo* [[pdf](https://aclanthology.org/2021.emnlp-main.759.pdf)]


### Benchmarks & Datasets
1. **Analysing Mathematical Reasoning Abilities of Neural Models** ICLR Poster (2019)

   *David Saxton, Edward Grefenstette, Felix Hill, Pushmeet Kohli* [[pdf](https://openreview.net/pdf?id=H1gR5iR5FX)] [[project](https://github.com/deepmind/mathematics_dataset)]

2. **HOList: An Environment for Machine Learning of Higher-Order Theorem Proving** ICML (2019)

   *Kshitij Bansal, Sarah M. Loos, Markus N. Rabe, Christian Szegedy, Stewart Wilcox* [[pdf](http://proceedings.mlr.press/v97/bansal19a/bansal19a.pdf)] [[project](http://deephol.org/t)]

3. **IsarStep: a Benchmark for High-level Mathematical Reasoning** ICLR Poster (2021)

   *Wenda Li, Lei Yu, Yuhuai Wu, Lawrence C. Paulson* [[pdf](https://openreview.net/pdf?id=Pzj6fzU6wkj)] [[project](https://github.com/Wenda302/IsarStep)]

4. **DROP: A Reading Comprehension Benchmark Requiring Discrete Reasoning Over Paragraphs** EMNLP (2019)

   *Dheeru Dua, Yizhong Wang, Pradeep Dasigi, Gabriel Stanovsky, Sameer Singh, Matt Gardner* [[pdf](https://aclanthology.org/N19-1246.pdf)] [[project](https://allennlp.org/drop)]

5. **Towards Table-to-Text Generation with Numerical Reasoning** ACL (2021)

   *Lya Hulliyyatus Suadaa, Hidetaka Kamigaito, Kotaro Funakoshi, Manabu Okumura, Hiroya Takamura* [[pdf](https://aclanthology.org/2021.acl-long.115.pdf)] [[project](https://github.com/titech-nlp/numeric-nlg)]

6. **SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables** NIPS (2021)

   *Nafise Sadat Moosavi, Andreas Rücklé, Dan Roth, Iryna Gurevych* [[pdf](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/149e9677a5989fd342ae44213df68868-Paper-round2.pdf)] [[project](https://github.com/UKPLab/SciGen)]

7. **MULTIHIERTT: Numerical Reasoning over Multi Hierarchical Tabular and Textual Data** ACL (2022)

   *Yilun Zhao, Yunxiang Li, Chenying Li, Rui Zhang* [[pdf](https://aclanthology.org/2022.acl-long.454.pdf)] [[project](https://github.com/psunlpgroup/MultiHiertt)]

8. **FINQA: A Dataset of Numerical Reasoning over Financial Data** EMNLP (2021)

   *Zhiyu Chen, Wenhu Chen, Charese Smiley, Sameena Shah, Iana Borova, Dylan Langdon, Reema Moussa, Matt Beane, Ting-Hao Huang, Bryan R. Routledge, William Yang Wang* [[pdf](https://aclanthology.org/2021.emnlp-main.300.pdf)] [[project](https://github.com/czyssrs/FinQA)]

9. **NUMGLUE: A Suite of Fundamental yet Challenging Mathematical Reasoning Tasks** ACL (2022)

   *Swaroop Mishra, Arindam Mitra, Neeraj Varshney, Bhavdeep Singh Sachdeva, Peter Clark, Chitta Baral, Ashwin Kalyan* [[pdf](https://aclanthology.org/2022.acl-long.246.pdf)] [[project](https://allenai.org/data/numglue)]

10. **Inter-GPS: Interpretable Geometry Problem Solving with Formal Language and Symbolic Reasoning** ACL (2021)

      *Pan Lu, Ran Gong, Shibiao Jiang, Liang Qiu, Siyuan Huang, Xiaodan Liang, Song-Chun Zhu* [[pdf](https://aclanthology.org/2021.acl-long.528.pdf)] [[project](https://lupantech.github.io/inter-gps)]


### Others
1. **Mathematical Reasoning in Latent Space** ICLR Oral (2020)

   *Dennis Lee, Christian Szegedy, Markus N. Rabe, Sarah M. Loos, Kshitij Bansal* [[pdf](https://openreview.net/pdf?id=Ske31kBtPr)]

2. **GraphMR: Graph Neural Network for Mathematical Reasoning** ACL (2021)

      *Weijie Feng, Binbin Liu, Dongpeng Xu, Qilong Zheng, Yun Xu* [[pdf](https://aclanthology.org/2021.emnlp-main.273.pdf)] [[project](https://github.com/nhpcc502/GraphMR)]













## Multi-hop Question Answering

### Distractor setting

1. **Answering while Summarizing: Multi-task Learning for Multi-hop QA with Evidence Extraction** ACL (2019)

   *Kosuke Nishida, Kyosuke Nishida, Masaaki Nagata, Atsushi Otsuka, Itsumi Saito, Hisako Asano, Junji Tomita* [[pdf](https://aclanthology.org/P19-1225.pdf)]

2. **Multi-hop Reading Comprehension through Question Decomposition and Rescoring** ACL (2019)

   *Sewon Min, Victor Zhong, Luke Zettlemoyer, Hannaneh Hajishirzi* [[pdf](https://aclanthology.org/P19-1613.pdf)] [[project](https://github.com/shmsw25/DecompRC)]

3. **Question Answering by Reasoning Across Documents with Graph Convolutional Networks** NAACL (2019)

   *Nicola De Cao, Wilker Aziz, Ivan Titov* [[pdf](https://aclanthology.org/N19-1240.pdf)]

4. **BAG: Bi-directional Attention Entity Graph Convolutional Network for Multi-hop Reasoning Question Answering** NAACL (2019)

   *Yu Cao, Meng Fang, Dacheng Tao* [[pdf](https://aclanthology.org/N19-1032.pdf)] [[project](https://github.com/caoyu1991/BAG)]

5. **Dynamically Fused Graph Network for Multi-hop Reasoning** ACL (2019)

   *Lin Qiu, Yunxuan Xiao, Yanru Qu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu* [[pdf](https://aclanthology.org/P19-1617.pdf)] [[project](https://github.com/woshiyyya/DFGN-pytorch)]

6. **Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs** ACL (2019)

   *Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou* [[pdf](https://aclanthology.org/P19-1260.pdf)]

7. **SRLGRN: Semantic Role Labeling Graph Reasoning Network** EMNLP (2020)

   *Chen Zheng, Parisa Kordjamshidi* [[pdf](https://aclanthology.org/2020.emnlp-main.714.pdf)]

8. **Breadth First Reasoning Graph for Multi-hop Question Answering** NAACL (2021)

   *Yongjie Huang, Meng Yang* [[pdf](https://aclanthology.org/2021.naacl-main.464.pdf)]

9. **Self-Assembling Modular Networks for Interpretable Multi-Hop Reasoning** EMNLP (2019)

   *Yichen Jiang, Mohit Bansal* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1455.pdf)] [[project](https://github.com/jiangycTarheel/NMN-MultiHopQA)]

10. **NLProlog: Reasoning with Weak Unification for Question Answering in Natural Language** ACL (2019)

   *Leon Weber, Pasquale Minervini, Jannes Münchmeyer, Ulf Leser, Tim Rocktäschel* [[pdf](https://aclanthology.org/P19-1618.pdf)] [[project](https://github.com/leonweber/nlprolog)]

11. **Deep Inductive Logic Reasoning for Multi-Hop Reading Comprehension** ACL (2022)

   *Wenya Wang, Sinno Jialin Pan* [[pdf](https://aclanthology.org/2022.acl-long.343.pdf)]


### Open-domain setting

1. **Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering** ICLR (2020)

   *Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong* [[pdf](https://openreview.net/pdf?id=SJgVHkrYDH)] [[project](https://github.com/AkariAsai/learning_to_retrieve_reasoning_paths)]

2. **Baleen: Robust Multi-Hop Reasoning at Scale via Condensed Retrieval** NIPS (2021)

   *Omar Khattab, Christopher Potts, Matei A. Zaharia* [[pdf](https://papers.nips.cc/paper/2021/file/e8b1cbd05f6e6a358a81dee52493dd06-Paper.pdf)] [[project](https://github.com/stanford-futuredata/Baleen)]

3. **Multi-Step Reasoning Over Unstructured Text with Beam Dense Retrieval** NAACL (2021)

   *Chen Zhao, Chenyan Xiong, Jordan L. Boyd-Graber, Hal Daumé III* [[pdf](https://aclanthology.org/2021.naacl-main.368.pdf)] [[project](https://github.com/henryzhao5852/BeamDR)]

4. **Differentiable Reasoning over a Virtual Knowledge Base** ICLR (2020)

   *Bhuwan Dhingra, Manzil Zaheer, Vidhisha Balachandran, Graham Neubig, Ruslan Salakhutdinov, William W. Cohen* [[pdf](https://openreview.net/pdf?id=SJxstlHFPH)] [[project](http://www.cs.cmu.edu/~bdhingra/pages/drkit.html)]

5. **Reasoning Over Virtual Knowledge Bases With Open Predicate Relations** ICML (2021)

   *Haitian Sun, Patrick Verga, Bhuwan Dhingra, Ruslan Salakhutdinov, William W. Cohen* [[pdf](https://proceedings.mlr.press/v139/sun21e/sun21e.pdf)]

6. **Low-Resource Generation of Multi-hop Reasoning Questions** ACL (2020)

   *Jianxing Yu, Wei Liu, Shuang Qiu, Qinliang Su, Kai Wang, Xiaojun Quan, Jian Yin* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.acl-main.601.pdf)]


### Rethinking

1. **Avoiding Reasoning Shortcuts: Adversarial Evaluation, Training, and Model Development for Multi-Hop QA** ACL (2019)

   *Yichen Jiang, Mohit Bansal* [[pdf](https://aclanthology.org/P19-1262.pdf)] [[project](https://github.com/jiangycTarheel-zz/Adversarial-MultiHopQA)]

2. **Understanding Dataset Design Choices for Multi-hop Reasoning** NAACL (2019)

   *Jifan Chen, Greg Durrett* [[pdf](https://aclanthology.org/N19-1405.pdf)]

3. **Compositional Questions Do Not Necessitate Multi-hop Reasoning** ACL (2019)

   *Sewon Min, Eric Wallace, Sameer Singh, Matt Gardner, Hannaneh Hajishirzi, Luke Zettlemoyer* [[pdf](https://aclanthology.org/P19-1416.pdf)] [[project](https://github.com/shmsw25/single-hop-rc)]

4. **Is Multihop QA in DiRe Condition? Measuring and Reducing Disconnected Reasoning** EMNLP (2020)

   *Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal* [[pdf](https://aclanthology.org/2020.emnlp-main.712.pdf)] [[project](https://github.com/stonybrooknlp/dire)]


### Question Generation

1. **Low-Resource Generation of Multi-hop Reasoning Questions** ACL (2020)

   *Jianxing Yu, Wei Liu, Shuang Qiu, Qinliang Su, Kai Wang, Xiaojun Quan, Jian Yin* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.acl-main.601.pdf)]

2. **Unsupervised Multi-hop Question Answering by Question Generation** NAACL (2021)

   *Liangming Pan, Wenhu Chen, Wenhan Xiong, Min-Yen Kan, William Yang Wang* [[pdf](https://aclanthology.org/2021.naacl-main.469.pdf)] [[project](https://github.com/teacherpeterpan/Unsupervised-Multi-hop-QA)]

3. **CQG: A Simple and Effective Controlled Generation Framework for Multi-hop Question Generation** ACL (2022)

   *Zichu Fei, Qi Zhang, Tao Gui, Di Liang, Sirui Wang, Wei Wu, Xuanjing Huang* [[pdf](https://aclanthology.org/2022.acl-long.475.pdf)] [[project](https://github.com/sion-zcfei/CQG)]


### Benchmarks & Datasets

1. **Constructing Datasets for Multi-hop Reading Comprehension Across Documents** TACL (2018)

   *Johannes Welbl, Pontus Stenetorp, Sebastian Riedel* [[pdf](https://aclanthology.org/Q18-1021.pdf)] [[project](http://qangaroo.cs.ucl.ac.uk/)]

2. **HOTPOTQA: A Dataset for Diverse, Explainable Multi-hop Question Answering** EMNLP (2018)

   *Zhilin Yang, Peng Qi, Saizheng Zhang, Yoshua Bengio, William Cohen, Ruslan Salakhutdinov, Christopher D. Manning* [[pdf](https://arxiv.org/pdf/1809.09600.pdf)] [[project](https://hotpotqa.github.io/)]

3. **QASC: A Dataset for Question Answering via Sentence Composition** AAAI (2020)

   *Tushar Khot, Peter Clark, Michal Guerquin, Peter Jansen, Ashish Sabharwal* [[pdf](https://arxiv.org/pdf/1910.11473.pdf)] [[project](https://github.com/allenai/qasc)]

4. **Learning to Explain: Datasets and Models for Identifying Valid Reasoning Chains in Multihop Question-Answering** AAAI (2020)

   *Harsh Jhamtani, Peter Clark* [[pdf](http://aclanthology.lst.uni-saarland.de/2020.emnlp-main.10.pdf)] [[project](https://allenai.org/data/eqasc)]

















## Fact Verification

1. **GEAR: Graph-based Evidence Aggregating and Reasoning for Fact Verification** ACL (2019)

   *Jie Zhou, Xu Han, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun* [[pdf](https://aclanthology.org/P19-1085.pdf)] [[project](https://github.com/thunlp/GEAR)]

2. **Topic-Aware Evidence Reasoning and Stance-Aware Aggregation for Fact Verification** ACL (2021)

   *Jiasheng Si, Deyu Zhou, Tongzhe Li, Xingyu Shi, Yulan He* [[pdf](https://aclanthology.org/2021.acl-long.128.pdf)] [[project](https://github.com/jasenchn/TARSA)]

3. **Reasoning Over Semantic-Level Graph for Fact Checking** ACL (2020)

   *Wanjun Zhong, Jingjing Xu, Duyu Tang, Zenan Xu, Nan Duan, Ming Zhou, Jiahai Wang, Jian Yin* [[pdf](https://aclanthology.org/2020.acl-main.549.pdf)]

4. **Exploring Listwise Evidence Reasoning with T5 for Fact Verification** ACL (2021)

   *Kelvin Jiang, Ronak Pradeep, Jimmy Lin* [[pdf](https://aclanthology.org/2021.acl-short.51.pdf)]

5. **Transformer-XH: Multi-Evidence Reasoning with eXtra Hop Attention** ICLR Poster (2020)

   *Chen Zhao, Chenyan Xiong, Corby Rosset, Xia Song, Paul N. Bennett, Saurabh Tiwary* [[pdf](https://openreview.net/pdf?id=r1eIiCNYwS)] [[project](https://aka.ms/transformer-xh)]

6. **Automatic Fake News Detection: Are Models Learning to Reason?** ACL (2021)

   *Casper Hansen, Christian Hansen, Lucas Chaves Lima* [[pdf](https://aclanthology.org/2021.acl-short.12.pdf)] [[project](https://github.com/casperhansen/fake-news-reasoning)]













## Commonsense Reasoning
### Winograd Schema Challenge & Pronoun Disambiguation Problem
1. **Unsupervised Deep Structured Semantic Models for Commonsense Reasoning** NAACL (2019)

   *Shuohang Wang, Sheng Zhang, Yelong Shen, Xiaodong Liu, Jingjing Liu, Jianfeng Gao, Jing Jiang* [[pdf](https://aclanthology.org/N19-1094.pdf)]

2. **Attention Is (not) All You Need for Commonsense Reasoning** EMNLP (2019)

   *Tassilo Klein, Moin Nabi* [[pdf](https://aclanthology.org/P19-1477.pdf)]

3. **How Reasonable are Common-Sense Reasoning Tasks: A Case-Study on the Winograd Schema Challenge and SWAG** EMNLP (2019)

   *Paul Trichelair, Ali Emami, Adam Trischler, Kaheer Suleman, Jackie Chi Kit Cheung* [[pdf](https://aclanthology.org/D19-1335.pdf)] [[project](https://github.com/ptrichel/How-Reasonable-are-Common-Sense-Reasoning-Tasks)]

### Grounded Commonsense Inference
1. **How Reasonable are Common-Sense Reasoning Tasks: A Case-Study on the Winograd Schema Challenge and SWAG** EMNLP (2019)

   *Paul Trichelair, Ali Emami, Adam Trischler, Kaheer Suleman, Jackie Chi Kit Cheung* [[pdf](https://aclanthology.org/D19-1335.pdf)] [[project](https://github.com/ptrichel/How-Reasonable-are-Common-Sense-Reasoning-Tasks)]

### Commonsense Question Answering
1. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** ACL (2019)

   *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher* [[pdf](https://aclanthology.org/P19-1487.pdf)] [[project](https://github.com/salesforce/cos-e)]

### If-Then
1. **Modeling Event Background for If-Then Commonsense Reasoning Using Context-aware Variational Autoencoder** EMNLP (2019)

   *Li Du, Xiao Ding, Ting Liu, Zhongyang Li* [[pdf](https://aclanthology.org/D19-1270.pdf)] [[project](https://github.com/sjcfr/CWVAE)]

### Dataset
1. **Explain Yourself! Leveraging Language Models for Commonsense Reasoning** ACL (2019)

   *Nazneen Fatema Rajani, Bryan McCann, Caiming Xiong, Richard Socher* [[pdf](https://aclanthology.org/P19-1487.pdf)] [[project](https://github.com/salesforce/cos-e)]

2. **SOCIAL IQA: Commonsense Reasoning about Social Interactions** EMNLP (2019)

   *Maarten Sap, Hannah Rashkin, Derek Chen, Ronan Le Bras, Yejin Choi* [[pdf](https://aclanthology.org/D19-1454.pdf)] [[project](https://tinyurl.com/socialiqa)]

3. **Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning** EMNLP (2019)

   *Lifu Huang, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi* [[pdf](http://aclanthology.lst.uni-saarland.de/D19-1243.pdf)] [[project](https://wilburone.github.io/cosmos)]

4. **WIQA: A dataset for "What if..." reasoning over procedural text** EMNLP (2019)

   *Niket Tandon, Bhavana Dalvi, Keisuke Sakaguchi, Peter Clark* [[pdf](https://aclanthology.org/D19-1629.pdf)] [[project](http://data.allenai.org/wiqa)]


## Contributor

Fei Yu
