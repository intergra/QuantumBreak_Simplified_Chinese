# 第三方许可说明

本 MOD 的中文字体使用 Source Han Sans SC 字形进行重建。相关字体内容不适用本项目的
自定义使用许可，而是继续遵循 SIL Open Font License 1.1。

## Source Han Sans SC

- 字体版本：Source Han Sans SC 2.005R
- 使用文件：`SourceHanSansSC-Medium.otf`、`SourceHanSansSC-Bold.otf`、`SourceHanSansSC-Regular.otf`、`SourceHanSansSC-Normal.otf`
- 对应字重：500、700、400、350
- 用途：重建《Quantum Break》的四套简体中文运行时字体资源
- 版权所有：Copyright 2014-2025 Adobe (http://www.adobe.com/), with Reserved Font Name “Source”.
- 许可协议：SIL Open Font License 1.1
- 上游项目：https://github.com/adobe-fonts/source-han-sans

本项目使用 Adobe 发布的 Source Han Sans SC 静态 OTF 文件生成所需字形。详细版权信息
见 `SourceHanSansSC-COPYRIGHT.md`。

为便于查阅，发布包随附以下许可与版权文件：

```text
licenses/LICENSE.md
licenses/THIRD_PARTY_NOTICES.md
licenses/OFL.md
licenses/SourceHanSansSC-COPYRIGHT.md
```

MOD 中的四套字体资源是在游戏原有字体基础上重新构建的衍生文件，并非 Adobe、
Source Han Sans SC 或 Quantum Break 的官方字体产品。由 Source Han Sans SC 生成的
字形继续遵循 SIL Open Font License 1.1；本项目其余内容不因此适用 OFL。

SIL Open Font License 1.1 官方文本：
https://openfontlicense.org/open-font-license-official-text/

## 仅用于构建和测试的依赖

NorthlightTools、Pillow、pytest 和 hatchling 仅用于本地构建、封包与测试，不会随 MOD
一同分发，因此不列入发布包的许可文件。各工具仍分别遵循其上游项目的许可协议。
