# framework

This folder holds all of Perspective Map's framework text. It is the tool's "brain", kept apart from the page's code so that it is easy to read, discuss, change and translate.

本文件夹存放视角地图的全部框架文字，与网页代码分开存放，方便阅读、讨论、修改和翻译。

| Folder 文件夹 | Language 语言 |
| --- | --- |
| [`en/`](en/) | English |
| [`zh-CN/`](zh-CN/) | 简体中文 |

Each folder contains 每个文件夹包括:

| File 文件 | Content 内容 |
| --- | --- |
| `prompt-template.md` | The full prompt sent to the AI 发送给 AI 的完整提示词模板 |
| `steps.md` | The eight aspects 八个分析方面 |
| `lenses.md` | The twelve fields 十二个领域 |
| `principles.md` | Design principles and the framework's assumptions 设计原则与框架的预设 |

In v0.1.0 the same text is also embedded in `index.html`. Please keep both in sync when making changes.

在 v0.1.0 中，这些文字也写在 `index.html` 里，修改时请两处保持一致。

To add a language, copy the `en/` folder, name it with the language code (for example `ja/` or `es/`), and translate the files. 如需添加一种语言，复制 `en/` 文件夹，以语言代码命名（如 `ja/`、`es/`），再翻译其中的文件。
