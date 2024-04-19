# Arcade Link

Arcade Link 是一个帮助街机游戏实现 **自助录像**、**自动直播**、**电子排卡** 以及 **调取回放（WIP）** 等功能的开源项目. 部分项目仍然在整理中，尚未开源.

# 简介

## 项目结构

- `Aircade` 为项目使用的 App, 用于下载录像以及与街机端交互.
- `ApiServer` 为项目的后端, 用于处理用户认证以及排卡等功能.
- `Aircade.Web` 为 App 的网页端, 仅保留了排卡功能.
- `ArcadeLink.UI` 提供街机端的 UI, 用于显示录像状态以及排卡信息.

## 项目进度

- [x] 街机端自助录像
- [x] 街机端自动直播
- [x] 街机端电子排卡
- [x] Android App
- [ ] 微信小程序
- [ ] iOS App
- [ ] 调取回放

在所有进度(iOS除外)完成后，本项目将会开源在此组织下. 如无特殊说明，所有项目遵循 GPL-3.0 协议开源

## 安装

### 二进制文件

#### Windows

双击 `Aircade.exe` 即可运行.

#### Linux / MacOS

```bash
chmod +x ./Aircade
./Aircade
```

# 贡献指南

## 加入

欢迎任何人加入本项目! 本项目急缺微信小程序开发者，iOS开发者和.NET开发者. 有意请加入QQ群聊 `257585826`

## 提交

我们欢迎所有的贡献！如果您希望贡献代码，请遵循以下步骤：

1. Fork 此仓库
2. 创建您的特性分支：`git checkout -b my-new-feature`
3. 提交您的更改：`git commit -am 'Add some feature'`
4. 将您的更改推送到分支：`git push origin my-new-feature`
5. 提交一个新的 Pull Request

如果您有任何问题，请随时提交 issue.

# 联系我们

如果您有任何问题或反馈，请发送邮件至 `haotrip05@gmail.com`
