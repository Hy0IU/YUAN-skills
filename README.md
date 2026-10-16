# YUAN-skills

个人研究工作流与论文阅读 Skills。独立 Skill 的入口是各自目录中的 `SKILL.md`；标题插件包含 Codex Stop Hook，需要按完整插件安装才能自动触发。

| 项目 | 简介 | 适用场景 |
|---|---|---|
| [yuan-codex-research-title](yuan-codex-research-title/README.md) | 按科研任务为 Codex 对话自动命名，包含 Stop Hook 和配套 Skill | 在 Codex 本地对话中维护可检索的科研标题 |
| [yuan-paper-intro](yuan-paper-intro/README.md) | 用中文标题、发表信息、原文框架图与逐模块步骤讲清模型流程 | 初次理解论文方法，重点看模块怎样运作 |
| [yuan-paper-reading-note](yuan-paper-reading-note/README.md) | 生成包含发表信息、消融实验、核心问题、贡献和详细模型流程的 Obsidian 阅读笔记 | 整理较完整的阅读笔记，保留个人理解与复现疑问 |

两个论文阅读 Skill 默认交付 Markdown 文件，并使用 Obsidian 兼容的数学格式。

## 跟踪范围

Git 采用 `.gitignore` 白名单，跟踪上表的三个项目，以及根目录的 `README.md` 和 `.gitignore`。其他本地目录、原始散装 MD、ZIP 和系统文件不纳入仓库。加入新项目时，在 `.gitignore` 中增加对应目录的例外规则，再显式提交该目录。
