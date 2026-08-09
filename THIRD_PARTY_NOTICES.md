# 第三方许可说明

本 MOD 的中文字体资源包含由以下开放字体生成的字形轮廓。该部分不适用仓库的自定义
使用许可，而是继续遵循 SIL Open Font License 1.1。

## Source Han Sans SC

- 使用来源：Source Han Sans SC 2.005R
- 实际输入：`SourceHanSansSC-Medium.otf`、`SourceHanSansSC-Bold.otf`、`SourceHanSansSC-Regular.otf`、`SourceHanSansSC-Normal.otf`
- 构建字重：500、700、400、350
- 用途：重建《Quantum Break》的四套简体中文运行时字体资源
- 字体版权：Copyright 2014-2025 Adobe (http://www.adobe.com/), with Reserved Font Name “Source”.
- 许可证：SIL Open Font License 1.1
- 上游项目：https://github.com/adobe-fonts/source-han-sans

本项目实际构建输入是 Adobe Source Han Sans SC 的静态 OTF 文件，字体版权声明见
`SourceHanSansSC-COPYRIGHT.md`。

根据当前正式发布包实际包含的内容，ZIP 的 `licenses/` 目录提供以下人类可读文件：

```text
licenses/LICENSE.md
licenses/THIRD_PARTY_NOTICES.md
licenses/OFL.md
licenses/SourceHanSansSC-COPYRIGHT.md
```

MOD 中生成的 Quantum Break 字体资源属于修改并嵌入后的衍生内容，不是 Adobe、
Source Han Sans SC 或 Quantum Break 官方发布的字体产品。字体衍生内容继续遵循 SIL
Open Font License 1.1；除字体相关部分外的仓库和 MOD 内容不因此自动适用 OFL。

SIL Open Font License 1.1 官方文本：
https://openfontlicense.org/open-font-license-official-text/

## 不随发布包分发的构建与测试依赖

NorthlightTools、Pillow、pytest 和 hatchling 仅用于本地资源构建、封包或测试，不会复制、
嵌入或打包进正式 MOD ZIP，因此发布包的 `licenses/` 目录不附带这些工具的许可证副本。
这些工具仍分别遵循各自上游项目的许可证。
