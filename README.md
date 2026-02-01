# F030_white vue+flask求职薪资预测职位推荐机器学习系统| 带有协同过滤| 决策树+随机森林预测薪资【白色版本】

> 完整项目收费，可联系QQ: 81040295 微信: mmdsj186011 注明从github来的，谢谢！
也可以关注我的B站： 麦麦大数据 https://space.bilibili.com/1583208775
> 

关注B站，有好处！
编号:  F030 【白色版本】
## 视频

[video(video-suuyhHNe-1760666804804)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=113615306759012)(image-https://i-blog.csdnimg.cn/img_convert/4a063aa39ab70b0bfe9d4657368f9558.jpeg)(title-机器学习薪资预测系统求职推荐工资预测可视化大数据vue+flask就业大数据，决策树随机森林，招生大数据)]

## 1 系统简介
系统简介：本求职系统（F030 Vue+Flask 薪资与职位推荐知识图谱可视化系统）旨在为用户提供一站式的求职体验，集成了职位推荐、数据分析、薪资预测及个人设置等多元功能。系统核心功能包括：精准职位推荐，通过Usercf和Itemcf等多种推荐算法，根据用户偏好和行为，智能匹配最合适的职位，并在主页展示，同时辅以数据分析和类型分析，帮助用户洞察职位市场。详尽职位库，允许用户通过查询功能，结合地图分析直观了解职位分布。深度数据分析，通过数据可视化和词云分析，直观呈现行业趋势与热点，智能薪资预测，引入决策树和随机森林等预测模型，为用户提供薪资参考，助力求职决策。此外，系统还具备完善的登录&注册系统及个人设置模块，包括实名认证、修改信息、头像和密码管理，确保用户数据安全与个性化体验。整个系统以知识图谱为基础，旨在通过可视化方式，让求职信息更加直观、易懂，助力用户高效找到心仪工作。
## 2 功能设计
本求职系统采用模块化、前后端分离的架构设计，以提升系统的可扩展性、可维护性和用户体验。前端部分基于Vue.js框架开发，利用HTML、CSS、JS构建用户界面，结合Vuex进行状态管理，vue-router实现路由跳转，并集成echarts等图表组件，为用户提供直观的数据可视化展示和流畅的交互体验。用户通过浏览器即可轻松访问系统。后端则采用Flask框架（Python）实现，负责处理前端请求、业务逻辑、数据存储与检索。数据存储层面，系统采用双数据库策略：MySQL用于存储如用户信息、职位信息等结构化数据，通过Sqlalchemy等ORM工具与Flask后端交互；系统还包含爬虫模块，负责从外部数据源抓取职位、薪资等数据并存入MySQL。整体架构清晰，各模块职责明确，保证了系统的高效稳定运行。
### 2.1系统架构图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0985654919a7411c86316f10a658952e.png)
### 2.2 功能模块图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/cede755b26414a079601981932e5c16d.png)
## 3 功能展示
### 3.1 登录 & 注册
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a296813be4d647fba7e5057db392c896.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/037bd0b2a8764bd5bbcd2c1b8332715c.png)
### 3.2 主页 & 推荐算法
主页左边是菜单栏，右边是操作面板，提供UserCF+ItemCF两种协同过滤推荐算法推荐职位：
**UserCF 推荐算法：**
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/5b7918a46df740d7b2d82d63f01f3849.png)
**ItemCF 推荐算法:**
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/be790328554741c0ba5edb6155b58eee.png)
点击可以查看职位详情：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/6530acd9c4bb47e9bfb2ea1694f76043.png)
### 3.3 职位库 & 职位搜索
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/cda7095e7aa64b03a4cb499546c6ad8b.png)
### 3.4 数据分析
在这个界面可以分析职位、城市职位分析、学历与城市薪酬的关系、高薪工资、底薪公司的分析。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/637da4facc1b4b14bacf7962ab0a780d.png)
### 3.5 地图分析
利用中国地图分析我们系统爬取到的职位。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/2c3894ebdecd4b69a0b89e4d0f47bc30.png)
### 3.6 类型散点分析
利用散点图进行职位和薪酬的分析。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/603699ba58104ead93009addb6056e4b.png)
### 3.8 薪资预测
利用机器学习训练的**决策树模型**预测薪资：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/bb9d5f3ce4404715892572df57df650a.png)

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/09718a1b37ce40ac9178eeeecb9b5e00.png)

利用机器学习训练的**随机森林模型**预测薪资：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/1b2aaf0d00ac4c2ba6c9535da32dbad6.png)

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/9a9fdb79f7c0490692120ef9b8ff77de.png)
### 3.9 个人设置
修改个人信息、头像、修改密码、实名认证功能都集成在这个页面上。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0cb7e56d1b6445f0878e0a7bd6f2ae35.png)
### 3.10 修改密码
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f54f8120a8964af39dbd11fafa9e00cd.png)
## 4程序代码
### 4.1 代码说明
代码介绍：使用scikit-learn库来创建和训练一个决策树回归模型。数据集将使用pandas读取，并进行预处理。模型训练后，我们将使用测试集进行预测，最后计算预测的准确性。代码中包含了数据加载、特征选择、模型训练、预测和评估的步骤。
### 4.2 流程图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/87465665b21b460f8549087dea5a8b8f.png)
### 4.3 代码实例
```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.metrics import mean_squared_error

# 加载数据
data = pd.read_csv('salaries.csv')

# 特征选择
X = data[['experience', 'education_level']]
y = data['salary']

# 数据集分割
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# 创建决策树回归模型
model = DecisionTreeRegressor(random_state=42)

# 训练模型
model.fit(X_train, y_train)

# 进行预测
y_pred = model.predict(X_test)

# 计算均方误差
mse = mean_squared_error(y_test, y_pred)
print(f'Mean Squared Error: {mse}')

```
