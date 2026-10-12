# YUAN-skills

个人使用的论文阅读 skills，公开保存，按需选择使用。每个目录都是独立的 skill 包，入口为 `SKILL.md`。

| Skill | 简介 | 适用场景 |
|---|---|---|
| [yuan-paper-intro](yuan-paper-intro/README.md) | 用中文标题、发表信息、原文框架图与逐模块步骤讲清模型流程 | 初次理解论文方法，重点看模块怎样运作 |
| [yuan-paper-reading-note](yuan-paper-reading-note/README.md) | 生成包含发表信息、消融实验、核心问题、贡献和详细模型流程的 Obsidian 阅读笔记 | 整理较完整的阅读笔记，保留个人理解与复现疑问 |

两个 skill 都默认交付 Markdown 文件，并使用 Obsidian 兼容的数学格式。

## 跟踪范围

Git 采用 `.gitignore` 白名单，目前仅跟踪上表两个 skill 目录，以及根目录的 `README.md` 和 `.gitignore`。其他本地目录、原始散装 MD、ZIP 和系统文件不纳入仓库。以后需要加入新 skill 时，在 `.gitignore` 中增加对应目录的例外规则，再显式提交该目录。
