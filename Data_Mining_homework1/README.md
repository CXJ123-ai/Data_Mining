# Data_Mining 互评作业1

#### 选取的数据集为Wine Reviews和Oakland Crime Statistics 2011 to 2016


**首先wine reviews数据集，处理过程如下**
1. 导入并合并两个winereviews.csv然后去重
2. 分析标称属性数据“country” “province” “region_1” “region_2” "variety" "winery"统计其频数
3. 分析数值属性“points” " price" 得到其五数概括
4. 使用盒图可视化数值属性“points” " price"数据
5. 分析“points”使用直方图分析“average point index of the top 10 national wines” “top 10 countries for the sum of the quality of wine” 
6. 分析“price” 可视化“price”分布的散点图，可视化“price的直方图与概率密度图”,讨论原材料与酒价格的关系
7. 数据集缺失处理，使用提出缺失值、高频填充等方法，并可视化数据与源数据对比


**处理Oakland Crime Statistics 2011 to 2016数据集，处理过程类似**
1. 导入并合并两个11-16年数据然后去重
2. 分析标称属性数据“Location” 、“Area Id”、 “Incident Type Id” ”Priority“ ”Zip Codes“等 统计其频
3. 可视化数据 用直方图画出‘Top 20 crime areas’、‘Top 20 Crime Types'、'Crime Level'等
4. 缺失值处理 ”location“，以此为例。处理方法为剔除缺失值和高频填充数据集，可视化处理后的数据并与源数据对比。
