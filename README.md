# Mole App

English · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

Official documentation and community support for **Mole for Mac** and **Mole for Windows**.

The Mac and Windows apps are paid native desktop apps, and license purchases help fund development and updates. This repository is for docs, questions and feedback. It doesn't contain app source code. The [Mole CLI](https://github.com/tw93/Mole) is still free and open source.

## Get Mole

| App | Requirements | Download | User guide |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 or later, Apple Silicon or Intel | [Mac website](https://mole.fit/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Mac help](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 or Windows 11, x64 or ARM64 | [Windows website](https://mole.fit/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Windows help](https://mole.fit/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

Both apps bring cleanup, app management, maintenance, disk analysis and live system status into one interface.

### Mole for Mac

Mole for Mac is a native SwiftUI app created and maintained by [Tw93](https://github.com/tw93), with quick tools in the menu bar.

![Mole for Mac cleanup screen](https://mole.fit/img/en/clean.jpg)

| Tool | What you can do | Guide |
| --- | --- | --- |
| Clean | Review app and browser caches, logs and developer build files before choosing what to remove | [Mac cleaner](https://mole.fit/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Software | Uninstall apps, review their leftovers, check for updates and manage startup items | [App management](https://mole.fit/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Optimize | Run macOS maintenance, use Clean Screen or Keep Screen On | [Mac maintenance](https://mole.fit/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Analyze | Find large files and folders with a disk treemap, reveal them in Finder or move selected items to Trash | [Disk analysis](https://mole.fit/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Status | View CPU, memory, storage, network and temperature readings, with selected metrics in the menu bar | [System monitor](https://mole.fit/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### AI cleanup

Mole for Mac 1.16.0 includes AI Cleanup & Care inside Clean. It reviews caches, old versions, old sessions, cleanable worktrees and idle command-line tools from Claude Code, Codex, Cursor and other AI tools. Caches start selected, while sessions and tools need your review. Memories, plans and skills are excluded. For local models, only Ollama models unused for a month are listed, for you to select and remove through Ollama. See the [AI cleanup guide](https://mole.fit/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai) for details.

### Start on your Mac

1. Download the DMG from the Mac website above, drag Mole into Applications and open it. If you already use Homebrew, `brew install --cask mole-app` installs the Mac app.
2. Run a scan and review the results before removing anything. If Mole reports missing Full Disk Access, follow the permissions guide below and relaunch it.
3. After buying, open the license panel with `Cmd + Shift + L`, paste the key from the Dodo Payments email and click Activate.

[Mac articles](https://mole.fit/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Mac release notes](https://mole.fit/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Selected Mac guides

- [Mole CLI vs Mac App](https://mole.fit/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): how the free terminal tool and paid native app differ.
- [Is Mole Safe for Mac?](https://mole.fit/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): what goes to Trash, what is removed permanently and what stays protected.
- [What Is System Data on Mac?](https://mole.fit/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): find what takes up space before deleting anything.
- [Review Mac Uninstall Leftovers](https://mole.fit/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): check file ownership and shared data before removal.
- [Delete Ollama and LM Studio Models](https://mole.fit/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): separate downloaded models, caches and personal data.
- [Testing Mac Apps for Mole](https://mole.fit/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): what real installations and uninstall tests reveal.

### Mole for Windows

The Windows app keeps improving with each release.

![Mole for Windows cleanup screen](https://mole.fit/img/windows/clean.jpg)

[Windows articles](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Windows release notes](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## Feedback

- [Report a Mac app bug](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Report a Windows app bug](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [Suggest a feature](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [Ask a question or join a discussion](https://github.com/tw93/Mole-App/discussions)

Issues and discussions are public. For purchase, activation or refund questions, email [hi@mole.fit](mailto:hi@mole.fit). Send security reports through the [private reporting channel](.github/SECURITY.md).

For Mac diagnostics, open the Mole logo menu and choose Run Doctor. Send the report privately to [hi@mole.fit](mailto:hi@mole.fit), along with the app version and what happened.

For CLI bugs and feature requests, use [tw93/Mole](https://github.com/tw93/Mole/issues).

## FAQ

### Does a public GitHub repository mean the apps are open source?

This repository contains documentation and community feedback. Mac and Windows app source code is private. The [Mole CLI](https://github.com/tw93/Mole) is free and open source.

### Do I need to install the CLI to use the apps?

No. Mole for Mac and Mole for Windows are standalone desktop apps. Installing the CLI does not install either app.

### Are the apps free?

The apps use one-time licenses. Mole for Mac is **$19 USD for two Macs**, with no subscription and free updates, including major versions. The [official pricing page](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) has the current terms. Windows pricing and availability are on its product website. The open-source CLI is free.

### Can I try the Mac app before buying?

Scanning is free, and each paid tool has two trial runs. You can view disk analysis and system status without a license. The [Mac help center](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explains downloading, trying and activating the app.

### Can I move my Mac license to a new computer?

Open the license panel on the old Mac with `Cmd + Shift + L`, deactivate it, then activate the same key on the new Mac. If the old Mac is unavailable, sign in to the [Dodo Payments Customer Portal](https://customer.dodopayments.com/) with your purchase email and deactivate it there. Your device limit depends on the license you bought. The current edition covers two Macs.

### Where are my license key and invoice?

Search your inbox and spam folder for Dodo Payments, or sign in to the [Dodo Payments Customer Portal](https://customer.dodopayments.com/) with the email used at checkout to find the key, order and invoice. If you still need help, email [hi@mole.fit](mailto:hi@mole.fit) with your purchase email or Payment ID. Keep these details out of public issues.

### What if the Mac app is not right for me?

Email [hi@mole.fit](mailto:hi@mole.fit) within 14 days of purchase with your Payment ID or purchase email. The [refund policy](https://mole.fit/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) has the full terms.

### Does the Mac app upload my files or scan results?

Scanning and cleaning happen locally on your Mac. Mole does not upload file contents, file names or scan results, and its local operation log is not uploaded automatically. The [privacy policy](https://mole.fit/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explains license activation, updates and other features that contact online services.

### Why does Mole ask for Full Disk Access?

macOS restricts access to some app data. Full Disk Access lets Mole inspect those locations. Protected paths and your whitelist still apply, so granting access does not make every file a cleanup candidate. See the [permissions guide](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda).

### Can I restore files after Mac cleanup?

Uninstalled apps and their selected leftover files go to Trash and can be restored while they remain there. Cache cleanup is permanent by default, with a Trash option in Settings. Some maintenance actions remove data directly and have no undo. The [safety guide](https://mole.fit/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explains each operation.

### How do Mac updates and Preview features work?

Mole has an in-app updater, and the [official release notes](https://mole.fit/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) describe each release. Features marked Preview in the documentation require the Preview build until they reach a stable release.

### Can I use Mole with a keyboard or VoiceOver?

Mole supports keyboard navigation and VoiceOver. The treemap is visual, and you can browse the same files in the Largest items list with a keyboard or VoiceOver. See the [accessibility guide](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) for details and current limits.

### Which website is official?

**mole.fit** is the official website for the apps. Use the download links above for current packages. The free CLI lives at [tw93/Mole](https://github.com/tw93/Mole).

### Where can I find detailed instructions?

The [Mac documentation](https://mole.fit/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explains the tools and their safety rules. The [tested-app catalog](https://mole.fit/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) has installation, uninstall and leftover notes for individual apps. For setup, activation or troubleshooting, see the [Mac help center](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) or [Windows help center](https://mole.fit/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme). License terms are in the [terms of service](https://mole.fit/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).
