# Awesome-IE-Resources

## 写在前面

[loujie0822/DeepIE: DeepIE: Deep Learning for Information Extraction (github.com)](https://github.com/loujie0822/DeepIE) 

@loujie0822 这一份信息抽取总结非常全面，总结了至2020年信息抽取方向了主流算法，和他在近几年在各大竞赛上成绩，能够看到各种方法之间的比较，总之是一份非常不错的学习资料。

下面是我在学习信息抽取时Star的许多资源，包括了论文代码，也有比赛top方案。

## 论文

### NER

- [jiesutd/LatticeLSTM: Chinese NER using Lattice LSTM. Code for ACL 2018 paper. (github.com)](https://github.com/jiesutd/LatticeLSTM)

- [LeeSureman/Flat-Lattice-Transformer: code for ACL 2020 paper: FLAT: Chinese NER Using Flat-Lattice Transformer (github.com)](https://github.com/LeeSureman/Flat-Lattice-Transformer)

  复旦邱锡鹏老师组的成果，通过Lattice机制将word边界信息融入了Transformer框架。就是代码没眼看，有点乱。。

- [ShannonAI/mrc-for-flat-nested-ner: Code for ACL 2020 paper `A Unified MRC Framework for Named Entity Recognition` (github.com)](https://github.com/ShannonAI/mrc-for-flat-nested-ner)

  香侬AI，MRC解决NER问题。
  
- Glyce: Glyph-vectors for Chinese Character Representations (NeurIPS-2019)
  
  香侬AI，将字形信息融合进Embedding在多个下游任务获得了提升。
  
- Named Entity Recognition as Dependency Parsing (ACL - 2020) [Code](https://github.com/juntaoy/biaffine-ner)
  
  NER + Biaffine网络
  
- A Unified Generative Framework for Various NER Subtasks - 2021

  复旦邱锡鹏老师组2021年最新成果，生成式框架解决NER问题。

- SpanNER: Named Entity Re-recognition as Span Prediction (ACL-2021)

  复旦黄萱菁老师组的成果，组合多个Span模型组合为一个系统，进行预测。

- Lattice-BERT: Leveraging Multi-Granularity Representations in Chinese Pre-trained Language Models - 2021

  阿里和北大合作的论文，沿着Lattice方向，重新设计了embedding方式以及预训练任务，将Lattice融入预训练过程。

### RE

- [thunlp/NREPapers: Must-read papers on neural relation extraction (NRE) (github.com)](https://github.com/thunlp/NREPapers)

  清华NLP总结的关系抽取论文集。

- [weizhepei/CasRel: A Novel Cascade Binary Tagging Framework for Relational Triple Extraction. Accepted by ACL 2020. (github.com)](https://github.com/weizhepei/CasRel)

### EE

- [xiaoqian19940510/Event-Extraction: 近年来事件抽取方法总结，包括中文事件抽取、开放域事件抽取、事件数据生成、跨语言事件抽取、小样本事件抽取、零样本事件抽取等类型，DMCNN、FramNet、DLRNN、DBRNN、GCN、DAG-GRU、JMEE、PLMEE等方法 (github.com)](https://github.com/xiaoqian19940510/Event-Extraction)

  网上单独搜索事件抽取获得的资料没有NER那么多（也可能因为两者本身就存在重叠），这是一份不错的总结。

- [thunlp/HMEAE: Source code for EMNLP-IJCNLP 2019 paper "HMEAE: Hierarchical Modular Event Argument Extraction". (github.com)](https://github.com/thunlp/HMEAE)

## 代码

### NER

- [CLUEbenchmark/CLUENER2020: CLUENER2020 中文细粒度命名实体识别 Fine Grained Named Entity Recognition (github.com)](https://github.com/CLUEbenchmark/CLUENER2020)

  推荐：⭐⭐⭐⭐⭐

  这一份包括下面@lonePatient（同时也是CLUENER2020作者）的代码，非常推荐学习，如果是像拿NER赛事TOP，拿这个代码往里套就是了

- [lonePatient/BERT-NER-Pytorch: Chinese NER(Named Entity Recognition) using BERT(Softmax, CRF, Span) (github.com)](https://github.com/lonePatient/BERT-NER-Pytorch)

  推荐：⭐⭐⭐⭐⭐

- [z814081807/DeepNER: 天池中药说明书实体识别挑战冠军方案；中文命名实体识别；NER; BERT-CRF & BERT-SPAN & BERT-MRC；Pytorch (github.com)](https://github.com/z814081807/DeepNER)
- [wavewangyue/ner: 命名实体识别实践与探索 (github.com)](https://github.com/wavewangyue/ner)

### RE

- [panchunguang/ccks_baidu_entity_link: ccks baidu entity link 实体链接 第一名 (github.com)](https://github.com/panchunguang/ccks_baidu_entity_link)

## 数据集

- [juand-r/entity-recognition-datasets: A collection of corpora for named entity recognition (NER) and entity recognition tasks. These annotated datasets cover a variety of languages, domains and entity types. (github.com)](https://github.com/juand-r/entity-recognition-datasets)

  信息抽取论文评测用到的数据集差不多都能在这里找到

## 工具

- [dongrixinyu/JioNLP: 中文 NLP 预处理工具包，准确、高效、易用 A Chinese NLP Preprocessing Library (github.com)](https://github.com/dongrixinyu/JioNLP)
