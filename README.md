# 项目简介 python1214

本项目是一个基于Python开发的图书借阅推荐系统，采用协同过滤算法，致力于为用户提供精准的图书推荐服务。

## 技术栈

- 后端：Python + Django框架
- 数据库：MySQL
- 前端：Vue.js

## 功能模块

### 前台功能

- 首页
- 图书推荐
- 图书详情页
- 用户中心

### 后台功能

- 总览
- 借阅管理
- 图书管理
- 分类管理
- 标签管理
- 评论管理
- 用户管理
- 运营管理
- 日志管理
- 系统信息

## 系统角色

- 图书馆管理者
- 读者

## 运行环境

- Python环境
- Django框架
- MySQL数据库
- Vue.js

## 部署步骤

1. 配置Python环境
2. 安装Django框架
3. 配置MySQL数据库
4. 部署Vue.js前端项目
5. 启动后端服务

## 目录结构

```
- backend
  - app
    - models.py
    - views.py
  - settings.py
  - urls.py
- frontend
  - assets
  - components
  - views
  - app.js
  - index.html
```

## 核心亮点

1. 基于用户协同过滤算法的图书推荐功能
2. 高内聚、低耦合的分层架构设计，便于维护和扩展
3. 全面的测试，包括功能测试、性能测试、兼容性测试和安全性测试

## 推荐逻辑

1. 构建用户-图书评分矩阵
2. 计算用户相似度（使用余弦相似度）
3. 基于协同过滤算法，为目标用户推荐相似用户喜好的图书

限制：推荐书籍数量最多为12本。

## 在线视频演示

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/327074/30/24444/736/68d6b35aF7d95db47/8c0760d9665ef797.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/348879/7/7693/41334/68d6b35aF8be04adc/e60da32b3b8cadf2.jpg)
