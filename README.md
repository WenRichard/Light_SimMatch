# Light_SimMatch
面向中文领域的轻量文本匹配框架，集成**文本匹配**，**文本蕴含**，**释义识别**等领域的各个经典，STA模型

## 文本匹配模型
- **DSSM** 【Learning Deep Structured Semantic Models 
 for Web Search using Clickthrough Data，**2013**】  
- **ConvNet** 【Learning to Rank Short Text Pairs with Convolutional Deep
Neural Networks，**2015**】
- **QACNN** 【Applying Deep Learning to Answer Selection: A Study And An Open Task，**2015**】
- **APCNN** 【Attentive Pooling Networks，**2016**】
- **ABCNN** 【ABCNN: Attention-Based Convolutional Neural Network
for Modeling Sentence Pairs，**2017**】
- **CAM** 【A Compare-Aggregate Model for Matching
Text Sequences，**2017**】
- **ESIM** 【Enhanced LSTM for Natural Language Inference，**2017**】
- **BiMPM** 【Bilateral Multi-Perspective
Matching for Natural Language Sentences，**2017**】
- **HCNN** 【Modelling Domain Relationships for Transfer Learning on Retrieval-based Question Answering Systems，**2017**】
- **HyperQA** 【Hyperbolic Representation Learning for Fast and Efficient Neural Question Answering，**2018**】
- **MAN** 【Multihop Attention Networks for QA Matching，**2018**】
- **DIIN** 【Natural Language Inference Over
Interaction Space，**2018**】
- **DRCN** 【Semantic Sentence Matching with Densely-connected
Recurrent and Co-attentive Information，**2018**】
- **TF** 【Attention Is All You Need，**2018**】
- **Bert** 【BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding，**2018**】
- **Xlnet** 【XLNet: Generalized Autoregressive Pretraining for Language Understanding，**2019**】
- **RE2** 【Simple and Effective Text Matching with Richer Alignment Features，**2019**】
- **ERCNN** 【Enhanced Recurrent Convolutional Neural Networks for Learning Sentence Similarity，**CCL 2019**】
- **GTF** 【Gaussian Transformer: A Lightweight Approach for Natural Language Inference，**2019**】
- **MVMT** 【Many vs. Many Query Matching with Hierarchical BERT and Transformer，**NLPCC 2019**】
- **HAS** 【Hashing based Answer Selection，**2019**】
- **GGSA** 【Gated Group Self-Atention for Answer Selection，**2019**】
- **Comp-Clip-LM** 【A Compare-Aggregate Model with Latent Clustering for Answer Selection，**CIKM 2019**】
- **BERT+GSAMN** 【A Gated Self-attention Memory Network for Answer Selection，**EMNLP 2019**, **STA**】


## 实验结果
|Model|Loss|Acc|Train_time|Test_size|Test_time|Best_epoch|输入说明|论文地址|年份|  
|-|-|-|-|-|-|-|-|-|-|  
|DSSM|0.6441|**0.6341**|1877.230 s|10000|1.524 s|15|字向量|[DSSM](https://posenhuang.github.io/papers/cikm2013_DSSM_fullversion.pdf)|2013|    
|ConvNet|0.6702|**0.6945**|210.760 s|10000|0.355 s|6|字向量|[ConvNet](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.723.6492&rep=rep1&type=pdf)|2015|
|ABCNN|0.6153|**0.75**|2872.306 s|10000|2.203 s|29|字向量|[ABCNN](https://arxiv.org/pdf/1512.05193.pdf)|2017|
|ESIM|0.5545|**0.755**|35399.251 s|10000|53.762 s|41|字向量|[ESIM](https://arxiv.org/pdf/1609.06038.pdf)|2017|
|ESIM|0.5592|**0.738**|35489.816 s|10000|65.915 s|18|字向量+Attention_Mask|[ESIM](https://arxiv.org/pdf/1609.06038.pdf)|2017|
|MAN|-|-|-|-|-|-|-|[MAN](http://delivery.acm.org/10.1145/3220000/3210009/p325-tran.pdf?ip=202.115.52.109&id=3210009&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2E384BFA948992204F%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1572317138_05182aabf32fd701d6c3fa249583e750)|2018|  
|BiMPM|0.4783|**0.761**|320535.6 s|10000|2070.67 s|44|字向量+静态词向量|[BiMPM](https://arxiv.org/pdf/1702.03814.pdf)|2017|
|HCNN|0.6196|**0.726**|2843.951 s|10000|6.849 s|35|字向量+动态词向量|[HCNN](https://arxiv.org/pdf/1711.08726.pdf)|2017|
|DIIN|0.4869|**0.782**||10000|220.748 s|14|字向量+动态词向量|[DIIN](https://arxiv.org/pdf/1709.04348.pdf)|2018|
|TF|0.6537|**0.699**|2630.853 s|10000|7.384 s|44|动态词向量+位置向量|[TF](https://arxiv.org/pdf/1706.03762.pdf)|2018|
|RE2|0.5115|**0.763**|7374.503 s|10000|15.281 s|18|字向量+动态词向量|[RE2](https://www.aclweb.org/anthology/P19-1465/)|2019|
|GTF|0.6438|**0.698**|23725.764 s|10000|54.646 s|40|n-gram字向量+词向量+位置向量|[GTF]|
