# 想法精炼师（Thought Refiner）

把模糊想法炼成清晰、完整、可执行的方案。

`thought-refiner` 是一个适用于 Codex 和 ChatGPT 的独立技能。它不会急着替你做决定，而是把问题整理成决策树，通过一轮轮简单追问，找出隐藏假设、遗漏选项和前后依赖。

## 它会做什么

- 把复杂问题拆成有先后关系的决策
- 每轮只问现在能回答的问题
- 给每个问题提供清楚选项和推荐答案
- 自动查找能查到的事实，减少用户负担
- 使用用户的语言；出现英文时附上中文解释
- 在所有关键问题确认前，不贸然执行方案

## 安装

在 Codex 中调用 `$skill-installer`，并让它安装这个目录：

```text
https://github.com/chenjieliefu/thought-refiner/tree/main/thought-refiner
```

也可以下载仓库，把 `thought-refiner` 文件夹放入 Codex 的个人技能目录中。

## 使用

在 Codex 中输入：

```text
$thought-refiner 帮我把这个产品想法想清楚。
```

适合用来讨论：

- 产品或创业想法
- 项目计划
- 技术或产品设计
- 重要选择
- 任何“感觉还没想透”的方案

## English

Thought Refiner turns vague ideas into clear, complete, actionable plans through dependency-aware rounds of simple questions.

## 许可

MIT License。你可以自由使用、修改和分享。
