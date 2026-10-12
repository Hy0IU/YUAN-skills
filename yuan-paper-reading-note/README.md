# yuan-paper-reading-note

将论文整理为适合 Obsidian 保存的中文阅读笔记，帮助复盘论文、理解模型设计和记录研究启发。由原始 `paper_reading_note_SKILL.md` 包装而来，原始规范保存在 [references/writing-guide.md](references/writing-guide.md)。

笔记先列发表渠道、等级、指标和代码公开状态，再按四部分组织：**消融实验、论文核心问题、论文贡献、模型流程说明**。模型流程是重点；个人理解、复现疑问和迁移启发以引用或 callout 与论文事实区分。

- **输入**：论文 PDF 或完整论文内容，可指定输出文件与目录。
- **输出**：Obsidian 兼容的 Markdown 文件，默认保存至论文目录的 `阅读笔记/`。
- **入口**：[SKILL.md](SKILL.md)。
- **示例请求**：使用 `$yuan-paper-reading-note` 为这篇论文生成阅读笔记，重点讲清模块机制与消融结果。

如果只需要模型方法说明，可选择 `yuan-paper-intro`；本 skill 额外整理消融、问题与贡献。
