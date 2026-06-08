# 我知道的所有 Agentic Engineering 技巧（2026 年 6 月）

| 属性 | 值 |
|------|-----|
| 标签 | 大模型 |
| 日期 | 2026-06-05 |
| 原文链接 | [原始链接](https://mp.weixin.qq.com/s/Oo0iksfTXvUSFNnBrWOOpw) |
| 本地文件 | [查看原文](https://xiongdage92.github.io/Personal_Docs_Base/articles_html/2026-06-05-我知道的所有Agentic-Engineering技巧.html) |

---

# 文章摘要

本文整理了连续创业者 Matt Van Horn 总结的 22 条 Agentic Engineering 实战技巧，涵盖从规划、多 agent 调度、上下文管理、远程控制到开源贡献的完整方法论。核心主张是"先规划再动手"——用 /ce-plan 将模糊想法外化为计划文件，用 /ce-work 驱动执行，将 research → plan → build → review 固化为默认流水线，最终让人的角色从编码者上移至调度者与品味判断者。

## 核心结论

拉开 AI 编程能力差距的关键不是模型本身，而是喂给 agent 的上下文质量和人给出的方向信号——原始会议录音、截屏、issue、历史笔记持续流入 agent 才能产生质变。

## 关键要点

- **用计划约束 agent**：有想法先用 /ce-plan 生成 plan.md，计划是 agent 的"缰绳"，无计划的 agent 易抄近路、提前停工
- **多线程调度 agent**：同时开 4-6 个 cmux 会话，一个写 plan、一个 build、一个跑研究、一个修 bug，人类负责调度与信号
- **上下文为王**：last30days 先行研究、Granola 原始会议记录、十年笔记全部喂入 agent，不要先"替模型总结"
- **一切可写成 skill**：任何做超过两次的事写成 skill，开源贡献纳入同一条 plan→build loop
- **警惕成瘾**：agent 让 build 变得像打游戏一样反馈极快，越能 build 越要警惕，保持与真实世界的连接

## 对读者的价值

对于日常使用 Claude Code 或 Codex 的开发者，这 22 条技巧提供了从单窗口操作到多 agent 调度的完整升级路径，每一条都可直接照做。尤其适合正在探索 AI 编程效率边界的独立开发者和开源贡献者。

## 标签

### 主题标签

Agentic Engineering、Claude Code、AI 编程、多 agent 调度、上下文工程

### 领域标签

- AI / 大模型
- 软件开发

### 文章类型

- 经验分享

### 核心实体

Claude Code、Codex、Compound Engineering、last30days、Printing Press、cmux、Granola、Monologue、Agent Cookie、Proof

### 检索关键词

Agent 开发、AI 编程技巧、多 agent 工作流、/ce-plan、/ce-work、上下文工程、远程控制、skill 开发、开源贡献

---

*点击上方"查看原文"链接可在浏览器中打开原始文章（含完整格式和图片）。*
