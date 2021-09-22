# 实验操作1.2  波段运算--以计算NDVI为例
*代码及帮助文档：何邦科<br> 编辑：赵涔良*
## 一、目的
* 学习利用编程语言python处理遥感数据
## 任务
1. 读写遥感影像
2. 计算NDVI
3. 显示影像及其直方图
## 三、测试数据
* ENVI安装目录下的bhtmref数据
## 四、软件工具
* 本程序需要提前安装好以下安装包：`os`、`numpy`、`spectral`、`matplotlib`
## 五、处理流程
1. 读入bhtmref数据
2. 获取红波段与近红外波段影像，并计算NDVI
3. 保存NDVI影像至本地
4. 显示影像及NDVI直方图
## 六、处理结果
1. 显示红波段、近红外波段和NDVI影像以及NDVI的频数分布直方图<br>
![处理结果](https://github.com/ZhaoCenLiang/Chinese-University-MOOC-BNU-Remote-Sensing-Digital-Image-Processing/blob/master/Section_1_Fundamentals%20of%20Digital%20Image/Fig_1_practice_1.2.jpg)
2. 保存计算的NDVI影像至指定路径（本文为C:/Users/Lenovo/Desktop）
