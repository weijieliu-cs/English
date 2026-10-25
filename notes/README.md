# 知识笔记与练习作品

[返回首页](../README.md) · [查看完整练习示例](examples/first-study-note.md)

这里保存可以反复查阅的知识笔记和说写作品；每天花了多少时间、做了哪些任务，放到 [进度目录](../progress/README.md)。

## 建议命名

按需要创建主题目录，不必预先建大量空文件夹：

```text
notes/
├── pronunciation/2026-10-25-word-stress.md
├── grammar/past-simple.md
├── listening/2026-10-25-daily-routine.md
├── speaking/2026-10-25-self-introduction.md
├── reading/2026-10-25-short-story.md
├── writing/2026-10-25-an-invitation.md
├── vocabulary.csv
└── errors.md
```

上面是命名示例，不代表已有这些学习记录。持续更新的知识点用主题命名，一次性的练习加日期；文件名用小写英文和连字符。

## 怎样新建笔记

1. 复制 [学习笔记模板](../templates/study-note.md)，填写来源和本次目标。
2. 保留自己的理解、初稿和修改理由，不只粘贴范文。
3. 从 [词汇表模板](../templates/vocabulary.csv) 建立自己的词汇表，按需要追加行。
4. 从 [错误记录模板](../templates/error-log.md) 建立值得复练的问题列表。
5. 在当天学习记录中链接这份笔记，复习时直接回到作品。

Markdown 相对路径以当前文件所在目录为起点；移动文件后同步更新链接。表格中含逗号的 CSV 字段要用双引号包住，字段里的双引号写成两个双引号；使用表格软件编辑可减少格式问题。

## 音频与原始素材

录音可保存在项目根目录的 `recordings/`，笔记写相对路径或文件名即可。`recordings/`、`downloads/` 和 `personal/` 已列入忽略规则，未来使用 Git 时默认不提交；Markdown 笔记和 CSV 默认会被提交。需要完全私人的内容可以放进 `personal/`。

项目中优先保留原材料链接和自己写的摘要，完整课程、书籍和媒体文件遵守原作者的授权条件。记录学习经验时标明试用条件，不从一次成功推导普遍效果。
