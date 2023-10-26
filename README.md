# Transformer
## 环境pytorch2.0.1
原始代码来自http://nlp.seas.harvard.edu/2018/04/03/attention.html\
一个完全注释且图文对照的Transformer代码，如果你觉得哪里有问题，请提交issue

以下两个文件使用时应保存为.py文件并从外部调用\
Transformer.ipynb实现了transformer \
Utilities.ipynb实现了一个简单的中英tokenizer可以将文字和id相互转化

## 学习顺序：
1.Transformer 对照原始论文学习Transformer中每个结构的功能\
2.看Transformer.ipynb 里面对代码进行了大量标注 看懂每个结构是怎么实现的\
3.看Utilities.ipynb 里面实现了一个简易的Tokenizer 并进行了完整的注释\
4.运行dataclean.ipynb获得清洗后的训练集 测试集 并简单了解数据清洗的过程\
5.transformer数据的全流程解释 这个文件描述了如何从数据集中抽取一条数据并且将它输入Transformer并各个节点的数据形状是什么样的\
6.编写自己的批量训练代码
