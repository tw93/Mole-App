# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · 日本語 · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

**Mole for Mac** と **Mole for Windows** の公式ドキュメントとコミュニティサポートです。

Mac 版と Windows 版は有料のネイティブデスクトップアプリで、ライセンスの購入は開発とアップデートの支えになります。このリポジトリはドキュメント、質問、フィードバック用で、アプリのソースコードは含まれていません。[Mole CLI](https://github.com/tw93/Mole) はこれまでどおり無料のオープンソースです。

## Mole を入手

| アプリ | 動作環境 | ダウンロード | ユーザーガイド |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 以降、Apple Silicon または Intel | [Mac 公式サイト](https://mole.fit/ja/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Mac ヘルプ](https://mole.fit/ja/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 または Windows 11、x64 または ARM64 | [Windows 公式サイト](https://mole.fit/ja/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Windows ヘルプ](https://mole.fit/ja/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

どちらのアプリも、クリーン、アプリ管理、メンテナンス、ディスク分析、リアルタイムのシステム状態をひとつの画面にまとめています。

### Mole for Mac

Mole for Mac は [Tw93](https://github.com/tw93) が開発・運営するネイティブの SwiftUI アプリで、メニューバーからもクイックツールを使えます。

![Mole for Mac のクリーン画面](https://mole.fit/img/ja/clean.jpg)

| ツール | できること | ガイド |
| --- | --- | --- |
| クリーン | アプリやブラウザのキャッシュ、ログ、開発用のビルドファイルを確認してから、削除するものを選べます | [Mac クリーナー](https://mole.fit/ja/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| アプリ | アプリのアンインストールと残留ファイルの確認、アップデートの確認、ログイン項目の管理ができます | [アプリ管理](https://mole.fit/ja/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 最適化 | macOS のメンテナンスを実行でき、画面を拭くや画面オン維持も使えます | [Mac メンテナンス](https://mole.fit/ja/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| 分析 | ディスクのツリーマップで大きなファイルやフォルダを見つけ、Finder で表示したり、選んだ項目をゴミ箱に移動したりできます | [ディスク分析](https://mole.fit/ja/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| ステータス | CPU、メモリ、ストレージ、ネットワーク、温度を確認でき、選んだ項目をメニューバーに表示することもできます | [システムモニター](https://mole.fit/ja/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### AI クリーン

Mole for Mac 1.16.0 の正式版には、クリーン内に AI クリーン&ケアが含まれています。Claude Code、Codex、Cursor などの AI ツールが残したキャッシュ、古いバージョン、古いセッション、整理できる worktree、使われていないコマンドラインツールを確認できます。キャッシュは最初から選択され、セッションとツールはあなたの確認が必要です。メモリ、プラン、スキルは対象外です。ローカルモデルについては、1か月使われていない Ollama モデルだけが一覧に出て、選択して Ollama 経由で削除します。詳しくは [AI クリーンのガイド](https://mole.fit/ja/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai)をご覧ください。

### Mac で使い始める

1. 上の Mac 公式サイトから DMG をダウンロードし、Mole を「アプリケーション」フォルダにドラッグして開きます。すでに Homebrew を使っている場合は、`brew install --cask mole-app` でも Mac アプリをインストールできます。
2. スキャンを実行し、何かを削除する前に結果を確認します。フルディスクアクセスが不足していると表示されたら、下の権限ガイドに従って設定し、Mole を開き直してください。
3. 購入後は `Cmd + Shift + L` でライセンスパネルを開き、Dodo Payments のメールに記載のキーを貼り付けて「有効化」をクリックします。

[Mac の記事](https://mole.fit/ja/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Mac のリリースノート](https://mole.fit/ja/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Mac のおすすめガイド

- [Mole CLI と Mac アプリの違い](https://mole.fit/ja/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 無料のターミナルツールと有料のネイティブアプリの違いです。
- [Mole は Mac で安全に使えますか](https://mole.fit/ja/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): ゴミ箱に入るもの、完全に削除されるもの、保護されるものを説明します。
- [Mac の「システムデータ」とは](https://mole.fit/ja/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 削除する前に、容量を使っているものを見つけます。
- [Mac のアンインストール後の残留ファイルを確認する](https://mole.fit/ja/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 削除前にファイルの所有者と共有データを確認します。
- [Ollama と LM Studio のモデルを削除する](https://mole.fit/ja/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): ダウンロードしたモデル、キャッシュ、個人データを切り分けます。
- [Mole のための Mac アプリ検証](https://mole.fit/ja/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): 実際のインストールとアンインストールのテストでわかったことです。

### Mole for Windows

Windows 版はリリースごとに改良を続けています。

![Mole for Windows のクリーン画面](https://mole.fit/img/windows-ja/clean.jpg)

[Windows の記事](https://mole.fit/ja/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Windows のリリースノート](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## フィードバック

- [Mac アプリの不具合を報告](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Windows アプリの不具合を報告](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [機能を提案](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [質問する、またはディスカッションに参加](https://github.com/tw93/Mole-App/discussions)

Issue とディスカッションは公開されます。購入、有効化、返金に関するご質問は [hi@mole.fit](mailto:hi@mole.fit) までメールでご連絡ください。セキュリティに関する報告は[非公開の報告窓口](.github/SECURITY.md)から送ってください。

Mac の診断情報が必要な場合は、Mole のロゴメニューから「Doctorを実行」を選び、レポートをアプリのバージョンと状況を添えて [hi@mole.fit](mailto:hi@mole.fit) に非公開で送ってください。

CLI の不具合や機能要望は [tw93/Mole](https://github.com/tw93/Mole/issues) へお願いします。

## FAQ

### GitHub リポジトリが公開されているということは、アプリはオープンソースですか

このリポジトリにあるのはドキュメントとコミュニティからのフィードバックです。Mac 版と Windows 版のアプリのソースコードは非公開です。[Mole CLI](https://github.com/tw93/Mole) は無料のオープンソースです。

### アプリを使うのに CLI のインストールは必要ですか

いいえ。Mole for Mac と Mole for Windows は単体で動作するデスクトップアプリです。CLI をインストールしても、どちらのアプリもインストールされません。

### アプリは無料ですか

アプリは買い切りのライセンスです。Mole for Mac は **2台の Mac で $19 USD** で、サブスクリプションはなく、メジャーバージョンを含むアップデートも無料です。最新の条件は[公式の料金ページ](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)でご確認ください。Windows 版の価格と提供状況は、その製品サイトに掲載されています。オープンソースの CLI は無料です。

### 購入前に Mac アプリを試せますか

スキャンは無料で、有料ツールはそれぞれ2回まで試用できます。ディスク分析とシステムの状態は、ライセンスなしで表示できます。ダウンロード、試用、有効化の手順は [Mac ヘルプセンター](https://mole.fit/ja/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)で説明しています。

### 新しい Mac にライセンスを移せますか

古い Mac で `Cmd + Shift + L` を押してライセンスパネルを開いて無効化し、同じキーを新しい Mac で有効化してください。古い Mac が手元にない場合は、購入時のメールアドレスで [Dodo Payments カスタマーポータル](https://customer.dodopayments.com/)にサインインし、そこで無効化できます。台数の上限は購入したライセンスによって異なり、現在販売中のエディションは2台の Mac に対応しています。

### ライセンスキーと領収書はどこにありますか

受信トレイと迷惑メールフォルダで Dodo Payments を検索するか、購入時のメールアドレスで [Dodo Payments カスタマーポータル](https://customer.dodopayments.com/)にサインインすると、キー、注文、領収書を確認できます。それでも見つからない場合は、購入時のメールアドレスか Payment ID を添えて [hi@mole.fit](mailto:hi@mole.fit) にご連絡ください。これらの情報は公開 Issue には書かないでください。

### Mac アプリが合わなかった場合はどうなりますか

購入から14日以内に、Payment ID か購入時のメールアドレスを添えて [hi@mole.fit](mailto:hi@mole.fit) にメールしてください。詳しい条件は[返金ポリシー](https://mole.fit/ja/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)に記載しています。

### Mac アプリはファイルやスキャン結果をアップロードしますか

スキャンとクリーンはすべて Mac 上でローカルに実行されます。Mole はファイルの内容、ファイル名、スキャン結果をアップロードせず、ローカルの操作ログも自動ではアップロードされません。ライセンスの有効化、アップデート、その他オンラインのサービスに接続する機能については、[プライバシーポリシー](https://mole.fit/ja/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)で説明しています。

### なぜ Mole はフルディスクアクセスを求めるのですか

macOS は一部のアプリデータへのアクセスを制限しています。フルディスクアクセスを許可すると、Mole はそれらの場所を確認できるようになります。保護されたパスとあなたのホワイトリストは引き続き適用されるので、許可してもすべてのファイルがクリーンの対象になるわけではありません。[権限ガイド](https://mole.fit/ja/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda)をご覧ください。

### Mac のクリーン後にファイルを復元できますか

アンインストールしたアプリと、選んだ残留ファイルはゴミ箱に移動され、ゴミ箱に残っている間は復元できます。キャッシュのクリーンは既定では完全に削除されますが、設定でゴミ箱に移動するよう変更できます。一部のメンテナンス操作はデータを直接削除し、元に戻せません。操作ごとの違いは[安全ガイド](https://mole.fit/ja/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)で説明しています。

### Mac アプリのアップデートとベータ版の機能はどうなっていますか

Mole にはアプリ内アップデーターがあり、各リリースの内容は[公式のリリースノート](https://mole.fit/ja/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)に記載しています。ドキュメントで Preview と記された機能は、安定版に入るまでベータ版でのみ利用できます。

### キーボードや VoiceOver で Mole を使えますか

Mole はキーボード操作と VoiceOver に対応しています。ツリーマップは視覚的な表示ですが、同じファイルを「最大の項目」リストでキーボードや VoiceOver から確認できます。詳細と現時点の制限は[アクセシビリティガイド](https://mole.fit/ja/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)をご覧ください。

### どのサイトが公式ですか

アプリの公式サイトは **mole.fit** です。最新のパッケージは上のダウンロードリンクから入手してください。無料の CLI は [tw93/Mole](https://github.com/tw93/Mole) にあります。

### 詳しい説明はどこにありますか

[Mac のドキュメント](https://mole.fit/ja/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)では各ツールと安全ルールを説明しています。[検証済みアプリ一覧](https://mole.fit/ja/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)には、個別のアプリのインストール、アンインストール、残留ファイルのメモがあります。セットアップ、有効化、トラブルシューティングは [Mac ヘルプセンター](https://mole.fit/ja/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)または [Windows ヘルプセンター](https://mole.fit/ja/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)をご覧ください。ライセンス条件は[利用規約](https://mole.fit/ja/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)に記載しています。
