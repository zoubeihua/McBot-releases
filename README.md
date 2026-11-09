# McBot for macOS

[**下载最新版本**](https://github.com/zoubeihua/McBot-releases/releases/latest)

这里提供 McBot 的 macOS 安装包、中文更新摘要和更新清单。McBot 基于 [OpenMausBot](https://github.com/milind-soni/OpenMausBot)，保留定制功能后独立发布。

## 选择安装包

| 你的 Mac | 下载文件 |
| --- | --- |
| Apple Silicon（M 系列芯片） | 名称以 `-arm64.dmg` 结尾 |
| Intel 芯片 | 名称以 `-x64.dmg` 结尾 |

打开 DMG，将 McBot 拖入“应用程序”。本版使用本地 ad-hoc 签名，未经 Apple 公证；首次打开如被系统阻止，请先尝试打开，再到“系统设置 → 隐私与安全性 → 仍要打开”按提示操作。详见 [Apple 的说明](https://support.apple.com/zh-cn/102445)。

使用时配置自己的模型账号或 API Key，并按需授予系统权限。安装包包含项目 LICENSE、NOTICE 和第三方声明。

## 后续更新

应用会自动检查本仓库的正式 Release，并下载、校验适合当前 Mac 的安装包。下载完成后查看更新摘要，点击“在 Finder 中显示安装包”。等 Bot 和通话结束，退出 McBot，再将新版拖入“应用程序”替换旧版。聊天和设置保存在应用外的数据目录，替换应用时保留该目录。

**更新方式是自动下载、手动安装。** 更新后系统可能再次询问钥匙串或其他权限。每个 Release 的 `INSTALL.zh-CN.md` 提供完整安装说明，`mcbot-update.json` 记录版本、源码提交、文件大小及 SHA-256。
