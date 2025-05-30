# Arcade Link

![Profile Image@2x](https://github.com/ArcadeLink/.github/assets/22652631/95901332-a6a0-454a-a3ae-fe0f1c40ddd1)

### README

测试场地（重庆城市英雄大坪店）关门了，一起做这个项目的曾经的一哥们现在也变成了大伞兵，沉溺在自己偏执的思想中去了（虽然他本身不会写啥程序，基本上只是个运维，纯菜，很多时候运维都是我自己去做的）

目前只有我和开发本项目安卓app的开发者在活跃，测试地点也已经关门，确实没有进行的条件了。如有想继续完善本项目的，欢迎加QQ群，私信或在群聊中告诉我，我会把部分尚未开源的代码权限给你，并且把对应项目的归档状态解除，以便发出pr

---

Arcade Link is an open-source project that helps arcade games implement features such as **self-service recording**, **online queueing**, and **retrieval of replays (WIP)**. Some parts of the project are still being organized and have not been open-sourced yet.

[中文文档](https://github.com/ArcadeLink/.github/blob/master/profile/README_cn.md).

# Introduction

## Project Structure

### Server-Side

An api server is needed for auth and queue.
- `ApiServer` is the lagecy version backend of the project, used for handling user authentication and queueing functions.
- `ArcadeLink.Api` is the latest version.

### Client-Side

Client applications generate QR code for queue, and offer video download to player.
- `Aircade` is the android app used by the project, used for downloading recordings and interacting with the arcade side. Developed with compose.
- `ArcadeLink.Air` is the flutter app offer lightweight service to players.
- `Aircade.Web` is the web version of the app, only the queueing function is retained. For more features like changing nickname please head to `ArcadeLink.Air`

### Arcade-Side

This is a terminal for players to sign in(join queue) and record videos.
- `ArcadeLink.UI` provides the UI for the arcade side, used to display recording status and queueing information.

## Project Progress

- [x] Self-service recording on the arcade side
- [x] Automatic live streaming on bilibili on the arcade side
- [x] Online queueing on the arcade side
- [x] Android App
- [ ] Wechat-Miniprogram
- [ ] iOS App
- [ ] Retrieval of replays

When all(except iOS) progress archieved, this project will be fully open-sourced.

# Contribution Guide

## Join

Any types of developers is needed! We mainly need Kotlin and DotNet developers.

## Commit

We welcome all contributions! If you wish to contribute code, please follow the steps below:

1. Fork this repository
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push your changes to the branch: `git push origin my-new-feature`
5. Submit a new Pull Request

If you have any questions, feel free to submit an issue.

# Contact Us

If you have any questions or feedback, please send an email to `i@bg8lrr.site`
