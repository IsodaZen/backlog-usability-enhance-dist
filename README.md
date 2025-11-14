# Backlog Usability Enhance

BacklogのWebインターフェースの使いやすくするChrome拡張機能です。

A Chrome extension that enhances the usability of Backlog web interface.

## 💻 対応サイト / Supported Sites

- `https://*.backlog.jp/*`
- `https://*.backlog.com/*`

## 📥 インストール方法 / Installation

1. **ファイルをダウンロード / Download Files**
   - [リリースページ](https://github.com/IsodaZen/backlog-usability-enhance-dist/releases)から最新版をダウンロード / Download the latest version from the releases page
   - ZIPファイルを解凍 / Extract the ZIP file

2. **Chrome拡張機能として読み込み / Load as Chrome Extension**
   - Chromeブラウザで `chrome://extensions/` を開く / Open `chrome://extensions/` in Chrome browser
   - 右上の「デベロッパーモード」をオンにする / Turn on "Developer mode" in the top right
   - 「パッケージ化されていない拡張機能を読み込む」をクリック / Click "Load unpacked"
   - 解凍したフォルダを選択 / Select the extracted folder

3. **設定 / Settings**
   - 拡張機能一覧で「Backlog Usability Enhance」の「詳細」をクリック / Click "Details" for "Backlog Usability Enhance" in the extensions list
   - 「拡張機能のオプション」から各機能の有効/無効を設定 / Configure each feature on/off in "Extension options"

または、拡張機能アイコンをクリックしてポップアップから設定も可能です。

Alternatively, you can access settings by clicking the extension icon in the popup.

## 🚀 機能 / Features

各機能の詳細な説明は [features.md](docs/features.md) をご覧ください。

For detailed information about each feature, please see [features.en.md](docs/features.en.md).

### 機能一覧 / Feature List

- **📋 [ボードアコーディオン機能](docs/features.md#ボードアコーディオン機能) / [Board Accordion Feature](docs/features.en.md#board-accordion-feature)**
  ステータス列の個別折りたたみ/展開で、作業中の列だけに集中できます
  Individual collapse/expand of status columns to focus only on working columns

- **⌨️ [ショートカットキー表示機能](docs/features.md#ショートカットキー表示機能) / [Shortcut Key Display Feature](docs/features.en.md#shortcut-key-display-feature)**
  Backlog標準ショートカットキーが視覚的に表示され、キーボード操作が効率化されます
  Backlog standard shortcut keys are visually displayed to improve keyboard operation efficiency

- **⏸️ [課題Pending機能](docs/features.md#課題pending機能) / [Issue Pending Feature](docs/features.en.md#issue-pending-feature)**
  ボード上で課題を一時保留状態にして、優先度の管理ができます
  Temporarily hold issues on the board for priority management

- **📝 [プルリクエストフォーマット自動挿入機能](docs/features.md#プルリクエストフォーマット自動挿入機能) / [PR Format Auto-Insert Feature](docs/features.en.md#pr-format-auto-insert-feature)**
  プルリクエスト作成時にプロジェクト別のテンプレートを自動挿入して、統一されたフォーマットで効率的に作成できます
  Automatically insert project-specific templates when creating pull requests for efficient and consistent formatting

- **🔗 [課題コメントURLコピー機能](docs/features.md#課題コメントurlコピー機能) / [Issue Comment URL Copy Feature](docs/features.en.md#issue-comment-url-copy-feature)**
  課題やプルリクエストの各コメントにURLコピーボタンを追加し、ワンクリックでコメントの直リンクをクリップボードにコピーできます
  Add URL copy buttons to each comment on issues and pull requests, allowing you to copy direct links to comments with one click

## 🐛 問題の報告 / Bug Reports

バグや改善要望がございましたら、以下の方法でお知らせください：

Please report bugs or feature requests using the following methods:

1. **GitHub Issues**（推奨 / Recommended）
   - [Issues ページ](https://github.com/IsodaZen/backlog-usability-enhance-dist/issues)で新しいIssueを作成 / Create a new issue on the Issues page
   - 問題の詳細、再現手順、環境情報を記載 / Include problem details, reproduction steps, and environment information

2. **問題報告時に含めてほしい情報 / Information to Include in Bug Reports**
   - Chrome のバージョン / Chrome version
   - 拡張機能のバージョン / Extension version
   - 問題が発生したBacklogのURL（プライベート情報は除く） / Backlog URL where the issue occurred (excluding private information)
   - 問題の詳細な説明と再現手順 / Detailed description and reproduction steps
   - エラーメッセージ（あれば） / Error messages (if any)

## ❓ よくある質問 / FAQ

**Q: 拡張機能が動作しません / Extension is not working**

A: 以下をご確認ください / Please check the following:
- 対応サイト（*.backlog.jp, *.backlog.com）でアクセスしているか / Are you accessing supported sites (*.backlog.jp, *.backlog.com)?
- 拡張機能が有効になっているか / Is the extension enabled?
- ページを再読み込みしてみてください / Try reloading the page

**Q: 設定が保存されません / Settings are not saved**

A: Chromeの同期設定がオンになっていることを確認し、拡張機能の権限で「ストレージ」が許可されていることをご確認ください。

Please ensure Chrome sync is enabled and that the extension has "Storage" permission.

**Q: キーボードショートカットが効きません / Keyboard shortcuts don't work**

A: 他の拡張機能やWebページのショートカットと競合している可能性があります。設定画面でショートカットキー機能を一度無効→有効にしてみてください。

There may be conflicts with other extensions or webpage shortcuts. Try disabling and re-enabling the shortcut key feature in settings.

## 🔒 プライバシー・セキュリティ / Privacy & Security

- この拡張機能はBacklogページ上でのみ動作します / This extension operates only on Backlog pages
- 設定情報はChromeの同期ストレージに保存されます / Settings are stored in Chrome sync storage
- 外部サーバーにデータを送信することはありません / No data is sent to external servers
- 個人情報や課題内容を収集することはありません / No personal information or issue content is collected

## ⚠️ 免責事項 / Disclaimer

- この拡張機能は非公式のツールです / This extension is an unofficial tool
- Backlogの仕様変更により動作しなくなる可能性があります / May stop working due to Backlog specification changes
- 使用は自己責任でお願いします / Use at your own risk
- 重要な作業の前には動作確認を行ってください / Please test functionality before important work

## 📄 ライセンス / License

MIT License
