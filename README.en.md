<div align="center">
  <img src="https://github.com/bileizhen/XBlocker/blob/main/.github/img/icon-512.png" width="96" alt="XBlocker">
  <h1>XBlocker</h1>
  <p>Less noise in your X timeline.</p>

  <p><a href="README.md">简体中文</a> | <strong>English</strong></p>

  [![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  [![Android 9+](https://img.shields.io/badge/Android-9%2B-blue.svg)](https://developer.android.com/about/versions/pie)
  [![LSPosed](https://img.shields.io/badge/LSPosed-API_101-orange.svg)](https://lsposed.org)
  [![GitHub](https://img.shields.io/badge/Author-bileizhen-blue)](https://github.com/bileizhen)

</div>

XBlocker is an LSPosed filtering module for the native X client on Android (`com.twitter.android`). It matches rules locally on your device to hide spam replies, promoted content and selected categories, with custom keywords, regex rules, an allowlist, a cloud rule list and diagnostics.

## Installation

1. Install the APK from the releases of this repository (module package: `io.github.bileizhen.xblocker`).
2. Enable XBlocker in LSPosed with X (`com.twitter.android`) as its only scope.
3. Force-stop X and reopen it, then check the connection under "Diagnostics" in XBlocker.

Since 0.2.4 the package name follows `io.github.bileizhen.xblocker`. When upgrading from 0.2.3 or earlier, configure the scope for the new package in LSPosed again, and uninstall the old package after confirming that the new one works.

## Features

- Selects the filtering entry based on the host interfaces, compatible with multiple X versions.
- Keywords, regex, an @username allowlist, import/export and rule testing.
- Syncs the [x-comment-blocker](https://github.com/amahteru/x-comment-blocker) rule list and keeps an offline snapshot.
- HyperOS Super Island, focus notification and Fluid Cloud status display; can be combined with [HyperIsland](https://github.com/Xposed-Modules-Repo/io.github.hyperisland) to unlock system restrictions.

## Source and feedback

- Source: https://github.com/bileizhen/XBlocker
- Issues: https://github.com/bileizhen/XBlocker/issues

This module is not affiliated with X, LSPosed or the rule-list maintainers.

## Views

<div align="center">

![Views](https://count.getloli.com/@bileizhen_XBlocker?name=bileizhen_XBlocker&theme=original-new&padding=7&offset=0&align=center&scale=1&pixelated=1&darkmode=auto)

</div>
