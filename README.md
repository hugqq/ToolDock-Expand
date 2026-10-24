# ToolDock 扩展组件

此仓库用于分发 ToolDock 的可选资源组件，二进制包存放在 [Releases](https://github.com/hugqq/ToolDock-Expand/releases)。主程序与扩展组件分别发布。

| 组件 | 作用 | 默认安装 |
| --- | --- | --- |
| PaddleOCR | 本地文字与表格识别 | 是 |
| Everything | Windows 文件搜索 | 是 |
| FFmpeg | 屏幕录制 | 否 |
| HEIF | HEIC / HEIF 图片转换 | 否 |
| Texo | 本地公式识别，含 ONNX Runtime | 否 |

安装器优先从 CDN 下载，失败时回退到本仓库同版本 Release。组件为独立 ZIP；不要合并、重命名或解压后上传。安装器使用随主程序发布的固定清单校验 ZIP 和文件的 SHA-256。

每次资源更新使用新的版本号发布，保留历史版本，不替换已发布的同名附件。后续新增组件也按独立 ZIP 和校验清单分发。

各组件的许可、NOTICE 和来源说明随 ZIP 一起提供，分别遵循原作者的许可。此仓库需要保持公开，以便安装器匿名下载。
