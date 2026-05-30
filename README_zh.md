# nature-skills 中文说明

<p align="center">
  <strong>把 Nature 风格论文写作、科研绘图、数据可用性声明和文献汇报流程做成可复用 AI skills。</strong><br/>
  <sub>它解决的问题不是“让 AI 更会润色”，而是把期刊规范、论文范例和检查清单转成明确、可执行、可复核的工作流。</sub>
</p>

<p align="center">
  <a href="README.md">English</a> | <a href="README_zh.md">中文</a>
</p>

> **Lling0000 fork / edition 说明**
> 本仓库是 [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) 的 fork。Lling0000 edition 用于让这组学术技能更容易被发现、学习和复用；不声称原创作者身份，也不继承上游项目声誉。完整归因见 [FORK.md](FORK.md)。

## 适合谁

- 正在写英文论文、准备投稿材料、整理图表或做文献汇报的研究者。
- 希望把“论文写作经验”沉淀成可执行 agent/Claude/Codex skill 的团队。
- 需要明确规则来源、输出格式和检查项，而不是泛泛风格建议的人。

## 核心卖点

- **规则来源清楚**：强调从 Nature 论文、作者指南和结构化写作课程中抽取规则。
- **输出导向**：目标是可直接使用的文本、图、PPTX 或审查清单。
- **分技能维护**：每个技能独立成目录，便于单独复制、安装、审阅和扩展。
- **边界诚实**：不能替代导师审阅、统计审查、伦理审查、期刊最终要求或人工核验。

## 技能索引

| Skill | 状态 | 解决的问题 | 触发关键词 |
|-------|------|------------|------------|
| [`nature-figure`](nature-figure/README.md) | Stable | 生成接近 Nature 标准的多面板科研图 | "Nature figure", "publication plot", "scientific figure" |
| [`nature-polishing`](nature-polishing/README.md) | Stable | 将论文草稿润色为更符合 Nature 风格的英文 | "Nature style", "polish", "academic writing" |
| [`nature-data`](nature-data/README.md) | Draft | 撰写和检查 Data Availability、FAIR 元数据、数据仓库策略 | "Data Availability", "repository", "FAIR metadata", "数据可用性声明" |
| [`nature-paper2ppt`](nature-paper2ppt/README.md) | Beta | 把论文、预印本或阅读笔记转成中文汇报 PPTX | "paper PPT", "journal club", "文献汇报", "论文做成PPT" |

## 快速使用

1. 先从上方表格选择一个 skill。
2. 打开对应目录的 `README.md`，确认输入、输出、规则依据和限制。
3. 将对应 skill 目录复制或安装到你的 agent / Claude / Codex skills workspace。
4. 在真实论文或投稿场景中使用时，保留人工核验，尤其是引用、数据、统计和伦理信息。

## Fork 边界

本 fork 的价值在于把上游技能集合以更清晰的门面呈现给 Lling0000 账号下的读者。核心技能内容仍应尊重上游作者与 MIT License。若要复用、二次发布或报告底层技能内容问题，请优先查看 [FORK.md](FORK.md) 中的上游信息。
