输入： 10-21年 股票 数据 有 30多个特征和 收益

输出 预测 股票并排序



训练集和交叉验证集的合成:在每个月末截面期，选取下月收益排名前 30%的股票作 为正例(𝑦 = 1)，后 30%的股票作为负例(𝑦 = −1)。将训练样本合并，随机选取 90%的 样本作为训练集，余下 10%的样本作为交叉验证集。

期望实用模型， transomer，lstm，wavenet





![image-20220302211211544](/Users/huyifan/Library/Application Support/typora-user-images/image-20220302211211544.png)