# Vocalier · 配音小助手

<img src="assets/assistant.webp" width="128" height="128" alt="Vocalier 小助手" />

把一段清晰参考人声保存为音色，输入新的台词，在自己的 Mac 上生成配音。适合教程、生活旁白、广告口播和产品介绍，也可以尝试跨语言朗读。

## 下载

<!-- release-downloads:start -->

| 系统 / 组件 | 版本 | 下载 |
|---|---|---|
| Mac · Apple Silicon / M 系列（macOS 14.0+） | 0.2.1（9） · 预览版 | [下载安装包](https://github.com/EspalierLin/devtools-releases/releases/download/vocalier%2Fv0.2.1-build.9-macos-arm64/Vocalier-0.2.1-9-macOS-arm64.dmg) |

<details>
<summary>下载文件校验（SHA-256）</summary>

- Mac · Apple Silicon / M 系列（macOS 14.0+）：`1f2c0124d444d48986f8ec5fe7b1b9b584b1f5ba29ef6969b12ef2af102b83a3`

</details>

<!-- release-downloads:end -->

当前提供 Apple Silicon / M 系列 Mac 预览版，要求 macOS 14 或更新系统。此包为 ad-hoc 签名，尚未经过 Apple 公证；最低系统的实机验收仍待完成。Intel Mac 和 Windows 安装包尚未发布。

## 第一次使用

1. 打开下载的 DMG，将 Vocalier 拖到“应用程序”，再打开 App。应用自带运行环境，无须另外安装 Python、Node 或 Homebrew。
2. 已有 Vocalier 完整模型时会自动承接并保持启用，无须再次下载或重复首次配置；已明确停用的选择保持。首次需要模型时，可在“本机配音配置”选择并安装，也可以暂不安装，以后补装。
3. 从示例入口打开“通用场景配音 Demo”，选择音色，对照试听参考原声与生成成品。包内有 3 个参考音色、4 条本地模型成品，覆盖英文教程、生活旁白、广告口播和中文产品介绍。试听已有音频不需要安装模型。
4. 模型安装完成后，输入台词、选择语言并生成；试听满意后下载 WAV。另存为自己的工程可保留编辑，也可以导入自己的清晰人声和准确原文。

工程保存在你选择的位置。共享模型安装在 App 外，更新应用不会替换工程或重新下载完整模型；模型安装完成后可离线生成。首次下载和真实推理速度取决于网络、设备和文本长度。

## 关于示例和预览版

四条示例由 Qwen3-TTS 0.6B Base / MLX 在本地生成，参考选自作者的 Cardegory 制作项目。原声与成品分别标明；示例尚待人工确认读音、相似度和自然度，未预先标为满意。音频不属于源码 MIT 许可的开放素材。

当前公开渠道为 preview。本版尚未启用应用内检查／下载更新；请从 GitHub 下载新版完整应用并手动替换，保留自己的工程和共享模型。
