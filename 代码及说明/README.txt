三个文件夹：
其中，每一个文件夹下都有自己的README文档。

编程语言：python-2.7

主要python包：gensim，sklearn，numpy，scipy

process_data:  处理原始数据，获得三个属性的标签文件、获取UTF-8编码的纯文本并完成分词
word2vec: 使用gensim完成w2v词向量的训练、生成以及独立测试。
main：基于上述步骤获得的数据，完成特征加权、特征融合和模型集成。