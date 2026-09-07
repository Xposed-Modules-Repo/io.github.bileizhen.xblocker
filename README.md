<div align="center">
  <img src="https://github.com/bileizhen/XBlocker/blob/main/docs/icon-512.png" width="96" alt="XBlocker">
  <h1>XBlocker</h1>
  <p>让 X 时间线少一点噪音。</p>

  [![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  [![Android 9+](https://img.shields.io/badge/Android-9%2B-blue.svg)](https://www.python.org/)
  [![LSPosed](https://img.shields.io/badge/LSPosed-legacy-orange.svg)](https://lsposed.org)
  [![GitHub](https://img.shields.io/badge/作者-bileizhen-blue)](https://github.com/bileizhen)

</div>

XBlocker 是一个 Android 原生 X 客户端（`com.twitter.android`）的 LSPosed 过滤模块。它在设备本地匹配规则，隐藏垃圾回复、推广内容和指定分类，并提供自定义关键词、正则、白名单、云端词库与诊断记录。

## 安装

1. 安装本仓库 Release 中的 APK（模块包名：`io.github.bileizhen.xblocker`）。
2. 在 LSPosed 启用 XBlocker，作用域只选择 X（`com.twitter.android`）。
3. 强行停止 X 后重新打开，在 XBlocker 的“运行诊断”确认连接。

0.2.4 起包名遵循 `io.github.bileizhen.xblocker`。从 0.2.3 或更早版本升级时，需要在 LSPosed 中为新包重新配置作用域；旧包确认停用后再卸载。

## 功能

- 按宿主接口自动选择过滤入口，兼容多个 X 版本。
- 关键词、正则、@用户名白名单、导入导出和规则测试。
- 同步 [x-comment-blocker](https://github.com/amahteru/x-comment-blocker) 词库并保留离线快照。
- 支持 HyperOS 超级岛、焦点通知和流体云状态展示；可配合 [HyperIsland](https://github.com/Xposed-Modules-Repo/io.github.hyperisland) 解锁系统限制。

## 源码与反馈

- 源码：https://github.com/bileizhen/XBlocker
- 问题反馈：https://github.com/bileizhen/XBlocker/issues

本模块与 X、LSPosed 及词库维护者没有隶属关系。
