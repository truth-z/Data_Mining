## 数据探索性分析与数据预处理

#### 1 问题描述

本次作业中，自行选择2个数据集进行探索性分析与预处理。

#### 2. 数据集

- [GitHub Dataset](https://www.kaggle.com/datasets/nikhil25803/github-dataset?select=repository_data.csv)
- [MovieLens 10M Dataset](https://www.kaggle.com/datasets/amirmotefaker/movielens-10m-dataset-latest-version)

其中，GitHub_Dataset数据集使用的是版本一的数据集

#### 3. 数据分析要求

##### 3.1 数据摘要和可视化

- 数据摘要

   标称属性，给出每个可能取值的频数

   数值属性，给出5数概括及缺失值的个数

- 数据可视化

   使用直方图、盒图等检查数据分布及离群点

##### 3.2 数据缺失的处理

观察数据集中缺失数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理:

- 将缺失部分剔除
- 用最高频率值来填补缺失值

注意：在处理后完成，要对比新旧数据集的差异。