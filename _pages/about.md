---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 💻 个人简介
人工智能应用开发工程师/中国计算机学会（CCF）会员/软件工程专业工学学士

目前就职于一家专注于AI领域的出海SaaS公司，产品面向全球市场，主要面向对象为海内外金融科技用户。本人专注于人工智能应用开发，重点研究大语言模型（LLM）在真实场景中的高效部署与系统集成。研究方向涵盖检索增强生成（RAG）、多智能体系统（Multi-Agent Systems）与多模态内容生成，聚焦于复杂任务中模型的知识调度、智能体协同决策以及多模态内容生成能力。

围绕大模型能力增强、智能体通信机制、跨模态数据处理与生成式系统设计等核心问题开展应用探索。具备扎实的系统开发能力与跨模态技术经验，致力于推动通用化、可落地的智能系统解决方案在内容生成、智能交互与信息服务等场景中的应用落地。

# 🔬 在校研究项目

## Py-Pose-Web：基于人体姿态估计算法的智能 Web 平台
#### 项目简介
系统融合深度学习与前后端架构，基于 Ultralytics YOLOv8 实现人体骨骼关键点定位检测，并通过 Flask Blueprints 构建模块化后端接口。支持静态图像、动态视频及实时摄像头输入的姿态估计，在浏览器端实现可视化交互展示，适用于体育分析、人机交互等多种场景。系统支持 PostgreSQL 向量扩展，为进一步的行为识别与数据库管理奠定基础。
#### 技术栈
YOLOv8 Pose、Flask、Blueprints、JavaScript、OpenCV、Numpy、HTML/CSS、PostgreSQL

## Face-VectorDB-Login：基于向量数据库的人脸识别登录系统
#### 项目简介
项目实现基于向量检索机制的人脸身份认证系统，采用 RetinaFace 和 ArcFace 构建高精度人脸检测与识别模型，结合 FAISS 高效索引库完成特征向量比对。系统支持人脸注册、验证与身份管理，后端利用 Flask 提供接口服务，前端通过 Electron + React 构建桌面应用，具备良好的交互体验与安全性保障。
#### 技术栈
 RetinaFace、ArcFace、iResNet50、FAISS、Flask、Electron、React、Spring Boot、PostgreSQL

## Label-Explorer：多源数据标注与可视化探索工具
#### 项目简介
工具面向计算机视觉任务中的标注数据管理，专为 YOLO 格式设计的数据集分析平台。基于 Electron 构建跨平台桌面应用，支持原始图像、标签、类别及元数据文件的统一管理与可视化，为数据清洗、标注审核及模型训练准备提供完整支持。系统可扩展接入 Label Studio 接口，增强数据处理流程的自动化与可控性。
#### 技术栈
Electron、Node.js、Python、Label Studio API

## 基于深度学习的人脸视频会议签到系统
#### 项目简介
系统集成视频通信与智能人脸识别功能，构建一套完整的视频会议出勤管理平台。前端采用 React + Electron 实现跨平台桌面应用，后端基于 Spring Boot 负责身份识别逻辑并接入 MySQL 数据库。通过 DJL 加载 RetinaFace 与 ArcFace 模型，实现精准的人脸检测与特征比对。系统融合开源 Jitsi 视频会议服务器，支持多用户实时视频通话与身份校验。
#### 技术栈
React、Electron、Spring Boot、MySQL、Ubuntu、DJL、RetinaFace、ArcFace、Jitsi

## 区块链智能合约开发与应用系统
#### 项目简介
项目围绕数字内容版权保护，构建基于区块链技术的去中心化注册与验证平台。通过 Solidity 编写并部署智能合约，实现链上资产确权与不可篡改记录存证。系统涵盖链网搭建、合约调用、前后端交互等运维流程，为实际区块链应用落地提供实验与开发平台。
#### 技术栈
Solidity、Ethereum、Web3、Linux、Docker


# 🎖 主要荣誉奖项
- *2025.06* 优秀毕业生
- *2024.12* 国家奖学金
- *2024.09* 泉州市新时代三好学生
- *2023.12* 第十一届全国大学生数字媒体科技作品及创意竞赛国赛三等奖
- *2023.12* 第十三届海峡两岸信息服务创新大赛暨第十七届计算机软件设计大赛省赛三等奖
- *2023.10* 第十一届全国大学生数字媒体科技作品及创意竞赛福建省省赛二等奖
- *2022.11* 一带一路暨金砖国家技能发展与技术创新大赛区块链智能合约赛项国内赛决赛二等奖
- *2022.09* 第十一届福建省大学生智能设计大赛省赛二等奖
- *2021 - 2022* 两年国家励志奖学金
- *2021 - 2024* 四年校一等奖学金

# 🎓 学术活动
- *2023.12* 参与海峡两岸应急管理暨应急产业发展论坛
  - 身份：大陆唯一本科生（其他参与者为研究生、博士生和教授/研究员）
  - 进展：
    - 在研讨会主会场进行汇报
    - 论文入选会议论文集
- *2023.12* 《基于你农我农平台于极端天气下农业防灾减灾的研究》论文入选《應急管理學報》第7卷


# 🏫 在校事迹
2025年6月，在专业257名学生中，以学业成绩和综合测评成绩双第一的优异表现，荣获“优秀毕业生”称号，并作为软件学院优秀毕业生代表、国家奖学金获得者登台领奖。在大学期间，累计获得三十余项校级、市级、省级及国家级技能竞赛奖项与荣誉称号。

在实践方面，大三学年，通过了学校与宁波工程学院机器人学院联合开设的科技创新班在全校范围内的选拔。在暑期留校期间，担任科创班项目团队负责人，并取得了优异成绩，在大四前的暑假提前修满了大四学年的全部课程学分。
