# xwchris/xhs-cover-skill 项目分析

## 项目定位
小红书封面生成 OpenClaw Skill。

## 核心能力

- 输入封面文案
- 自动生成小红书风格封面
- 支持多比例输出
- 支持 Agent 调用

支持比例：
- 3:4 小红书标准比例
- 9:16 竖版
- 1:1
- 16:9

## 架构提取

Agent
↓
Skill识别
↓
封面生成接口
↓
图像模型
↓
图片输出

## 对 visual-cover 的价值

提取：
- 平台适配层设计
- MCP/Agent调用方式
- 封面生成参数结构

参数：
- text
- aspectRatio
- style
- history

## 限制

该项目偏生成执行层。

visual-cover需要进一步增加：
- Layout DNA
- 品牌规则
- 行业模板
- A/B评价

不能直接作为完整视觉系统。
