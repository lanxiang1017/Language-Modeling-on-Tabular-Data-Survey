# Language Modeling on Tabular Data Survey
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)

This is the repository of **Language Modeling on Tabular Data: A Survey of Foundations, Techniques and Evolution** , a comprehensive and systematic survey of the development of language modeling for tabular data. For details, please refer to our paper:

**Language Modeling on Tabular Data: A Survey of Foundations, Techniques and Evolution**  [[Paper](https://arxiv.org/pdf/2408.10548)]

*We will regularly update this repo with the latest resources. Please feel free to submit pull requests or contact us if you discover any relevant papers that are not yet included.*

## About This Survey
This paper providing a systematic review of the development of language modeling for tabular data, encompassing: 
* a categorization of different tabular data structures and data types;
* a review of key datasets used in model training and tasks used for evaluation;
* a summary of modeling techniques including widely-adopted data processing methods, popular architectures, and training objectives;
* the evolution from adapting traditional Pre-training/Pre-trained language models to the utilization of large language models;
* an identification of persistent challenges and potential future research directions in language modeling for tabular data analysis.

## Structure of Language Modeling on Tabular Data Survey

<img src="./pics/structure.png" width="96%" height="96%">


### LLM-based Methods
* TabLLM: Few-shot Classification of Tabular Data with Large Language Models. *AISTATS 2023* [[Paper](https://arxiv.org/pdf/2210.10723)]
* Language Models are Realistic Tabular Data Generators. *ICLR 2023* [[Paper](https://arxiv.org/pdf/2210.06280)]
* Generative Table Pre-training Empowers Models for Tabular Prediction. *EMNLP 2023* [[Paper](https://aclanthology.org/2023.emnlp-main.917.pdf)]
* Semi-supervised Tabular Classification via In-context Learning of Large Language Models. *ICML 2023 ES-FoMo Workshop* [[Paper](https://openreview.net/pdf?id=r77CeOBO0L)]
* Large Language Models are Versatile Decomposers: Decompose Evidence and Questions for Table-based Reasoning. *SIGIR 2023* [[Paper](https://arxiv.org/pdf/2301.13808)]
* TABLET: Learning From Instructions For Tabular Data. *Preprint 2023* [[Paper](https://arxiv.org/pdf/2304.13188)]
* TabuLa: Harnessing Language Models for Tabular Data Synthesis. *Preprint 2023* [[Paper](https://arxiv.org/pdf/2310.12746)]
* Multimodal LLMs for Health Grounded in Individual-specific Data. *Preprint 2023* [[Paper](https://arxiv.org/pdf/2307.09018)]
* UniPredict: Large Language Models are Universal Tabular Classifiers. *Preprint 2023* [[Paper](https://arxiv.org/pdf/2310.03266)]
* TabText: A Flexible and Contextual Approach to Tabular Data Representation. *Preprint 2023* [[Paper](https://arxiv.org/pdf/2206.10381)]
* REaLTabFormer: Generating Realistic Relational and Tabular Data using Transformers. *Preprint 2023* [[Paper](https://arxiv.org/pdf/2302.02041)]
* Table Meets LLM: Can Large Language Models Understand Structured Table Data? A Benchmark and Empirical Study. *WSDM 2024* [[Paper](https://arxiv.org/pdf/2305.13062v5)]
* MediTab: Scaling Medical Tabular Data Predictors via Data Consolidation, Enrichment, and Refinement. *IJCAI 2024* [[Paper](https://arxiv.org/pdf/2305.12081)]
* From Supervised to Generative: A Novel Paradigm for Tabular Deep Learning with Large Language Models. *KDD 2024* [[Paper](https://arxiv.org/pdf/2310.07338v4)]
* Confronting LLMs with Traditional ML: Rethinking the Fairness of Large Language Models in Tabular Classifications. *NAACL 2024* [[Paper](https://arxiv.org/pdf/2310.14607v2)]
* DTT: An Example-Driven Tabular Transformer for Joinability by Leveraging Large Language Models. *SIGMOD 2024* [[Paper](https://arxiv.org/pdf/2303.06748)]
* Chain-of-Table: Evolving Tables in the Reasoning Chain for Table Understanding. *ICLR 2024* [[Paper](https://arxiv.org/pdf/2401.04398)]
* Efficient Prompting for LLM-Based Generative Internet of Things (Tab-PoT: Table-QA with Program Aided LLM).  *IEEE Internet of Things Jounal 2024* [[Paper](https://ieeexplore.ieee.org/document/10705427)]

### PLM-based Methods

* TaBERT: Pretraining for Joint Understanding of Textual and Tabular Data. *ACL 2020* [[Paper]([TaBERT: Pretraining for Joint Understanding of Textual and Tabular Data (aclanthology.org)](https://aclanthology.org/2020.acl-main.745.pdf))]
* TaPas: Weakly Supervised Table Parsing via Pre-training. *ACL 2020* [[Paper]([TaPas: Weakly Supervised Table Parsing via Pre-training (aclanthology.org)](https://aclanthology.org/2020.acl-main.398.pdf))]
* TAPEX: Table Pre-training via Learning a Neural SQL Executor. ICLR 2022 [[Paper]([pdf (openreview.net)](https://openreview.net/pdf?id=O50443AsCP))]
* MultiHiertt: Numerical Reasoning over Multi Hierarchical Tabular and Textual Data. ACL 2022 [[Paper]([aclanthology.org/2022.acl-long.454.pdf](https://aclanthology.org/2022.acl-long.454.pdf))]
* TableQuery: Querying tabular data with natural language. Preprint 2022 [[Paper](https://arxiv.org/pdf/2202.00454)]
* NAPG: Non-Autoregressive Program Generation for Hybrid Tabular-Textual Question Answering. NLPCC 2023 [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-44693-1_46)]
* Few-Shot Tabular Data Enrichment Using Fine-Tuned Transformer Architectures. ACL 2022 [[Paper](https://aclanthology.org/2022.acl-long.111.pdf)]
* P-Transformer: A Prompt-based Multimodal Transformer Architecture For Medical Tabular Data. Preprint 2023 [[Paper](https://arxiv.org/pdf/2303.17408)]
* CTRL: Connect Collaborative and Language Model for CTR Prediction. Preprint 2023 [[Paper](https://arxiv.org/pdf/2306.02841)]
* Named Entity Recognition in Industrial Tables using Tabular Language Models. EMNLP 2022 [[Paper](https://aclanthology.org/2022.emnlp-industry.35.pdf)]
* TABBIE: Pretrained Representations of Tabular Data. NAACL 2021 [[Paper][https://aclanthology.org/2021.naacl-main.270.pdf]]
* External Knowledge Infusion for Tabular Pre-training Models with Dual-adapters. KDD 2022 [[Paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539403)]
* Right for the Right Reason: Evidence Extraction for Trustworthy Tabular Reasoning. ACL 2022 [[Paper](https://aclanthology.org/2022.acl-long.231.pdf)]


### Pre-training Methods

* Table2Vec: Neural Word and Entity Embeddings for Table Population and Retrieval. SIGIR 2019 [[Paper](https://dl.acm.org/doi/abs/10.1145/3331184.3331333)]
* TabTransformer: Tabular Data Modeling Using Contextual Embeddings. Preprint 2020 [[Paper](https://arxiv.org/pdf/2012.06678)]
* CT-BERT: learning better tabular representations through cross-table pre-training. Preprint 2023 [[Paper](https://arxiv.org/pdf/2307.04308)]
* TAT-QA: A Question Answering Benchmark on a Hybrid of Tabular and Textual Content in Finance. IJCNLP 2021 [[Paper](https://aclanthology.org/2021.acl-long.254.pdf)]
* TUTA: Tree-based Transformers for Generally Structured Table Pre-training. SIGKDD 2021 [[Paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467434)]
* TURL: Table Understanding through Representation Learning. SIGMOD Record 2022 [[Paper](https://dl.acm.org/doi/abs/10.1145/3542700.3542709)]
* TableFormer: Robust Transformer Modeling for Table-Text Encoding. ACL 2022 [[Paper](https://aclanthology.org/2022.acl-long.40.pdf)]
* Tabular Transformers for Modeling Multivariate Time Series. ICASSP 2021 [[Paper](https://ieeexplore.ieee.org/abstract/document/9414142)]
* FATA-Trans: Field And Time-Aware Transformer for Sequential Tabular Data. CIKM 2023 [[Paper](https://dl.acm.org/doi/abs/10.1145/3583780.3614879)]
* Self-supervised Representation Learning Across Sequential and Tabular Features Using Transformers. NeurIPS 2022 Workshop TRL [[Paper](https://openreview.net/pdf?id=wIIJlmr1Dsk)]
* One Transformer for All Time Series: Representing and Training with Time-Dependent Heterogeneous Tabular Data. Preprint 2023 [[Paper](https://arxiv.org/pdf/2302.06375)]
* UniTabE: A Universal Pretraining Protocol for Tabular Foundation Model in Data Science. ICLR 2024 [[Paper](https://openreview.net/pdf?id=6LLho5X6xV)]
* MET: Masked Encoding for Tabular Data. NeurIPS 2022 Workshop TRL [[Paper](https://openreview.net/pdf?id=vMHs3HR7r0A)]
* TransTab: Learning Transferable Tabular Transformers Across Tables. NeurIPS 2022 [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/1377f76686d56439a2bd7a91859972f5-Paper-Conference.pdf)]
* TabRet: Pre-training Transformer-based Tabular Models for Unseen Columns. ICLR 2023 Workshop [[Paper](https://openreview.net/pdf?id=qnRlh8BdMY)]
