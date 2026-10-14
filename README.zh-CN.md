# Mole App

[English](README.md) · 简体中文 · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

这里放 **Mole for Mac** 和 **Mole for Windows** 的使用说明和社区反馈。

Mac 和 Windows App 都是原生桌面应用，付费授权支持后续开发和更新，这里欢迎提问和反馈，不包含 App 源码，[Mole CLI](https://github.com/tw93/Mole) 继续免费开源。

## 下载 Mole

| App | 系统要求 | 下载 | 使用指南 |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 及以上，Apple Silicon 或 Intel | [Mac 官网](https://mole.fit/zh/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Mac 帮助](https://mole.fit/zh/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 或 Windows 11，x64 或 ARM64 | [Windows 官网](https://mole.fit/zh/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Windows 帮助](https://mole.fit/zh/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

两个 App 都提供清理、软件管理、维护、磁盘分析和实时系统状态。

### Mole for Mac

Mole for Mac 是 [Tw93](https://github.com/tw93) 开发和维护的原生 SwiftUI App，菜单栏也能查看指标和打开常用工具。

![Mole for Mac 清理页面](https://mole.fit/img/ch/clean.jpg)

| 工具 | 可以做什么 | 指南 |
| --- | --- | --- |
| 清理 | 先看 App 与浏览器缓存、日志和开发工具的构建文件，再选择要删除的内容 | [Mac 清理](https://mole.fit/zh/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 软件 | 卸载 App 并检查残留，也能检查软件更新、管理启动项 | [软件管理](https://mole.fit/zh/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 优化 | 按需维护系统，也可以用清洁屏幕和保持常亮 | [Mac 维护](https://mole.fit/zh/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 分析 | 用树状图找到大文件和目录，在 Finder 中显示或把选中的内容移到废纸篓 | [磁盘分析](https://mole.fit/zh/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 状态 | 查看 CPU、内存、磁盘、网络和温度，也能把选定的指标放到菜单栏 | [系统状态](https://mole.fit/zh/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### AI 清理 · Preview

Preview 版的清理页里有 AI 清理与维护，可以整理 Claude Code、Codex、Cursor 等工具留下的缓存、旧版本、旧会话、可清理的 worktree 和闲置命令行工具。缓存默认勾上，会话和工具由你确认，记忆、计划和技能文件不在清理范围里，本地模型只列出一个月没用的 Ollama 模型，由你勾选后通过 Ollama 删除，详见 [AI 清理说明](https://mole.fit/zh/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai)。

### 在 Mac 上开始使用

1. 从上面的 Mac 官网下载 DMG，把 Mole 拖进应用程序目录并打开，已经在用 Homebrew 的话，也可以运行 `brew install --cask mole-app` 安装 Mac App。
2. 扫描后先核对结果，再决定删除什么，提示缺少完全磁盘访问权限时，按下面的权限说明设置并重新打开 Mole。
3. 购买后按 `Cmd + Shift + L` 打开许可证面板，粘贴 Dodo Payments 邮件里的密钥，点击激活。

[Mac 文章](https://mole.fit/zh/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Mac 更新日志](https://mole.fit/zh/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### 精选 Mac 指南

- [Mole CLI 和 Mac App 有什么区别](https://mole.fit/zh/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，看看免费终端工具与付费原生 App 各自能做什么。
- [Mole 清理安全吗](https://mole.fit/zh/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，哪些内容进废纸篓，哪些会永久删除，哪些受到保护。
- [Mac 系统数据是什么](https://mole.fit/zh/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，先找到占空间的内容，再决定要不要删。
- [卸载残留为什么需要检查](https://mole.fit/zh/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，删除前确认文件归属和共用数据。
- [删除 Ollama 和 LM Studio 模型](https://mole.fit/zh/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，分清下载的模型、缓存和个人数据。
- [为 Mole 实测 Mac 软件](https://mole.fit/zh/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，实际安装和卸载以后，才能看到哪些文件留下来了。

### Mole for Windows

Windows 版持续迭代。

![Mole for Windows 清理页面](https://mole.fit/img/windows-ch/clean.jpg)

[Windows 文章](https://mole.fit/zh/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Windows 更新日志](https://mole.fit/zh/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## 反馈

- [反馈 Mac App 问题](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [反馈 Windows App 问题](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [提出功能建议](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [提问或参与讨论](https://github.com/tw93/Mole-App/discussions)

Issue 和讨论是公开的，购买、激活或退款问题可以发邮件到 [hi@mole.fit](mailto:hi@mole.fit)，安全问题走[私下反馈渠道](.github/SECURITY.md)。

需要 Mac 诊断信息时，可以在 Mole logo 菜单里选择运行诊断，把报告、App 版本和遇到的问题私下发到 [hi@mole.fit](mailto:hi@mole.fit)。

CLI 的问题和功能建议放在 [tw93/Mole](https://github.com/tw93/Mole/issues)。

## 常见问题

### GitHub 仓库公开，是不是意味着 App 开源了？

这里公开的是使用说明和社区反馈，Mac 与 Windows App 的源码没有公开，[Mole CLI](https://github.com/tw93/Mole) 免费开源。

### 用 App 之前需要安装 CLI 吗？

不需要，Mole for Mac 和 Mole for Windows 都可以独立运行，安装 CLI 也不会安装这两个 App。

### App 是免费的吗？

App 采用一次性付费授权，Mole for Mac 当前为 **19 美元，可激活两台 Mac**，没有订阅，包含后续免费更新和大版本升级，[官方定价说明](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)提供当前条款，Windows 的价格和可用状态以它的官网为准，开源 CLI 免费。

### Mac App 可以先试用吗？

扫描免费，每个付费工具可以试用两次，不需要授权也能查看磁盘分析和系统状态，下载、试用和激活方式可以看 [Mac 帮助中心](https://mole.fit/zh/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### 换 Mac 后还能用原来的许可证吗？

可以，在旧 Mac 上按 `Cmd + Shift + L` 打开许可证面板并停用，再用同一个密钥在新 Mac 上激活，旧机器已经不在时，可以用购买邮箱登录 [Dodo Payments 客户门户](https://customer.dodopayments.com/)停用它，设备数量按购买时的版本计算，目前在售版支持两台 Mac。

### 许可证密钥和发票在哪里？

先在收件箱和垃圾邮件里搜索 Dodo Payments，也可以用购买时的邮箱登录 [Dodo Payments 客户门户](https://customer.dodopayments.com/)查看密钥、订单和发票，仍然找不到的话，把购买邮箱或 Payment ID 发到 [hi@mole.fit](mailto:hi@mole.fit)，这些信息不要放在公开 Issue 里。

### Mac App 不适合我，可以退款吗？

购买后 14 天内，带上 Payment ID 或购买邮箱发邮件到 [hi@mole.fit](mailto:hi@mole.fit)，完整条款见[退款政策](https://mole.fit/zh/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### Mac App 会上传我的文件和扫描结果吗？

扫描和清理都在 Mac 本机完成，Mole 不会上传文件内容、文件名或扫描结果，本机操作日志也不会自动上传，激活、更新和其他联网功能会联系哪些服务，可以看[隐私政策](https://mole.fit/zh/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### 为什么会需要完全磁盘访问权限？

macOS 限制了部分 App 数据的读取，完全磁盘访问权限让 Mole 能检查这些位置，不代表所有文件都会被列入清理，受保护路径和你的白名单仍然生效，具体设置可以看[权限说明](https://mole.fit/zh/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda)。

### Mac 清理后还能恢复文件吗？

卸载的 App 和选中的残留文件会移到废纸篓，文件还在那里时可以恢复，缓存清理默认永久删除，也可以在设置里改为移到废纸篓，部分维护操作会直接删除数据，无法撤销，[安全说明](https://mole.fit/zh/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)按操作列出了这些区别。

### Mac App 怎么更新，Preview 功能什么时候能用？

Mole 内置更新功能，每次发布的变化可以看[官方更新日志](https://mole.fit/zh/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，文档里标记为 Preview 的功能，需要使用 Preview 版，直到它们进入正式版。

### 可以只用键盘或 VoiceOver 操作吗？

可以，Mole 支持键盘导航和 VoiceOver，树状图用来展示空间分布，同样的文件也会列在旁边，方便用键盘或 VoiceOver 浏览，操作方式和目前的限制见[无障碍说明](https://mole.fit/zh/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### 哪个网站是官方的？

App 官网是 **mole.fit**，最新安装包可以从上面的下载入口获取，免费 CLI 放在 [tw93/Mole](https://github.com/tw93/Mole)。

### 更详细的说明在哪里？

[Mac 功能文档](https://mole.fit/zh/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)介绍各工具和安全规则，[实测软件目录](https://mole.fit/zh/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)有具体 App 的安装、卸载和残留说明。下载、激活和排查问题可以看 [Mac 帮助中心](https://mole.fit/zh/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)或 [Windows 帮助中心](https://mole.fit/zh/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，授权条款见[使用条款](https://mole.fit/zh/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。
