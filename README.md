#Chineses-Sentiment Analysis-Pytorch
#(中文情感分析的Pytorch实现)

#本项目使用了word2vec的中文预训练向量
#模型采用的有BiLSTM-attention和普通的LSTM
#使用说明：
1、在Config中配置相关参数

2、然后运行DataProcess.py，生成相应的word2id，word2vec等文件

3、运行主函数main，得到训练好的模型，并保存模型

4、运行eval.py，读取模型，并得到评价

#如果好用请给个Star，谢谢了
