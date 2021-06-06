## 数据挖掘互评作业二: 频繁模式与关联规则挖掘

### 1. 问题描述

本次作业中，将选择1个数据集进行频繁模式和关联规则挖掘。

### 2. 数据说明

数据集包括：

- [Consumer & Visitor Insights For Neighborhoods](https://www.kaggle.com/safegraph/visit-patterns-by-census-block-group)
- [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews)
- [Oakland Crime Statistics 2011 to 2016](https://www.kaggle.com/cityofoakland/oakland-crime-statistics-2011-to-2016)
- [Chicago Building Violations](https://www.kaggle.com/chicago/chicago-building-violations)
- [Trending YouTube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new)
- [Melbourne Airbnb Open Data](https://www.kaggle.com/tylerx/melbourne-airbnb-open-data)
- [MLB Pitch Data 2015-2018](https://www.kaggle.com/pschale/mlb-pitch-data-20152018)

与第一次互评作业的数据集范围是相同的，在选择的时候可以选择之前预处理的数据集，也可以重新选择一个。

### 3. 数据分析要求

- 对数据集进行处理，转换成适合进行关联规则挖掘的形式；
- 找出频繁模式；
- 导出关联规则，计算其支持度和置信度;
- 对规则进行评价，可使用Lift、卡方和其它教材中提及的指标, 至少2种；
- 对挖掘结果进行分析；
- 可视化展示。

### 4. 提交的内容

- 对数据集进行处理的代码
- 关联规则挖掘的代码
- 挖掘过程的报告：展示挖掘的过程、结果和你的分析
- 所选择的数据集在README中说明，数据文件不要上传到Github中

乐学平台提交注意事项：

- 仓库地址：**记得加上**
- 报告：附件，word，pdf，html格式都可以

# 数据集Wine Reviews

------

## Description

### Context

After watching Somm (a documentary on master sommeliers) I wondered how I could create a predictive model to identify wines through blind tasting like a master sommelier would. The first step in this journey was gathering some data to train a model. I plan to use deep learning to predict the wine variety using words in the description/review. The model still won't be able to taste the wine, but theoretically it could identify the wine based on a description that a sommelier could give. If anyone has any ideas on how to accomplish this, please post them!

------

### Content

This dataset contains three files:

winemag-data-130k-v2.csv contains 10 columns and 130k rows of wine reviews.

winemag-data_first150k.csv contains 10 columns and 150k rows of wine reviews.

winemag-data-130k-v2.json contains 6919 nodes of wine reviews.

Click on the data tab to see individual file descriptions, column-level metadata and summary statistics.

------

### Acknowledgements

The data was scraped from WineEnthusiast during the week of June 15th, 2017. The code for the scraper can be found here if you have any more specific questions about data collection that I didn't address.

UPDATE 11/24/2017 After feedback from users of the dataset I scraped the reviews again on November 22nd, 2017. This time around I collected the title of each review, which you can parse the year out of, the tasters name, and the taster's Twitter handle. This should also fix the duplicate entry issue.

------

### Inspiration

I think that this dataset offers some great opportunities for sentiment analysis and other text related predictive models. My overall goal is to create a model that can identify the variety, winery, and location of a wine based on a description. If anyone has any ideas, breakthroughs, or other interesting insights/models please post them.