# Rail Transit Accessibility and Commercial Spatial Patterns

language support: [English(英语)](#rail-transit-accessibility-and-commercial-spatial-patterns), [Chinese(中文)](#轨道交通服务与一小时商业可达性)

A comparative GIS study of the Utsunomiya Line in Tokyo Metropolitan Area and Chongqing Metro Line 6.

## Overview

This project investigates the relationship between rail transit accessibility and commercial spatial distribution in two contrasting urban environments: Tokyo and Chongqing.

A cumulative-opportunity accessibility measure with a 60-minute travel-time threshold is used to quantify rail accessibility.

## Study Areas

- Utsunomiya Line, Japan
- Chongqing Metro Line 6, China

## Research Workflow

1. Railway network construction
2. Travel-time calculation
3. 60-minute accessibility measurement
4. Commercial POI processing
5. Spatial comparison
6. Visualization

## Methods

- Cumulative Opportunity Measure
- Network Analysis
- GIS Spatial Analysis
- POI Analysis
- Comparative Urban Analysis

## Tools

- Python
- GeoPandas
- NetworkX
- OSMnx
- ArcGIS Pro
- OpenStreetMap

## Result

## Repository Structure

## Author

---

## 轨道交通服务与一小时商业可达性

语言支持: [English(英语)](#rail-transit-accessibility-and-commercial-spatial-patterns), [Chinese(中文)](#轨道交通服务与一小时商业可达性)

对重庆市轨道交通6号线与东京宇都宫线的GIS对比分析研究

## 项目概述
本项目研究轨道交通的停站策略与服务频率如何通过候车、行驶与停站时间，影响一小时内可达的站点与商业机会，并分析交通可达性与站点周边商业空间的匹配关系。

以重庆轨道交通6号线的单一服务等级和东京JR宇都宫线的普通、快速列车服务为案例，结合Python POI数据采集、GIS网络分析、商业空间指标和耦合协调度评价，构建跨城市轨道交通与商业空间比较框架。

## 研究问题

- 将候车时间计入后，快速列车是否能扩大一小时可达范围？
- 单一停站策略与快慢车并行，对沿线可达性的空间分布有何不同影响？
- 交通可达性较高的站点，是否同时具有更集聚、更多样的商业空间？


## 研究区域

维度 | 重庆轨道交通 6 号线 | 东京 JR 宇都宫线 |
| --- | --- | --- |
| 研究区段 | 茶园—北碚 | 上野—宇都宮 |
| 研究站点 | 28 站 | 23 站 |
| 服务形式 | 单一服务等级、逐站停靠 | 普通与快速列车 |
| 运行情景 | 高峰、平峰 | 高峰普通、高峰快速、平峰普通、平峰快速 |
| 商业数据来源 | 高德地图 POI | OpenStreetMap POI |
| 商业类型 | 购物零售、餐饮服务、综合商业 | 购物零售、餐饮服务、综合商业

## 研究方法与研究技术

<img width="1320" height="1152" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/19f879d5-3691-4be8-af5c-d21e3aa6398d" />

- 时间成本建模：区分候车、站间行驶与停站时间，按照服务类型与高峰、平峰构建情景
- GIS网络分析：以60分钟作为核心阈值，使用OD成本矩阵与服务区分析描述可达范围；论文方法部分另设45、75分钟敏感性分析。
- 商业空间分析：结合POI总数、核密度KDE、集聚度CI、香浓多样性H和餐饮占比BR。
- 耦合协调发展：通过通达性得分与商业空间得分，刻画协调程度及两者的相对发展状态。

使用ArcMap 10.4, Network Analyst 和 Spatial Analyst分析，通过高德地图API或OSM Overpass采集数据。

## 研究流程
1. 构建轨道交通网络
2. 计算出行时间
3. 测算60分钟可达性
4. 处理商业POI数据
5. 进行空间对比分析
6. 结果可视化

## 研究方法

- 累计机会法
- 网络分析
- GIS空间分析
- POI分析
- 城市比较分析

## 使用工具

- Python
- GeoPandas
- NetworkX
- OSMnx
- ArcGIS Pro
- OpenStreetMap

## 主要发现

1. 候车成本会抵消快速列车的行驶优势。

## 仓库结构
## 作者
