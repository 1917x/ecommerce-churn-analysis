# 电商用户购物车流失分析

## 项目简介
针对某电商平台 20,000 名用户的行为数据，搭建全链路转化漏斗，定位购物车流失瓶颈，并通过多维度归因分析锁定 Email 渠道为关键异常点，提出可落地的增长建议。

## 核心发现
- 购物车→下单转化率仅 81.6%，为最大增长瓶颈（流失 3,677 人）
- Email 渠道流失率高达 25%，显著高于其他渠道（均值 ~19%）
- 流失用户平均浏览会话数明显低于下单用户，呈现“浅逛即弃”行为模式

## 业务建议
1. 优化 Email 营销落地页一致性
2. 购物车页面增加“猜你喜欢”推荐模块
3. 加购 30 分钟未支付自动触发限时优惠券

## 项目仪表盘
<img width="1914" height="1076" alt="image" src="https://github.com/user-attachments/assets/c349644c-ddc8-4445-ab84-d165a6b893dc" />


## 使用工具
Python (Pandas, Matplotlib) | Power BI | Jupyter Lab

## 项目结构
- `notebooks/`：数据清洗与分析代码
- `dashboard/`：Power BI 仪表盘源文件
- `report/`：完整分析报告
