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
- **DIIN** 【Natural Language Inference Over
Interaction Space，**2018**】
- **DRCN** 【Semantic Sentence Matching with Densely-connected
Recurrent and Co-attentive Information，**2018**】
- **Transformer** 【Attention Is All You Need，**2018**】
- **Bert** 【BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding，**2018**】
- **Xlnet** 【XLNet: Generalized Autoregressive Pretraining for Language Understanding，**2019**】

## 实验结果
|Model|Loss|Acc|Train_size|Train_time|Test_size|Test_time|输入说明|论文地址|年份|  
|-|-|-|-|-|-|-|-|-|-|  
|DSSM|0.6441|0.6341|100000|1877.23s|10000|1.524s|字向量|[DSSM](https://posenhuang.github.io/papers/cikm2013_DSSM_fullversion.pdf)|2013|    
