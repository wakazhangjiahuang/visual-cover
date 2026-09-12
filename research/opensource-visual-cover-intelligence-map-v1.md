# Visual Cover Intelligence Open Source Research Map V1

## 定位

本仓库用于支撑 `$visual-cover-studio` 的视觉策略分析与规划，不作为生成结果记忆库。

核心职责：

- 平台规则研究
- 视觉设计方法研究
- Layout DNA 分析
- 字体/色彩/版式策略
- 行业场景模板
- Agent Skill 架构参考

## 系统链路

Platform Intelligence
→ Asset Audit
→ Reference Analysis
→ Layout DNA Engine
→ Creative Direction
→ GPT Image Production
→ Visual QA

## 开源项目分类

## A. 小红书平台与封面策略

### panggungunvibe/atutun-xhs-cover

用途：小红书封面提示词与风格策略参考。

吸收：
- 封面类型模板
- 标题视觉规则
- 高点击视觉结构
- Skill 文件组织方式

禁止直接复制其视觉风格。

### atian-create/xhs-cover-lab-open-skill

用途：封面诊断与视觉规划参考。

吸收：
- 封面类型判断
- 点击原因分析
- 内容赛道路由
- Cover Brief 生成

### xwchris/xhs-cover-skill

用途：Agent 封面生成流程参考。

吸收：
- 多比例输出
- Skill 调用结构
- 自动化流程

### Vivixiao980/xhs-cover-skill

用途：GPT Image/Codex封面生成执行参考。

吸收：
- 风格库
- 参数化生成
- Agent调用方式

### tensorslab/xhs-skills

用途：小红书内容卡片与主题渲染参考。

吸收：
- 主题系统
- 卡片结构
- 多尺寸适配

### ziguishian/xhs-visual-director-skill

用途：视觉导演Agent参考。

吸收：
- 内容任务判断
- 图文结构规划
- 视觉导演流程

## B. Layout DNA / Design System

### uselayout/app

用途：设计系统提取理念参考。

吸收：
- Design Token 思维
- 结构化设计上下文
- AI可读取设计规则

### design-system-extraction

用途：设计系统逆向分析参考。

吸收：
- 色彩系统
- 字体系统
- 布局规则

### designmd-extractor

用途：Design.md生成体系参考。

吸收：
- 品牌设计规范结构
- 视觉语言描述
- Do/Don't规则

## C. Poster / Graphic Agent

### PosterBoy

用途：多Agent视觉设计流程参考。

吸收：
- Creative Director Agent
- Layout Agent
- Critic Loop

### poster-design-mcp

用途：参考图到设计系统转换参考。

吸收：
- 不复制参考图
- 提取设计方法
- 结构化设计规则

### cover-generator

用途：批量视觉生产参考。

吸收：
- 模板系统
- 自动化输出

## GitHub知识目录规划

visual-cover/

- platform-intelligence/
  - xiaohongshu
  - douyin
  - short-video
  - wechat

- layout-engine/
  - layout-library
  - font-system
  - color-strategy
  - composition-rules

- scenario/
  - illustration-ip
  - ai-product
  - ecommerce

- opensource-reference/
  - skills
  - agents
  - design-tools

- prompts/
  - analysis
  - planning
  - generation
  - qa

## 核心原则

1. 参考图只提取比例、层级、留白、字图关系、模块组织和视觉节奏。
2. 禁止复制角色、Logo、文案、品牌元素和独特视觉资产。
3. 平台规则优先于模板。
4. Layout DNA Engine 根据场景动态生成方案。
5. GPT Image 负责最终视觉生产，不负责策略判断。
