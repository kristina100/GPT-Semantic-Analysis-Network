# GPT-Semantic-Analysis-Network

## 赛题



**赛题八：利用Tensorflow实现GPT 语义分析网络**

Paperwithcode：

 https://paperswithcode.com/paper/improving-language-understanding-by

Github：

 https://github.com/openai/finetune-transformer-lm

数据集：

 训练集：ROCStrories  测试集：ROCStrories Test

精度基线：86.50%

性能基线：24.72 sec/epoch

建议参数：train step:100*epoch BatchSize:8

## 模型解释

GPT语义分析网络是论文[《Improving Language Understanding》](https://www.cs.ubc.ca/~amuham01/LING530/papers/radford2018improving.pdf)中提出的模型，其核心思想是先通过无标签的文本去训练生成语言模型，再根据具体的NLP任务来通过有标签的数据对模型进行fine-tuning，概括而言就是先进行大量无标签数据的预训练，再使用该模型训练有标签的数据并进行监督微调。





参赛人员：王伟杭 林东迎 彭嘉涛 聂芳琪 周雍圆 黄海涛



