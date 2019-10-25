# o2o_comment
CCFo2o食品安全相关评论发现

|模型|码农|迭代次数|准确率(%)|词向量表示形式|注释|
|---|---|---|---|---|---|
|朴素贝叶斯|yang|1|74.43|one-hot|
|朴素贝叶斯|lin|1|78.76|one-hot|
|AdaBoost+朴素贝叶斯|lin|50|48.96|one-hot|准确率对比单独的朴素贝叶斯没有变化|
|线性SVM|lin|1000|78.13|one-hot|模型都没有朴素贝叶斯好，推测可能为one-hot编码方式所造成|
|朴素贝叶斯|lin|1|83.22|one-hot|使用修正后的分词数据集|
