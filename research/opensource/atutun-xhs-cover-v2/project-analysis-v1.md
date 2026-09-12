# atutun-xhs-cover-v2 项目分析

## 项目来源
GitHub: panggungunvibe/atutun-xhs-cover-v2

## 项目定位
小红书封面提示词生成 Codex Skill v2。
用于把文章、脚本、选题、产品测评、AI工具教程、效率方法等内容转换为可交给图像模型执行的封面提示词。

## 核心流程

输入：
- 人物参考图
- 辅助素材
- 标题
- 封面风格
- 标题用色偏好

输出：
- 完整封面 Prompt
- 构图要求
- 字体要求
- 素材关系
- 生成限制

## v2核心优化

相比完整问卷式流程，v2减少用户决策负担，将视觉细节交给模型规划。

保留关键变量：
1. 人物
2. 辅助素材
3. 标题
4. 风格
5. 标题颜色

## 可提取到 visual-cover

### Cover Brief Schema

content
platform
headline
subject
style
color
layout
constraints

### Agent策略

用户输入最小化。
模型负责：
- 字体组合
- 背景规划
- 装饰元素
- 信息层级
- 构图平衡

## 不复制

禁止复制：
- 原项目图片
- 商业账号视觉
- 固定角色

只提取：
- 工作流
- 参数结构
- 视觉决策逻辑
