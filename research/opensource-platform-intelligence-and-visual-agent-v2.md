# Visual Cover Open Source Research V2

## 定位
visual-cover 不是模板库，而是 AI视觉设计知识基础设施。
GitHub资料用于支撑：平台规则分析、视觉策略规划、Layout DNA Engine、生成约束。

## 研究方向

### 1. 自媒体平台智能 Platform Intelligence

#### Xiaohongshu
参考项目：
- buptweixin/xiaohongshu_skills
- atian-create/lingzao-skill
- panggungunvibe/atutun-xhs-cover
- xhs-cover-lab-open-skill

提炼：
- 内容主题分析
- 封面结构规划
- 标题与视觉层级
- 发布前检查
- 爆款内容拆解

#### 短视频/抖音方向
需要建立：
- 首帧视觉规则
- 3秒识别规则
- 视频封面规则
- 内容节奏规则

---

## 2. Layout DNA Engine

### Poster Agent

参考：
- PosterBoy
- PosterGen
- PosterMELD
- VibePoster

提炼架构：

输入素材
→ Vision Agent
→ Creative Director
→ Layout Agent
→ Typography Agent
→ Color Agent
→ Critic Loop
→ 输出视觉资产

---

## 3. Design System Extraction

参考：
- uselayout/app
- design-extract
- design-md-extractor

提炼：

参考图/UI
→ 提取设计语言
→ Layout DNA
→ Typography System
→ Color Strategy
→ AI可执行规则

禁止：复制Logo、角色、文案、独特视觉元素。

---

## 4. Skill/Agent结构参考

参考：
- xiaohongshu_skills
- xiaohongshu-operator
- poster-generator-skill

提炼：

SKILL.md
agents/openai.yaml
references/
assets/
evals/

---

## 5. visual-cover目标链路

用户素材
↓
Asset Audit
↓
Platform Intelligence
↓
Reference Analysis
↓
Layout DNA Engine
↓
Creative Direction
↓
GPT Image 2.5 Production
↓
A/B Testing
↓
QA

---

## GitHub知识分类

platform-intelligence/
layout-engine/
design-system/
opensource-reference/
scenario/
prompts/
evals/

## 应用场景

A. 插画/IP营销
- 小红书图文笔记
- IP故事传播
- 产品应用展示
- 授权招商

B. AI系统推广
- AI产品封面
- Agent案例
- 教程内容
- 视频首帧

