# Arcade Link

Arcade Link is an open-source project that helps arcade games implement features such as **self-service recording**, **online queueing**, and **retrieval of replays (WIP)**. Some parts of the project are still being organized and have not been open-sourced yet.

[中文文档](https://github.com/ArcadeLink/.github/blob/master/profile/README_cn.md).

# Introduction

## Project Structure

- `Aircade` is the app used by the project, used for downloading recordings and interacting with the arcade side.
- `ApiServer` is the backend of the project, used for handling user authentication and queueing functions.
- `Aircade.Web` is the web version of the app, only the queueing function is retained.
- `ArcadeLink.UI` provides the UI for the arcade side, used to display recording status and queueing information.

## Project Progress

- [x] Self-service recording on the arcade side
- [x] Automatic live streaming on bilibili on the arcade side
- [x] Online queueing on the arcade side
- [x] Android App
- [ ] Wechat-Miniprogram
- [ ] iOS App
- [ ] Retrieval of replays

When all(except iOS) progress archieved, this project will be open-sourced.

# Contribution Guide

## Join

Any types of developers is needed! We mainly need wechat-miniprogram, Kotlin and DotNet developers right now.

## Commit

We welcome all contributions! If you wish to contribute code, please follow the steps below:

1. Fork this repository
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push your changes to the branch: `git push origin my-new-feature`
5. Submit a new Pull Request

If you have any questions, feel free to submit an issue.

# Contact Us

If you have any questions or feedback, please send an email to `haotrip05@gmail.com`
