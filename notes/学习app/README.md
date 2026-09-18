# 学习app

- 创建 / 更新日期：2026-09-18
- 类型：专门分类 / 项目进度与界面设想
- 搜索词：Termux、Rust daemon、文件编辑、终端、Codex app server、Chat UI、横屏平板。
- 来源：[用户原话](../../sources/2026/09/2026-09-18-002-learning-app.md)。以下为 agent 按用户原意整理，进度未经独立验证。

## 当前进度（2026-09-18）

- app 已成型，与 Termux 连接，有一个 Rust daemon。
- 目的是「work with files/work in projects」。
- 目前有类似 VS Code 的文件编辑与终端。

## 前端需求

用 Codex app server 建立经典的 Chat UI，需要模型选择、强度选择 slider，以及图片上传。

## UI 与布局需求

- 不常用的内容需要折叠起来。
- 布局尽可能紧凑，便于在横屏平板上轻松使用。
- 用户描述编辑器 UI 有一个「bottom bar/right bar」；具体位置关系保留原文，未进一步展开。
- 折叠区域展开时：空间不足则类似 drawer；空间充足则类似 CSS flex，即展开区域占据布局空间、处于文档流内，与悬浮 flyout 相对。这是用户对交互方式的大致描述。

### 表述澄清（2026-09-18）

最初原话为「css flexkm」，记录时标注含义待澄清。用户随后明确是「css flex」，重点是占空间、在文档流内，与悬浮 flyout 相对；据此更新上面的布局描述。原始表述保留在原始来源中，本处疑问已澄清。来源：[用户补充原话](../../sources/2026/09/2026-09-18-003-learning-app-layout-clarification.md)。

## 关联待办

任务状态统一见 [TASKS.md](../../TASKS.md)：T-20260918-01（Chat UI 前端）、T-20260918-02（UI 与布局改进）。

当天进展见 [2026-09-18](../../journal/2026/09/2026-09-18.md)。
