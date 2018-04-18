# DataMining-MachineLearning
- 数据挖掘与机器学习作业
- 预览html文件，在网址前加 http://htmlpreview.github.io/?

## [信用卡违约客户的分类与聚类分析.pdf](https://github.com/Snowing-ST/DataMining-MachineLearning/blob/master/%E4%BF%A1%E7%94%A8%E5%8D%A1%E8%BF%9D%E7%BA%A6%E5%AE%A2%E6%88%B7%E7%9A%84%E5%88%86%E7%B1%BB%E4%B8%8E%E8%81%9A%E7%B1%BB%E5%88%86%E6%9E%90.pdf)
- [信用卡classification部分.Rmd](https://github.com/Snowing-ST/DataMining-MachineLearning/blob/master/%E4%BF%A1%E7%94%A8%E5%8D%A1classification%E9%83%A8%E5%88%86.Rmd)
- [信用卡description+cluster部分.Rmd](https://github.com/Snowing-ST/DataMining-MachineLearning/blob/master/%E4%BF%A1%E7%94%A8%E5%8D%A1description%2Bcluster%E9%83%A8%E5%88%86.Rmd)

本研究主要目的在于利用商业智能与数据挖掘的技术整合，利用UCI中信用卡违约客户数据，使用聚类模型探索客户分类，并利用分类算法建立一套相对稳定且有效的预测模型，提供相关部门与发卡机构一个准则，以降低违约比例，进而降低信用风险。

## [在线新闻热度预测.html](http://htmlpreview.github.io/?https://github.com/Snowing-ST/DataMining-MachineLearning/blob/master/%E5%9C%A8%E7%BA%BF%E6%96%B0%E9%97%BB%E7%83%AD%E5%BA%A6%E9%A2%84%E6%B5%8B.html)

- [在线新闻热度预测.Rmd](https://github.com/Snowing-ST/DataMining-MachineLearning/blob/master/%E5%9C%A8%E7%BA%BF%E6%96%B0%E9%97%BB%E7%83%AD%E5%BA%A6%E9%A2%84%E6%B5%8B.Rmd)

文章数据集来源于UCI网站的OnlineNewsPopularity数据集，这是关于13-14年发表在Mashable网站的新闻数据，共4万条样本，63个变量。原有数据含有的因变量为文章的转发量，我们将1400作为分界点，将转发量大于等于1400的新闻标记为热门新闻，将小于1400的文章标记为非热门新闻。我们分别使用决策树、bagging、随机森林算法，根据新闻的特征预测新闻是否为热门新闻。建模发现，bagging和随机森林比决策树的预测效果好，预测错误率分别为33.7%，33.7%，38.3%。影响因素方面，文章主题、发表时间、关键字、参考链接类型等都对新闻热度有重要影响。
