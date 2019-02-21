# 自学Machine learning的一些代码和笔记  
## Day 1: 信用卡欺诈检测  
日期：2019/02/21  

数据来源：[Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud  )     

最近在看生成模型相关的算法，因为之前对于生成模型几乎没怎么接触，所以计划在学习理论的同时也动手用这类模型做一些小任务。今天实现了用朴素贝叶斯模型对kaggle信用卡欺诈数据进行检测，代码主要参考了《Web安全之深度学习实战》第15章-反信用卡欺诈。     

**Key words:**  欺诈检测，朴素贝叶斯，降采样，过采样，Smote算法  