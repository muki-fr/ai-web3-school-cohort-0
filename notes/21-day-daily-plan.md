# 21 天 Hackathon 每日学习计划

## 你的目标

用 21 天完成一个适合新手的 Hackathon MVP：AI 辅助 Web3 学习助手。

每天投入 3 小时，固定节奏：

- 60 分钟：学习一个核心概念
- 75 分钟：动手做一个小产出
- 30 分钟：整理笔记和 README
- 15 分钟：提交 GitHub proof-of-work

## 第 1 周：工具和基础概念

### Day 001：公开学习仓库初始化

目标：完成学习仓库、明确方向、建立打卡习惯。

任务：
- 确认 GitHub 仓库可以公开访问
- 阅读 `README.md`、`notes/learning-roadmap.md`、`hackathon/ideas.md`
- 修改 `daily-logs/day-001.md`，写成自己的真实记录

交付物：
- `daily-logs/day-001.md`
- 一次 commit + push

### Day 002：Git / GitHub 基础

目标：会做最常用的 Git 操作。

任务：
- 学会 `git status`、`git add`、`git commit`、`git push`
- 修改 `README.md`，补充你的学习目标
- 新建 `daily/day-002.md`

交付物：
- 更新后的 `README.md`
- `daily/day-002.md`

### Day 003：Markdown 写作

目标：能写清楚项目文档和学习笔记。

任务：
- 学习 Markdown 标题、列表、代码块、链接
- 新建 `notes/markdown-basics.md`
- 用 Markdown 写 5 个你今天学到的 GitHub 概念

交付物：
- `notes/markdown-basics.md`
- `daily-logs/day-003.md`

### Day 004：Web3 最小词汇表

目标：理解钱包、地址、私钥、助记词、链、Gas 的关系。

任务：
- 新建 `notes/web3-basics.md`
- 用自己的话解释 8 个 Web3 词汇
- 写一段安全提醒：为什么不能泄露私钥和助记词

交付物：
- `notes/web3-basics.md`
- `daily-logs/day-004.md`

### Day 005：AI Agent 基础概念

目标：理解 Agent 是什么，以及它和普通聊天机器人的区别。

任务：
- 新建 `notes/ai-agent-basics.md`
- 写清楚：输入、推理、工具、记忆、输出
- 设计你的学习助手会回答的 10 个问题

交付物：
- `notes/ai-agent-basics.md`
- `hackathon/questions.md`
- `daily-logs/day-005.md`

### Day 006：Hackathon 项目问题定义

目标：把项目从“想法”变成“问题”。

任务：
- 阅读 `hackathon/ideas.md`
- 选择主方向：AI 辅助 Web3 学习助手
- 新建 `hackathon/problem.md`
- 写清楚用户、痛点、使用场景、为什么现在值得做

交付物：
- `hackathon/problem.md`
- `daily-logs/day-006.md`

### Day 007：第 1 周复盘

目标：检查基础是否跑通。

任务：
- 整理本周所有笔记
- 更新 `README.md` 的项目方向
- 写出你的 MVP 一句话说明

交付物：
- `daily-logs/day-007.md`
- 更新后的 `README.md`

## 第 2 周：做出最小 Demo

### Day 008：MVP 功能拆解

目标：确定 Demo 只做最小必要功能。

任务：
- 新建 `hackathon/mvp.md`
- 写 3 个核心功能：提问、中文解释、安全提醒
- 写 3 个暂时不做的功能，避免范围失控

交付物：
- `hackathon/mvp.md`
- `daily-logs/day-008.md`

### Day 009：准备项目原型页面

目标：建立一个最简单的网页 Demo。

任务：
- 在 `experiments/` 下创建 `web3-learning-assistant/`
- 做一个 `index.html`
- 页面包含输入框、按钮、回答区域

交付物：
- `experiments/web3-learning-assistant/index.html`
- `daily-logs/day-009.md`

### Day 010：做静态回答逻辑

目标：不接 API，先让 Demo 可以用。

任务：
- 新增 `script.js`
- 用户输入“钱包 / Gas / 私钥”等关键词时，显示预设中文解释
- 每个回答都带安全提醒

交付物：
- `experiments/web3-learning-assistant/script.js`
- `daily-logs/day-010.md`

### Day 011：优化界面

目标：让 Demo 看起来像一个可展示的产品。

任务：
- 新增 `style.css`
- 优化输入区域、回答区域、示例问题
- 确保页面中文清晰、按钮明显

交付物：
- `experiments/web3-learning-assistant/style.css`
- `daily-logs/day-011.md`

### Day 012：补充 Web3 问答库

目标：让 Demo 可以覆盖更多新手问题。

任务：
- 整理 15 个 Web3 新手问题
- 每个问题写：一句话解释、详细解释、安全提醒
- 保存到 `experiments/web3-learning-assistant/knowledge.js`

交付物：
- `knowledge.js`
- `daily-logs/day-012.md`

### Day 013：增加学习记录功能

目标：让用户看到自己问过什么。

任务：
- 在页面上显示最近 5 条提问
- 使用浏览器本地存储保存历史记录
- 写明不保存隐私信息

交付物：
- 更新后的 Demo
- `daily-logs/day-013.md`

### Day 014：第 2 周复盘和 Demo 截图

目标：确认 Demo 可以被别人看懂。

任务：
- 从浏览器打开 Demo，测试 5 个问题
- 截图或写测试记录
- 更新项目 README，说明如何打开 Demo

交付物：
- `daily-logs/day-014.md`
- 更新后的 Demo README

## 第 3 周：包装成 Hackathon 项目

### Day 015：写项目 README 初稿

目标：让评委 1 分钟内理解项目。

任务：
- 新建 `hackathon/project-readme-draft.md`
- 写项目名、问题、解决方案、目标用户、Demo 功能
- 写当前限制和下一步计划

交付物：
- `hackathon/project-readme-draft.md`
- `daily-logs/day-015.md`

### Day 016：设计 Pitch 结构

目标：准备 3 分钟项目介绍。

任务：
- 新建 `hackathon/pitch.md`
- 按 6 段写：问题、用户、方案、Demo、优势、下一步
- 每段控制在 2 到 4 句话

交付物：
- `hackathon/pitch.md`
- `daily-logs/day-016.md`

### Day 017：安全和伦理检查

目标：避免项目误导 Web3 新手。

任务：
- 新建 `hackathon/safety.md`
- 写清楚：不索要私钥、不替用户投资、不保证收益、不诱导签名
- 给 Demo 增加明显安全提示

交付物：
- `hackathon/safety.md`
- 更新后的 Demo
- `daily-logs/day-017.md`

### Day 018：模拟用户测试

目标：用新手视角检查 Demo。

任务：
- 设计 5 个测试问题
- 记录 Demo 的回答是否清楚
- 写 3 个需要改进的地方

交付物：
- `hackathon/user-test.md`
- `daily-logs/day-018.md`

### Day 019：修复和 polish

目标：把最影响展示的问题修掉。

任务：
- 修复 Day 018 发现的问题
- 优化 README、Pitch 和 Demo 文案
- 确保 GitHub 仓库结构清晰

交付物：
- 更新后的 Demo 和文档
- `daily-logs/day-019.md`

### Day 020：最终演示稿

目标：准备可以提交的 Hackathon 材料。

任务：
- 整理最终 README
- 整理 Pitch 脚本
- 写 1 分钟 Demo 操作流程

交付物：
- `hackathon/final-submission.md`
- `daily-logs/day-020.md`

### Day 021：最终复盘和提交

目标：完成 21 天 proof-of-work。

任务：
- 检查所有文件是否已 push 到 GitHub
- 写项目复盘：学到了什么、哪里卡住、下一版做什么
- 在 README 顶部放最终项目说明和 Demo 路径

交付物：
- `daily-logs/day-021.md`
- 最终版 README
- GitHub 仓库完整记录

## 每天提交格式

每天结束时执行一次：

```powershell
git status
git add .
git commit -m "Day XXX: short summary"
git push
```

示例：

```powershell
git commit -m "Day 002: learn Git and update README"
```

## 每天打卡模板

```markdown
# Day XXX

## 今天目标

-

## 今天完成

-

## 学到的概念

-

## 遇到的问题

-

## 明天计划

-
```
