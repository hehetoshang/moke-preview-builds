# 墨客 Preview（Moke Preview）

Moke Preview 是墨客的预览通道，面向希望提前体验新功能并参与反馈的赞助者。墨客是 [Talebook](https://github.com/talebook/talebook) 自托管电子书服务的客户端，支持浏览书库、搜索、下载和阅读电子书。

本仓库提供 Moke Preview 安装包与发布说明。完整参与说明可查看 [墨客帮助文档 · Moke Preview 赞助内测](https://website-ten-tan-60.vercel.app/docs/guide/support#moke-preview-%E8%B5%9E%E5%8A%A9%E5%86%85%E6%B5%8B)。

[下载 Preview](https://github.com/hehetoshang/moke-preview-builds/releases) · [参加赞助内测](https://ifdian.net/a/hehetoshang) · [一键反馈](https://github.com/talebook/moke/issues/new?template=moke-preview.yml&labels=moke-preview) · [帮助文档](https://website-ten-tan-60.vercel.app/docs/)

## 可以体验什么

- 尚未进入稳定版的新功能、交互调整与兼容性改进。
- 与稳定版分开的 Preview 构建和发布节奏。
- 在功能正式发布前，向开发者反馈问题与使用感受。

## 如何参加

1. 前往 [爱发电](https://ifdian.net/a/hehetoshang) 购买对应的 Moke Preview 内测方案。
2. 从私信获取一次性 Preview 访问码及安装说明。
3. 从本仓库的 [Releases](https://github.com/hehetoshang/moke-preview-builds/releases) 下载适合当前平台的安装包。
4. 首次启动时输入访问码，完成当前设备的激活。

爱发电同时提供普通赞助和 Moke Preview 内测方案；是否包含 Preview 资格，以爱发电页面中的具体方案说明为准。通过其他方式进行普通赞助，也不代表自动获得 Preview 资格。

## 下载与安装

前往 [本仓库的 Releases 页面](https://github.com/hehetoshang/moke-preview-builds/releases)，在最新版本的 **Assets** 中选择对应平台的安装包。具体可用平台及安装要求以该版本的发布说明为准。

| 平台 | 架构 | 安装包 |
| --- | --- | --- |
| Windows | x64 | `.exe` / `.msi` |
| macOS | Apple Silicon / Intel | `.dmg`，分别选择 `macos-arm64` / `macos-x64` |
| Linux | x64 | `.AppImage` / `.deb` |
| Android | ARM64 | 已签名的 `.apk` |
| iOS / iPadOS | ARM64 | 未签名的 `.ipa`，需要自行签名安装 |
| HarmonyOS NEXT | ARM64 | 已签名的 `.hap` |

当前本仓库发布的 Preview 安装包未启用自动更新。需要更新时，请在 [本仓库的 Releases 页面](https://github.com/hehetoshang/moke-preview-builds/releases)下载新版本并按发布说明安装。

## 使用须知

- Preview 资格与当前设备绑定，启动时需要联网检查授权。
- 更换或重装设备时，需按应用提示迁移资格；无法迁移时请通过爱发电私信联系开发者处理。
- Preview 更新更快，可能包含未完成的功能、界面调整或兼容性问题，请提前备份重要数据。
- Preview 不包含稳定性承诺，不适合作为唯一的日常阅读环境。
- 公开稳定版仍在 [talebook/moke](https://github.com/talebook/moke) 免费发布，可从[稳定版下载页](https://github.com/talebook/moke/releases/latest)获取。

## 反馈问题与建议

遇到 Preview 功能异常、安装更新问题、兼容性问题或有体验建议时，请使用专用表单提交：

**[一键反馈 Moke Preview 问题](https://github.com/talebook/moke/issues/new?template=moke-preview.yml&labels=moke-preview)**

该入口会直接打开 `talebook/moke` 的 Moke Preview 反馈模板，并自动添加 `moke-preview` 标签。请填写 Preview 版本、运行平台、系统版本、问题描述、复现步骤以及预期与实际结果，可附上脱敏后的日志或截图。

GitHub Issue 内容公开可见，请勿提交访问码、订单凭证、账号密码、服务器密钥或其他敏感信息。涉及订单或访问码的问题，请通过爱发电私信联系开发者。

## 相关链接

- [墨客官网](https://website-ten-tan-60.vercel.app/)
- [墨客帮助文档](https://website-ten-tan-60.vercel.app/docs/)
- [Moke Preview 赞助内测说明](https://website-ten-tan-60.vercel.app/docs/guide/support#moke-preview-%E8%B5%9E%E5%8A%A9%E5%86%85%E6%B5%8B)
- [爱发电：Preview 与普通赞助](https://ifdian.net/a/hehetoshang)
- [查看已有 Preview 反馈](https://github.com/talebook/moke/issues?q=is%3Aissue%20label%3Amoke-preview)
- [墨客公开稳定版](https://github.com/talebook/moke)
