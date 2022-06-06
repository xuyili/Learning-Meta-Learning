本仓库用于更新收集Meta Learning学习笔记。

---

更新日志

22060608:创建仓库

---

## 概念术语表

Support Set：支持数据集，类比训练数据

Query:查询任务，类比传统机器学习的测试集

Few-Shot Learning：少样本学习

k-way:Support Set里有k个类别

n-shot:每个类别里有n个样本

Accuracy：衡量指标

\# of ways

\# of shot

Triplet Loss:

anchor:锚点

Fine-Tuning:

Neural Architecture Search:神经网络结构搜索。

Meta-Learner:元学习器

Siamese Network:孪生网络(翻译成连体网络更合适，参考“连体婴儿”)

## 入门推荐视频

1. https://www.bilibili.com/video/BV1V44y1r7cx?spm_id_from=333.880.my_history.page.click
   https://www.bilibili.com/video/BV1vQ4y1R7dr/?spm_id_from=333.788.recommend_more_video.-1

   https://www.bilibili.com/video/BV1B44y1r75K/?spm_id_from=333.788.recommend_more_video.-1

   来自wangshusen大佬，某互联网公司算法团队带头人。github：https://github.com/wangshusen/DeepLearning

2. https://www.bilibili.com/video/BV1JK4y1D7Wb?p=79
   李宏毅老师的

## 论文中常用的数据集

## 

**Omniglot,**1600多个类，每类只有20个样本，50种字母（希伯来，希腊，拉丁），105*105的图片

![A) A snapshot of some of the classes in the Omniglot dataset. (B)... |  Download Scientific Diagram](https://www.researchgate.net/publication/345010738/figure/fig6/AS:974721902460949@1609403219583/A-A-snapshot-of-some-of-the-classes-in-the-Omniglot-dataset-B-The-sample-N-way.png)

**Mini-ImageNet:**100个类，每类600个样本，84*84图片

![Sample images of widely used few-Shot learning data-sets:miniImagenet... |  Download Scientific Diagram](https://www.researchgate.net/profile/Shruti-Jadon-2/publication/343600770/figure/fig1/AS:923599858855936@1597214774024/Sample-images-of-widely-used-few-Shot-learning-data-setsminiImagenet-and-Omniglot.ppm)