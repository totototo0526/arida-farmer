# Agent Workspace State

## Current Status
- プロジェクト: 有田市ふるさと納税 農家様向けマニュアル (arida-farmer)
- 状態: 安定稼働中。先日、本番環境特有の画像拡大機能（lightbox）によるUI崩れ（チェックボックス表示）の問題を解決済み。

## Core Philosophy
- シンプルなMarkdownによる管理と自動ビルド。
- カスタムの機能（サーバー側でのlightbox付与など）を使用する場合は、それに対応するCSS（`src/custom.css`）を適切に保守する。

## タスクリスト
- [x] 画像に表示されるチェックボックスの削除（CSS対応）
- [x] 製造報告ドキュメントの「希望申込」への統合とファイル整理
