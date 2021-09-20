# 中国大学MOOC 北京师范大学
## 遥感数字图像处理 Python配套教程代码

### 目录
* 项目背景
* 环境配置
* 使用指南
* 课程大纲
* 预备知识
* 项目人员
* 参考资料
---
### 项目背景
> 遥感已从科学研究走向了大众生活，遥感数字图像处理可以帮助我们从遥感大数据中挖掘知识、获取信息。<br>
> 本课程主要讲述遥感数字图像处理的数据与方法基础、遥感数字图像质量改善、遥感数字图像信息提取与制图表达三大部分内容，为学员利用遥感数据解决科学研究与业务应用问题奠定坚实基础。
> *——《遥感数字图像处理》课程团队*<br>
> 课程链接：[中国大学MOOC-BNU-遥感数字图像处理](https://www.icourse163.org/course/BNU-1002335009)
* 目前已有越来越多不同领域的研究者开始从事遥感数字图像处理方面的工作，但是这类人员往往不熟悉遥感数字图像领域的IDL语言。<br>
* 因此，课程团队在2021年9月 - 2021年12月期间，配合第8次MOOC课程的节奏，逐步将原IDL代码迁移至Python平台。
<br>

### 环境配置
* 本教程使用Python 3.7进行演示<br>
* 需在基础版本上额外安装`numpy`和`gdal`
```python
conda install numpy gdal
```
<br>

### 使用指南
* 本课程教学代码将按照课程大纲分为12个章节，每个章节拥有独立的文件夹。<br>
* 每一章节的文件夹内部都包含三部分内容（数据文件、代码和说明文档）
<br>

### 课程大纲
#### 第一部分：遥感数字图像处理的数据与方法基础
* 第1章 数字图像基础
* 第2章 数字图像存储与读取
* 第3章 空间域处理方法
* 第4章 变换域处理方法
#### 第二部分：遥感数字图像质量改善
* 第5章 辐射校正
* 第6章 几何校正
* 第7章 图像去噪声
* 第8章 图像增强
#### 第三部分：遥感数字图像信息提取及制图表达
* 第9章 感兴趣目标及对象提取
* 第10章 特征提取与选择
* 第11章 遥感数字图像分类
* 第12章 遥感制图表达
<br>

### 预备知识
* 先修课程（必修）：计算机基础；遥感原理或遥感概论
* 先修课程（可选）：科学计算语言（python、matlab、IDL等）、遥感图像处理软件（ENVI、ERDAS等）
<br>

### 项目人员
姓名 | 单位 | 专业方向
-- | -- | --
朱文泉 | 北京师范大学 地理科学学部 教授 | 植被与生态遥感
赵涔良 | 北京师范大学 地理科学学部 21级博士生 | 植被遥感与气候反馈
何邦科 | 北京师范大学 地理科学学部 20级硕士生 | 植被遥感算法
<br>

### 参考资料
1. [朱文泉](https://geot.bnu.edu.cn/Public/htm/news/5/317.html), 林文鹏. 遥感数字图像处理——原理与方法. 北京: 高等教育出版社, 2015
2. [朱文泉](https://geot.bnu.edu.cn/Public/htm/news/5/317.html), 林文鹏. 遥感数字图像处理——实践与操作. 北京: 高等教育出版社, 2016
3. 中英文期刊：Remote Sensing of Environment、IEEE Transactions on Geoscience and Remote Sensing、遥感学报等
4. 网上论坛，如：遥感类的学术论坛
<br>
