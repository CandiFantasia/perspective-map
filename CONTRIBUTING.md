# 参与贡献 Contributing

感谢你愿意帮助改进视角地图。

## 可以怎样参与

- **报告问题**：在 Issues 中描述你遇到的问题，最好附上浏览器、使用的接口类型，以及出错时页面显示的提示。请不要贴出你的 API 密钥。
- **改进提示词**：`framework/` 文件夹里是框架的全部文字。如果你认为某一步的问法可以更清楚、更公平，欢迎提出修改建议。
- **补充领域说明**：路线图中计划为每个领域编写"透镜"说明。如果你熟悉某个领域，欢迎参与。
- **翻译**：目前提供英文和简体中文。欢迎帮助翻译成其他语言：复制 `framework/en/` 文件夹并以语言代码命名后翻译；界面文字位于 `index.html` 中的语言字典里。这完全出于自愿，不作任何要求。

## 提交修改时请留意

- **保持"不替用户做决定"的原则。** 修改不应让工具给出唯一的结论或推销某种立场。
- **公平地陈述不同观点。** 新增的领域说明，应当包含该领域内主要的不同观点。
- **公开预设。** 如果你的修改引入了新的预设，请在页面的"这套框架的预设"和 README 中写明。
- **保持简单。** 工具应当只需一个网页就能运行，不依赖服务器。

## 当前的一个技术说明

在 v0.1.0 中，提示词的文字同时存在于 `index.html` 和 `framework/en/`、`framework/zh-CN/` 中，修改时请保持一致。路线图中计划让网页直接读取 `framework/` 中的文件。

---

Thank you for helping improve Perspective Map. Please open an Issue for bugs or suggestions (never paste your API key). Contributions to the prompts in `framework/`, field "lens" notes, and translations are welcome. The interface is currently in English and Simplified Chinese; to add a language, copy `framework/en/`, name the folder with the language code, translate the files, and add the interface strings to the language dictionary in `index.html`. Translation is entirely voluntary. Please keep the core principles: the tool does not decide for the user, competing views are stated fairly, assumptions are made public, and the tool stays a single page with no server.
