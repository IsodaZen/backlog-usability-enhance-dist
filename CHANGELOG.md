<!--
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
-->
# Changelog


## [0.3.1] - 2025-11-15

### Fixed
- 遅延読み込みされたコメントにURLコピーボタンが付与されない
- ダッシュボード画面でショートカットキー表示機能がエラー
- .github/ディレクトリがbacklog-usability-enhance-distにデプロイされていない

### Documentation
- ドキュメント構成を改善し、機能詳細を`docs/features.md`に集約
- `README.md`を機能一覧とリンクのみに簡略化し、見通しを向上

## [0.3.0] - 2025-11-11

### Added
- **課題コメントURLコピー機能** - 課題詳細ページとプルリクエストページの各コメントにURLコピーボタンを追加

### Technical
- 包括的なユニットテスト（76テストケース）実装

## [0.2.0] - 2025-08-07

### Added
- **プルリクエストフォーマット自動挿入機能** - プルリクエスト作成時にプロジェクト別のテンプレートを自動挿入

### Improved
- ボード画面のPending状態アイコンのUI改善

## [0.1.0] - 2025-07-30

### Added
- **拡張機能設定画面** - 各機能の有効/無効を切り替え可能な設定画面
- **ボードアコーディオン機能** - ステータス列の個別折りたたみ/展開機能
- **ショートカットキー表示機能** - Backlog標準ショートカットキーの視覚的表示
- **課題Pending機能** - ボード画面での独自Pending状態管理機能
- **ツールバーポップアップ機能** - 拡張機能アイコンからの設定画面アクセス

### Technical
- TypeScript + Chrome Extension基盤
- Vitest + Testing Library による統合テスト環境
- ESLint + Prettier による品質管理
- Vite による高速ビルド環境
