# Vivixiao980/xhs-cover-skill 项目分析

## 项目定位
小红书封面生成 Codex / Claude Code Skill。

## 核心特点

支持预设风格库管理。

风格结构：

style id
name
prompt
reference image

## 可提取设计资产

### Style Registry

每个风格包含：

- 布局要求
- 文字样式
- 核心特效
- 禁止事项
- 氛围描述

## 对 visual-cover 的价值

适合作为 Layout DNA 风格注册方式参考。

推荐结构：

styles/
  style-name/
    prompt.md
    layout.json
    color.json
    reference.png

## 扩展方向

结合：
- 品牌信息卡
- 平台规则
- 行业模板

形成商业封面生成系统。

## 限制

原项目主要关注封面生成，不包含完整品牌视觉策略。
