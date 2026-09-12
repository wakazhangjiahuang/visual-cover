# Cover Agent 开源项目研究提炼 V2

## 1. atutun-xhs-cover

来源：panggungunvibe/atutun-xhs-cover

项目类型：小红书封面 Prompt Skill

可提取模块：

### 输入合同
- 平台场景
- 内容类型
- 封面标题
- 人物/产品素材
- 目标情绪

### 输出合同
- 封面构图
- 标题层级
- 视觉元素
- 生成约束

### 已提炼视觉规则

标题：
- 超大标题优先
- 高对比文字区域
- 标题必须作为第一视觉入口

版式：
- 顶部标题区
- 中部主体视觉区
- 辅助标签/利益点区域

字体方向：
- 超粗黑体
- 粗描边
- 高识别标题字

颜色策略：
- 高明度强调色
- 黑白强对比
- 根据内容主题调整辅助色

## 2. xhs-cover-lab-open-skill

项目定位：
封面分析、赛道路由、Cover Brief生成。

提炼：

输入：
- 平台
- 内容赛道
- 目标用户
- 内容目标

分析：
- 封面类型判断
- 信息层级判断
- 视觉钩子判断

输出：
- Cover Brief
- Layout方向
- 生成规则

## 3. Vivixiao980/xhs-cover-skill

提炼方向：

- 风格标签化管理
- 风格参数与Prompt绑定
- 通过style配置扩展封面类型

适配visual-cover：
建立Style Registry。

## 4. PosterBoy / PosterAgent 类项目

提炼Agent链路：

视觉分析
→ 创意规划
→ 字体规划
→ 布局生成
→ 质量评价
→ 修复优化

适配：
作为GPT Image 2.5多方案生成前的视觉规划层。

## 5. visual-cover使用边界

允许：
- 提取版式逻辑
- 提取评价方法
- 提取Agent流程
- 提取设计变量

禁止：
- 复制项目图片
- 复制模板素材
- 复制品牌元素

## 当前缺失继续补充

- 原项目README原文摘要
- LICENSE信息
- 示例图视觉拆解
- 平台适配规则
- 风格参数库
