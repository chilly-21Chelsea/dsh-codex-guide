# DSH / Codex 上手指南

> 一份给零基础同学的 AI Agent 入门讲义：从装软件、配 API Key，到写好提示词让 agent 真正替你干活。

这是宣传部「AI Agent 使用分享会」的配套文字版材料。现场演示的部分（Codex 配置文件、插件安装）以文档里的思路为准，具体界面以你安装的版本为准。

## 目录

| # | 内容 | 文档 |
| --- | --- | --- |
| 1 | 配置流程：装什么、API Key 怎么配 | [docs/01-setup.md](docs/01-setup.md) |
| 2 | 以 DSH 为例：agent 怎么用（提示词 / 四种模式） | [docs/02-dsh-demo.md](docs/02-dsh-demo.md) |
| 3 | Codex 的使用，以及与 DSH 的差别 | [docs/03-codex-vs-dsh.md](docs/03-codex-vs-dsh.md) |
| 4 | DeepSeek Harness 使用要点（`/`、`@`、md 文件） | [docs/04-dsh-tips.md](docs/04-dsh-tips.md) |
| 5 | 用到的链接 | [docs/05-links.md](docs/05-links.md) |
| 6 | 宣传部第一次团建通知 | [docs/06-teambuilding.md](docs/06-teambuilding.md) |

## 三步开始

1. **装软件**：装 DeepSeek Harness（<https://deepseek.com/harness/>）。它下载后用账号登录即可，不用额外配 Key。
2. **配 Key**（用 Codex 或其他模型时才需要）：到 <https://platform.deepseek.com/> 申请 API Key，用 CC Switch 把它接到 agent 上。
3. **写提示词**：把任务说清楚，并主动让 agent 反问你几个选择题，再让它开工。

## 核心概念速查

| 概念 | 一句话 |
| --- | --- |
| 对话式 AI vs Agent | 豆包、DeepSeek 桌面端是"对话"；agent 会拆解任务、调用工具、检查结果、反复迭代，直接操作电脑完成任务 |
| API Key | 是"钥匙"，让 agent 远程连上模型这个"脑子"。**绝不能外泄**，也不要发给 agent 让它记 |
| CC Switch | 把 agent 接到模型的工具；DSH 不需要，Codex 需要 |
| 好提示词 | 让 agent 倒回来问你问题、给你选择题，而不是让它猜 |
| Codex vs DSH | Codex = 精装商品房，流程难改；DSH = 毛坯房，插件和模式随你 DIY |

## 四种模式（DSH）

| 模式 | 用途 |
| --- | --- |
| 默认模式 | 写代码、改项目 |
| PTC 模式 | 连续调用工具（搜索、操作浏览器、截图），多技能调用省钱又快 |
| 创造模式 | 开发插件和模式，把"问问题 → 生成 md → 检查 → 开工"固化成一套流程 |
| 极简模式 | 不推荐 |

## 学习建议

- 先用**默认模式**跑通一次真实任务（比如整理课件知识点），再试 PTC 模式；
- 复杂任务先让它写一份 `md` 方案给你审，审完再动手；
- 多连几家模型的 API 对比（豆包 / 千问 / GPT / DeepSeek / Kimi），日常场景推荐 DeepSeek，便宜好用。

## 说明

- 内容来自内部分享会的讲义整理，欢迎同学补充 issue / PR。
- 文中链接为第三方站点，请注意账号与 API Key 安全。

## License

[MIT](LICENSE)
