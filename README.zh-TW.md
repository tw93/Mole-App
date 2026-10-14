# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · 繁體中文 · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

這裡放 **Mole for Mac** 和 **Mole for Windows** 的使用說明和社群回饋。

Mac 和 Windows App 都是原生桌面應用，付費授權支援後續開發和更新，這裡歡迎提問和回饋，不包含 App 原始碼，[Mole CLI](https://github.com/tw93/Mole) 繼續免費開源。

## 下載 Mole

| App | 系統要求 | 下載 | 使用指南 |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 及以上，Apple Silicon 或 Intel | [Mac 官網](https://mole.fit/tw/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Mac 幫助](https://mole.fit/tw/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 或 Windows 11，x64 或 ARM64 | [Windows 官網](https://mole.fit/tw/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Windows 幫助](https://mole.fit/tw/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

兩個 App 都提供清理、軟體管理、維護、磁碟分析和即時系統狀態。

### Mole for Mac

Mole for Mac 是 [Tw93](https://github.com/tw93) 開發和維護的原生 SwiftUI App，選單列也能檢視指標和開啟常用工具。

![Mole for Mac 清理頁面](https://mole.fit/img/zh-hant/clean.jpg)

| 工具 | 可以做什麼 | 指南 |
| --- | --- | --- |
| 清理 | 先看 App 與瀏覽器快取、日誌和開發工具的建置檔案，再選擇要刪除的內容 | [Mac 清理](https://mole.fit/tw/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 軟體 | 解除安裝 App 並檢查殘留，也能檢查軟體更新、管理啟動項 | [軟體管理](https://mole.fit/tw/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 最佳化 | 按需維護系統，也可以用清潔螢幕和保持常亮 | [Mac 維護](https://mole.fit/tw/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 分析 | 用樹狀圖找到大檔案和目錄，在 Finder 中顯示或把選中的內容移到垃圾桶 | [磁碟分析](https://mole.fit/tw/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 狀態 | 檢視 CPU、記憶體、磁碟、網路和溫度，也能把選定的指標放到選單列 | [系統狀態](https://mole.fit/tw/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### AI 清理 · Preview

Preview 版的清理頁裡有 AI 清理與維護，可以整理 Claude Code、Codex、Cursor 等工具留下的快取、舊版本、舊會話、可清理的 worktree 和閒置命令列工具。快取預設勾上，會話和工具由你確認，記憶、計劃和技能檔案不在清理範圍裡，本地模型只列出一個月沒用的 Ollama 模型，由你勾選後透過 Ollama 刪除，詳見 [AI 清理說明](https://mole.fit/tw/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai)。

### 在 Mac 上開始使用

1. 從上面的 Mac 官網下載 DMG，把 Mole 拖進應用程式目錄並開啟，已經在用 Homebrew 的話，也可以執行 `brew install --cask mole-app` 安裝 Mac App。
2. 掃描後先核對結果，再決定刪除什麼，提示缺少完全磁碟訪問權限時，按下面的權限說明設定並重新開啟 Mole。
3. 購買後按 `Cmd + Shift + L` 開啟授權面板，貼上 Dodo Payments 郵件裡的金鑰，點選啟用。

[Mac 文章](https://mole.fit/tw/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Mac 更新日誌](https://mole.fit/tw/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### 精選 Mac 指南

- [Mole CLI 和 Mac App 有什麼區別](https://mole.fit/tw/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，看看免費終端機工具與付費原生 App 各自能做什麼。
- [Mole 清理安全嗎](https://mole.fit/tw/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，哪些內容進垃圾桶，哪些會永久刪除，哪些受到保護。
- [Mac 系統資料是什麼](https://mole.fit/tw/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，先找到佔空間的內容，再決定要不要刪。
- [解除安裝殘留為什麼需要檢查](https://mole.fit/tw/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，刪除前確認檔案歸屬和共用資料。
- [刪除 Ollama 和 LM Studio 模型](https://mole.fit/tw/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，分清下載的模型、快取和個人資料。
- [為 Mole 實測 Mac 軟體](https://mole.fit/tw/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，實際安裝和解除安裝以後，才能看到哪些檔案留下來了。

### Mole for Windows

Windows 版持續迭代。

![Mole for Windows 清理頁面](https://mole.fit/img/windows-zh-hant/clean.jpg)

[Windows 文章](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Windows 更新日誌](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## 回饋

- [回饋 Mac App 問題](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [回饋 Windows App 問題](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [提出功能建議](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [提問或參與討論](https://github.com/tw93/Mole-App/discussions)

Issue 和討論是公開的，購買、啟用或退款問題可以發郵件到 [hi@mole.fit](mailto:hi@mole.fit)，安全問題走[私下回饋渠道](.github/SECURITY.md)。

需要 Mac 診斷資訊時，可以在 Mole logo 選單裡選擇執行診斷，把報告、App 版本和遇到的問題私下寄到 [hi@mole.fit](mailto:hi@mole.fit)。

CLI 的問題和功能建議放在 [tw93/Mole](https://github.com/tw93/Mole/issues)。

## 常見問題

### GitHub 倉庫公開，是不是意味著 App 開源了？

這裡公開的是使用說明和社群回饋，Mac 與 Windows App 的原始碼沒有公開，[Mole CLI](https://github.com/tw93/Mole) 免費開源。

### 用 App 之前需要安裝 CLI 嗎？

不需要，Mole for Mac 和 Mole for Windows 都可以獨立執行，安裝 CLI 也不會安裝這兩個 App。

### App 是免費的嗎？

App 採用一次性付費授權，Mole for Mac 目前為 **19 美元，可啟用兩台 Mac**，沒有訂閱，包含後續免費更新和大版本升級，[官方定價說明](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)提供目前條款，Windows 的價格和可用狀態以它的官網為準，開源 CLI 免費。

### Mac App 可以先試用嗎？

掃描免費，每個付費工具可以試用兩次，不需要授權也能檢視磁碟分析和系統狀態，下載、試用和啟用方式可以看 [Mac 幫助中心](https://mole.fit/tw/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### 換 Mac 後還能用原來的授權嗎？

可以，在舊 Mac 上按 `Cmd + Shift + L` 開啟授權面板並停用，再用同一個金鑰在新 Mac 上啟用，舊機器已經不在時，可以用購買時使用的電子郵件登入 [Dodo Payments 客戶入口網站](https://customer.dodopayments.com/)停用它，裝置數量按購買時的版本計算，目前在售版支援兩台 Mac。

### 授權金鑰和發票在哪裡？

先在收件箱和垃圾郵件裡搜尋 Dodo Payments，也可以用購買時的電子郵件登入 [Dodo Payments 客戶入口網站](https://customer.dodopayments.com/)檢視金鑰、訂單和發票，仍然找不到的話，把購買時使用的電子郵件或 Payment ID 發到 [hi@mole.fit](mailto:hi@mole.fit)，這些資訊不要放在公開 Issue 裡。

### Mac App 不適合我，可以退款嗎？

購買後 14 天內，帶上 Payment ID 或購買時使用的電子郵件發郵件到 [hi@mole.fit](mailto:hi@mole.fit)，完整條款見[退款政策](https://mole.fit/tw/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### Mac App 會上傳我的檔案和掃描結果嗎？

掃描和清理都在 Mac 本機完成，Mole 不會上傳檔案內容、檔名或掃描結果，本機操作日誌也不會自動上傳，啟用、更新和其他聯網功能會聯絡哪些服務，可以看[隱私政策](https://mole.fit/tw/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### 為什麼會需要完全磁碟訪問權限？

macOS 限制了部分 App 資料的讀取，完全磁碟訪問權限讓 Mole 能檢查這些位置，不代表所有檔案都會被列入清理，受保護路徑和你的白名單仍然生效，具體設定可以看[權限說明](https://mole.fit/tw/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda)。

### Mac 清理後還能恢復檔案嗎？

解除安裝的 App 和選中的殘留檔案會移到垃圾桶，檔案還在那裡時可以恢復，快取清理預設永久刪除，也可以在設定裡改為移到垃圾桶，部分維護操作會直接刪除資料，無法撤銷，[安全說明](https://mole.fit/tw/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)按操作列出了這些區別。

### Mac App 怎麼更新，Preview 功能什麼時候能用？

Mole 內建更新功能，每次發布的變化可以看[官方更新日誌](https://mole.fit/tw/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，文件裡標記為 Preview 的功能，需要使用 Preview 版，直到它們進入正式版。

### 可以只用鍵盤或 VoiceOver 操作嗎？

可以，Mole 支援鍵盤導航和 VoiceOver，樹狀圖用來展示空間分佈，同樣的檔案也會列在旁邊，方便用鍵盤或 VoiceOver 瀏覽，操作方式和目前的限制見[無障礙說明](https://mole.fit/tw/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。

### 哪個網站是官方的？

App 官網是 **mole.fit**，最新安裝包可以從上面的下載入口獲取，免費 CLI 放在 [tw93/Mole](https://github.com/tw93/Mole)。

### 更詳細的說明在哪裡？

[Mac 功能文件](https://mole.fit/tw/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)介紹各工具和安全規則，[實測軟體目錄](https://mole.fit/tw/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)有具體 App 的安裝、解除安裝和殘留說明。下載、啟用和排查問題可以看 [Mac 幫助中心](https://mole.fit/tw/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)或 [Windows 幫助中心](https://mole.fit/tw/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)，授權條款見[使用條款](https://mole.fit/tw/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)。
