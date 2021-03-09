# 网约车Uber 出行数据分析
 
工具：Pandas、Matplotlib、Seaborn、Tableau  
注：个人实战锻炼项目，欢迎交流与勘误

## 项目背景
项目概览：根据Uber真实订单数据对基公司运营及用户出行特征进行分析，透过数据现象发现本质问题，总结网约车运营过程中应关注的点，指导出行服务进行精细化运营。
数据来源与说明：
- ①https://www.kaggle.com/fivethirtyeight/uber-pickups-in-new-york-city
- ②https://www.kaggle.com/zusmani/uberdrives


### 数据集①

2014年（4月至9月）的Uber行程数据，按月分隔，并提供详细的位置信息

Date/Time ：Uber接单的日期和时间  
Lat ：Uber接单的纬度  
Lon ：Uber接单的经度  
Base：与Uber接单相关的TLC基本公司代码  

这些文件名为：  
`uber-raw-data-apr14.csv`  
`uber-raw-data-aug14.csv`  
`uber-raw-data-jul14.csv`  
`uber-raw-data-jun14.csv`  
`uber-raw-data-may14.csv`  
`uber-raw-data-sep14.csv`

### 数据集②
2016年的Uber行程数据，按月分隔，提供地理位置（USA, Sri Lanka and Pakistan）

START_DATE*：Uber接单开始日期时间  
END_DATE*：Uber接单开始日期时间  
CATEGORY*：出行类型  
START*：起始位置  
END*：结束位置  
MILES*：里程  
PURPOSE*：出行目的  

文件名：`My Uber Drives - 2016.csv`

