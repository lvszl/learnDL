一个 Attention 的计算过程有三步：

* query 和 key 进行相似度计算，得到一个 query 和 key 相关性的分值；
* 将这个分值进行归一化(softmax)，得到一个注意力的分布；
* 使用注意力分布和 value 进行计算，得到一个融合注意力的更好的 value 值。
