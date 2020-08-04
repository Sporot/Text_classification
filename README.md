# Text_classification ： A comprehensive Review
2020年的一篇文本分类综述：[**Deep Learning Based Text Classification: A Comprehensive Review**](https://arxiv.org/abs/2004.03705 "With a Title")

该论文共42页，本文档概括梳理了其具体内容，并对提到的模型和数据集进行了整理（附开源地址）；


## 1. 文本分类任务（Text Classification Tasks)
文本分类在应用中包含多个不同的任务：

1）**情感分析（Sentiment Analysis)**

分析文本数据中人们的观点（如，对产品、电影的评论），情感分类可以是二分类问题（积极、消极），也可以多分类问题（在程度上进行更细粒度的区分）。

2）**新闻分类（News Categorization)**

发现新闻热点、相关新闻推荐，为新闻分类两个主要应用。

3）**主题分析（Topic Analysis)**

给每个文档分配**一个或者多个**主题标签使得它更易理解。

4）**问答（Question Answering）**

QA系统分为抽取（Extractive)和生成(Generative)；抽取式问答可以作为文本分类的一种：给一个问句和一个候选答案群，对每个候选答案分类属于正确还是错误。

5）**自然语言推理（Natural language inference)**:

衡量两个句子间的语义相似性，来判断一个句子是否可以解释另一个句子。


## 2 文本分类中的深度学习模型

### 2.1 前向传播神经网络（Feed-Forward Neural Networks)
此方法首先通过word2vec或者Glove计算文本中每个词对应的词向量，然后将向量加和或者向量平均作为文本的嵌入表示；将此嵌入表示通过一层或多层前向传播层，然后在最后一层利用逻辑回归、朴素贝叶斯或者SVM做分类器。

#### DAN

#### FastText

#### Doc2vec




