# 知识图谱融合方法  
CCF 学科前沿讲习班第 108 期：知识图谱融合方法，2019/11/9，北京  
(CCF ADL #108: Tutorial on Knowledge Graph Fusion, 2019/11/9, Beijing)


## 摘要
知识图谱以结构化的方式描述客观世界中的概念、实体及其间的关系，将万维网的信息表达成更接近人类认知世界的形式，提供了一种更好地组织、管理和理解万维网上海量信息的能力。知识图谱可以由任何机构和个人自由构建，其背后的数据来源广泛、质量参差不齐，导致它们之间存在多样性和异构性。例如，对于相似领域，通常会存在多个不同的概念或实体指称真实世界中的相同事物。本报告首先简要介绍了语义网、知识图谱及知识图谱融合问题，然后介绍了面向知识图谱模式层的本体匹配方法，接下来介绍了面向知识图谱实例层的实体对齐方法，特别涉及近期基于表示学习的实体对齐方法，还介绍了知识融合过程中的真值推断方法，最后做了总结和展望。

## 报告人
胡伟，博士，南京大学计算机科学与技术系副教授、博士生导师。

如果您使用了本讲稿，请按如下引用：  
(If you use this slides, please kindly cite it as follows:)      
```
胡伟. 知识图谱融合方法. CCF 学科前沿讲习班, 2019  
(Wei Hu. Tutorial on Knowledge Graph Fusion. The CCF Advanced Disciplines Lectures, 2019)
```

## 参考文献
本报告参考了以下论文和讲稿。由于报告人水平所限，错误和遗漏在所难免，恳切希望听众批评指正！

#### 预备知识
* Similarity measures. 2013
* A string metric for ontology alignment. ISWC, 2005
* String similarity metrics for ontology alignment. ISWC, 2013

#### 本体匹配
* Anchor-PROMPT: Using non-local context for semantic matching. IJCAI, 2001
* Learning to map between ontologies on the semantic web. WWW, 2002
* Similarity flooding: a versatile graph matching algorithm and its application to schema matching. ICDE, 2002
* Constructing virtual documents for ontology matching. WWW, 2006
* Using Google distance to weight approximate ontology matches. WWW, 2007
* A survey of exploiting WordNet in ontology matching. IFIP AI, 2008
* Falcon-AO: A practical ontology matching system. JWS, 2008
* Matching large ontologies: A divide-and-conquer approach. DKE, 2008
* RiMOM: A dynamic multistrategy ontology alignment framework. TKDE, 2009
* LogMap: Logic-based and scalable ontology matching. ISWC, 2011
* SMap: 基于语义的关系数据库模式与OWL本体间映射方法. 计算机研究与发展, 2012
* An extensible linear approach for holistic ontology matching. ISWC, 2016
* Cross-lingual infobox alignment in Wikipedia using entity-attribute factor graph. ISWC, 2017

#### 实体对齐
* Entity resolution with Markov logic. ICDM, 2006
* A self-training approach for resolving object coreference on the semantic web. WWW, 2011
* Data matching. Principles of data integration, 2012
* PARIS: Probabilistic alignment of relations, instances, and schema. VLDB, 2012
* SiGMa: Simple greedy matching for aligning large knowledge bases. KDD, 2013
* Translating embeddings for modeling multi-relational data. NIPS, 2013
* Progressive approach to relational entity resolution. VLDB, 2014
* Cross-lingual entity alignment via joint knowledge graph embedding. ISWC, 2017
* Falcon: Scaling up hands-off crowdsourced entity matching to build cloud services. SIGMOD, 2017
* Knowledge graph embedding: A survey of approaches and applications. TKDE, 2017
* Multilingual knowledge graph embeddings for cross-lingual knowledge alignment. IJCAI, 2017
* Bootstrapping entity alignment with knowledge graph embedding. IJCAI, 2018
* Cross-lingual knowledge graph alignment via graph convolutional networks. EMNLP, 2018
* Deep learning for entity matching: A design space exploration. SIGMOD, 2018
* Entity alignment between knowledge graph using attribute embeddings. AAAI, 2018
* Learning to exploit long-term relational dependencies in knowledge graphs. ICML, 2019
* Multi-channel graph neural network for entity alignment. ACL, 2019
* Multi-view knowledge graph embedding for entity alignment. IJCAI, 2019
* Relation-aware entity alignment for heterogeneous knowledge graphs. IJCAI, 2019

#### 知识融合
* Truth discovery with multiple conﬂicting information providers on the web. TKDE, 2008
* Integrating conflicting data: The role of source dependence. VLDB, 2009
* A Bayesian approach to discovering truth from conﬂicting sources for data integration. VLDB, 2012
* Resolving conflicts in heterogeneous data by truth discovery and source reliability estimation. SIGMOD, 2014
* SLiMFast: Guaranteed results for data fusion and source reliability. SIGMOD, 2017
* Fact checking: Theory and practice. KDD, 2018

#### Blocking
* A blocking framework for entity resolution in highly heterogeneous information spaces. TKDE, 2012
* A survey of indexing techniques for scalable record linkage and deduplication. TKDE, 2012
* PBA: Partition and blocking based alignment for large knowledge bases. DASFAA, 2016
