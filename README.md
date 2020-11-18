# KDD_xgboost_example
# 关于数据源
数据源是NSL-KDD 数据包。数据源来自： https://www.unb.ca/cic/datasets/nsl.html。 简单介绍一下数据源，NSL-KDD是为解决在中KDD'99数据集的某些固有问题而推荐的数据集。尽管该数据集可能无法完美地代表现有的现实网络世界，但是很多论文依然可以用它作有效的基准数据集，以帮助研究人员比较不同的入侵检测方法。
本文数据集来源于github的整理半成品。https://github.com/arjbah/nsl-kdd.git (include the most attack types) 和https://github.com/defcom17/NSL_KDD.git。 
数据集比较分散，train_file 和test_file 只包含样本特征和标签值，但是没有表头（header），表头的信息包含在field_name_file 中，另外关于网络攻击类型，分为5个大类，40多个小类，但是我们该测试中只预测5个大类。

# 关于代码详解
我的知乎上有文章详解了思路，这里就不赘述。
https://zhuanlan.zhihu.com/p/145458134

# 一点说明
这个是我测试的最后一个版本。代码仅供参考，因为写的比较久了，现在看来改善的空间还很大。
