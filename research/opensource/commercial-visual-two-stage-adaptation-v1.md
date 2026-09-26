# 双阶段商业视觉 → 小红书封面：开源方法适配 V1

检索日期：2026-09-26。用途：供 visual-cover 研究层复用的方法映射。本文只整理公开项目的方法，不包含用户上传的品牌资料、参考图、原 GPT 指令或其私有知识。

## 已有资产与新增范围

已有 [xhs-cover-lab-open-skill 项目分析](./xhs-cover-lab-open-skill/project-analysis-v1.md)覆盖封面类型、赛道路由和 Cover Brief。这里补充“第一阶段商业系列图 → 选定源图 → 第二阶段封面”的源图约束、其他两个项目的兼容性与许可核验；不重抄原分析。

| 项目及核验文件 | 可借用的方法 | 不能直接继承 |
| --- | --- | --- |
| [atian-create/xhs-cover-lab-open-skill](https://github.com/atian-create/xhs-cover-lab-open-skill)；SKILL blob `e162ebf31221fd4fd4534b055bfe9857cabf3a2c`，封面类型 blob `1448d790b7597a300e652158b12c52fda86d6081`，MIT LICENSE blob `6fd39e374ff4c21146ed4fce47f3224d6d723210` | 封面类型判断、受众与证明场景、非复制的 Cover Brief | 它不提供实时搜索、图像生成或真实效果数据；不能把简报直接当成成品 |
| [ziguishian/xhs-visual-director-skill](https://github.com/ziguishian/xhs-visual-director-skill)；SKILL blob `1d870c7e7aed8df08af96973263e4bd839eeb39d`，MIT LICENSE blob `b948235b71f83c1d4d0eb090a35ebe5ae829607a` | 系列视觉母版、逐张信息层级与一致性检查 | 强制十问、固定多页数和默认风格与直接出图需求不兼容 |
| [Ali-Aria/aria-visual-skills](https://github.com/Ali-Aria/aria-visual-skills)；xhs-visual-cards SKILL blob `635c235345af9d36b57f6d597594554d1bfe7291`，MIT LICENSE blob `b7dc063ab0640044e94c0b2c4143c5c1282a261b` | 每页独立 3:4 生成、逐页检查文字与移动端阅读 | 固定白底手绘、无人物的美学不能覆盖跨行业品牌风格 |

## 适配到新链路

1. 第一阶段先由目标产品事实决定内容模块，再由参考图提取抽象风格锚点，形成十个可见差异的商业视觉假设；每版单独生成并记录 `S1-xx` 与真实图片。
2. 第二阶段必须绑定存在的 `parent_asset_id`；承袭该图主体与风格锚点，再借 Cover Brief 的“受众/点击理由/证明场景”重新组织标题、焦点和裁切。
3. 每张 `S2-xx` 独立生成，移动端检查主题识别和标题准确性。创意评分只能作为事前启发，不能称为观察到的 CTR；以真实发布数据验证效果。
4. 用户授权的品牌名与定稿文案可保留，第三方参考图的商标、原文案和具体组合不复制。

方法借鉴不包含原项目的代码、提示词、模板或图像，因此没有把任何上游文件重新分发。若未来复制源码或大量文字，重新核对当时的许可版本并保留许可声明。此研究文件是可选知识补充；新业务 Skill 自带执行规则，运行不依赖本仓库或 Manifest。
