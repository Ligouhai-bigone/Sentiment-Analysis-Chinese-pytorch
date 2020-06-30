# Chineses-Sentiment Analysis-Pytorch
## 中文情感分析的Pytorch实现

**本项目使用了word2vec的中文预训练向量

**模型分别有BiLSTM-attention和普通的LSTM两种，自行选择

## 使用说明：
1、在**Config**中配置相关参数

2、然后运行**DataProcess.py**，生成相应的word2id，word2vec等文件

3、运行主函数**main.py**，得到训练好的模型，并保存模型

4、运行**eval.py**，读取模型，并得到评价
**准确率平均85%左右**
## 如果好用请给个Star，谢谢了
