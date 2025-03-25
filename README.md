# 员工流失预测与决策系统

[![CN](https://img.shields.io/badge/语言-中文-red.svg)](README.md)
[![EN](https://img.shields.io/badge/Language-English-blue.svg)](README_EN.md)

> 数据科学毕业设计项目 (2024.02 - 2024.10)

## 项目概述

本项目针对企业员工流失率超行业基准且数据稀疏的问题，开发了一套完整的预测模型与可视化系统，帮助人力资源部门精准制定员工留存策略。通过混合预测模型、数据增强技术和交互式可视化，实现了高准确率的员工流失风险预测。

## 核心功能

- **流失风险预测**：基于Random Forest和Survival Analysis的混合模型，预测员工流失风险
- **数据采集系统**：通过Flask Web应用收集员工数据，支持表单填写和批量上传
- **实时数据处理**：MySQL数据管道实现员工行为数据自动化导入与风险概率计算
- **可视化决策支持**：Metabase交互看板，支持多维度筛选并可视化高危员工特征

## 技术亮点

- 通过合成数据增强与SMOTE过采样技术解决数据噪声和不平衡问题
- 模型准确率达87%，较基线提升45%
- 高危员工识别覆盖率提升至92%
- 交互式看板显著提升客户筛查效率

## 技术栈

- **编程语言**：Python
- **机器学习框架**：scikit-learn, scikit-survival
- **Web框架**：Flask
- **数据库**：MySQL
- **可视化工具**：Metabase

## 项目结构
```plaintext
Employee Turnover Prediction & Decision System/
├── Data/                   # 数据集（Kaggle数据集、合成数据集）
├── EDA/                    # 探索性数据分析和初始模型
├── Meeting Minutes/        # 项目会议记录
├── Material/               # 项目材料（PPT、报告等）
├── Model/                  # 预测模型实现
│   ├── Initial Models/     # 基于Kaggle数据的初始模型
│   └── Synthetic Models/   # 基于合成数据的模型
└── System/                 # Web应用系统
├── app/                # Flask应用
│   ├── routes/         # 路由定义
│   ├── services/       # 业务逻辑
│   └── templates/      # 前端模板
└── database/           # 数据库相关
```


## 核心模型特征

根据模型分析，以下特征对员工流失预测最为关键：

- 年龄
- 关系状态
- 工作经验年限
- 当前领域工作年限
- 薪资水平
- 每周平均工作时间
- 福利价值
- 每周无薪加班时间
- 当前职位任职时间
- 与当前主管共事时间
- 公司员工数量
- 最近薪资调整百分比
- 工作出差百分比
- 公司满意度

## 团队成员

- **Junheng Yu**
- **Pengjiabei Tang**
- **Cheng Qian**
- **Xuan Ji**
- **Yufeng Liu**

## 项目成果

- 模型准确率87%（较基线提升45%）
- 高危员工识别覆盖率提升至92%
- 交互式看板获得客户好评，显著提升筛查效率
 