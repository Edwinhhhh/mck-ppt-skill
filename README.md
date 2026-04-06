# mck-ppt-skill

一个用于 OpenClaw 的 Skill 仓库模板，目标是将文章、备忘录、会议纪要、商业议题和零散业务素材，整理为 McKi风格的咨询式 PPT 大纲。

## 适用场景

适用于以下类型的工作内容：

- 将长文章整理为管理汇报型 PPT 大纲
- 将会议纪要提炼为决策沟通材料
- 将备忘录改写为结论先行的汇报结构
- 将商业问题快速展开为咨询式 deck storyline
- 将零散素材整理为董事会、经营会、项目汇报的页面框架

常见主题包括但不限于：

- 战略分析
- 经营复盘
- 市场进入
- 增长诊断
- 组织与运营优化
- 项目汇报与提案准备

## 核心输出特点

本 Skill 默认采用以下输出原则：

- Conclusion-first：先给结论，再展开支撑
- One-slide-one-message：单页只表达一个核心信息
- Storyline：整份大纲具备可复述、可推进的逻辑主线
- Executive tone：语言专业、克制、面向管理层
- Chart suggestions：每页附带建议图表或视觉表达方式

典型输出通常包括：

1. Overall takeaway
2. Storyline
3. Page-by-page outline
4. 每页标题、核心信息、支撑要点
5. 每页 chart suggestion

## 安装方式

将本仓库上传至 GitHub 后，可按以下方式安装到 OpenClaw：

1. 确保仓库根目录包含 `README.md`、`SKILL.md` 和 `references/`
2. 在 OpenClaw 中选择导入或安装自定义 Skill
3. 填入该 GitHub 仓库地址
4. 完成安装后，在对应对话或工作流中调用该 Skill

建议：

- 仓库名保持清晰，例如 `mckinsey-ppt-skill`
- 将 `SKILL.md` 作为能力规则的主文档持续维护
- 行业模板、补充规范和参考资料统一放入 `references/`

## 使用方式

安装完成后，直接提供原始材料或明确任务，即可生成咨询式 PPT 大纲。

推荐输入尽量包含以下信息：

- 业务背景
- 目标受众
- 希望回答的核心问题
- 关键事实、数据或观察
- 已有结论或待验证假设
- 期望页数范围

推荐在提示词中加入约束，例如：

- 请使用 conclusion-first 结构
- 请输出 one-slide-one-message 的页面大纲
- 请给出 page-by-page outline 与 chart suggestions
- 请使用 executive tone，避免宣传口吻
- 如原文信息不足，请显式标注 assumptions

## 示例提示词

### 1. 文章转管理汇报大纲



text
请将以下文章整理为 8 页 McKinsey 风格 PPT 大纲。
要求：conclusion-first、one-slide-one-message、语言面向管理层、每页给出标题、核心信息、3 个支撑要点和 chart suggestion。
文章如下：
[粘贴文章内容]

### 2. 会议纪要转咨询式 deck


text
下面是一份项目周会纪要。请把它改写成适合管理层汇报的咨询式幻灯片大纲。
要求先输出 overall takeaway，再给 storyline，然后给出 page-by-page outline。
每页标题必须是完整观点句，语气保持 executive tone。
[粘贴会议纪要]

### 3. 商业主题直接展开


text
主题：某零售品牌未来 12 个月如何恢复同店增长。
请输出一份 6 页的咨询式 PPT 大纲，体现 hypothesis-driven storyline。
每页需要包含：slide title、key message、supporting points、recommended chart。

### 4. 零散素材整合


text
我会提供一些零散素材，请将其整理为董事会风格汇报大纲。
输出要求：
先给一句总论
再给 5-7 页 page-by-page outline
每页只表达一个核心信息
为每页建议最合适的图表形式
若素材不足，请标注需要补充的数据素材如下：[粘贴素材]
## 推荐最佳实践
为了让输出更接近真实咨询汇报，建议优先补充以下约束：
- 明确受众，例如 CEO、管理层、业务负责人或客户方高管
- 明确用途，例如经营复盘、项目汇报、内部提案、投资人沟通
- 明确页数范围，例如 5 页、8 页、10 页
- 明确是否偏战略、运营、市场或财务视角
- 明确是否需要更强的图表建议和页面结构化表达
如果输入信息不足，推荐要求 Skill 显式标注 assumptions 与待补充数据，避免直接编造结论。
