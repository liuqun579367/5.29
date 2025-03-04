# 我的商小

## 项目介绍

本项目是一个学生校园生活社交软件。前端使用uniapp+javascript+scss+vue.js,后端使用java+springboot，数据库使用MySQL+Navicat。主要功能有：

- 发布具有标题，文字内容，配图的帖子，进行校园生活分享或者二手物品买卖。
- 对帖子进行点赞，评论收藏。
- 发布对于老师，课程，食堂等校园模块的评分和评价留言。
- 导入课程表，对课程信息进行查询。
- 进行兼职工作的招聘。

## 小组成员与分工

| 姓名                                | 学号         | 分工                     |
| ----------------------------------- | ------------ | ------------------------ |
| [李坤](https://github.com/applekkkk) | 2223040529 | 前端核心开发+扩展模块    |
| [刘群](https://github.com/liuqun579367)     | 2212190233 | 后端服务+基础设施        |

## 项目结构

```mermaid
mindmap
	root((我的商小))
		技术栈
			前端
				uniapp
				Vue.js
				uni-ui
				javascript
				Dcloud
			后端
				Java
				Springboot3
				MySQL·
				Maven
				mybatis
				JWT
		功能模块
			帖子管理
				发布帖子
				点赞帖子
				收藏帖子
				删除帖子
				添加评论
			校园评价
				发布主题
				进行打分
				统计分数
				进行排名
				添加评论
			课程管理
				导入课程
				课程查看
				作业标记
			招聘管理
				发布工作
				接受工作
		测试方案
			后端测试
				Postman
			集成测试
				selenium
		第三方服务
			界面设计
				即时设计
			文档编写
				markdown
				typora
			版本管理
				git
				github
```

## 项目计划

```mermaid
gantt
    title 我的商小 - 项目计划
    dateFormat  YYYY-MM-DD
    section 需求与设计
    需求分析              :a1, 2025-02-26, 7d
    技术方案评审          :a2, after a1, 5d
    UI/UX原型设计         :a3, after a2, 10d        李坤
    数据库表结构设计      :a4, after a2, 7d        刘群
    API 设计             :a5, after a4, 7d        刘群

    section 前端开发
    主页与基础框架搭建   :b1, after a3, 10d       李坤
    帖子管理页面开发     :b2, after b1, 15d       李坤
    校园评价页面开发     :b3, after b2, 10d       李坤
    课程管理页面开发     :b4, after b3, 12d       李坤
    招聘管理页面开发     :b5, after b4, 10d       李坤
    UI优化与动画         :b6, after b5, 7d        李坤

    section 后端开发
    帖子管理服务开发     :c1, after a5, 15d       刘群
    校园评价服务开发     :c2, after c1, 10d       刘群
    课程管理服务开发     :c3, after c2, 12d       刘群
    招聘管理服务开发     :c4, after c3, 10d       刘群
    JWT 鉴权与用户管理  :c5, after c4, 8d        刘群

    section 测试
    后端 API 测试       :d1, after c5, 7d        刘群
    前端页面测试        :d2, after b6, 7d        李坤
    集成测试            :d3, after d1, 7d        李坤 & 刘群
    性能优化与Bug修复   :d4, after d3, 7d        李坤 & 刘群

    section 部署与维护
    服务器环境搭建      :e1, after d4, 5d        刘群
    CI/CD 流水线配置   :e2, after e1, 5d        刘群
    版本发布           :e3, after e2, 3d        李坤 & 刘群
    运营与维护         :e4, after e3, 30d       李坤 & 刘群

```
