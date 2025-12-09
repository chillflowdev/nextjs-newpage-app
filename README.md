# News Page App

## 📌 概要
Next.js の高度なルーティング（並列ルート、キャッチオール、インターセプトなど）を中心に学習したアプリです。  
複数のニュースカテゴリーを閲覧でき、動的ルーティングを多用しています。

## 🛠️ 技術スタック
- Next.js (App Router)
- Dynamic Routes / Catch-all Routes
- Parallel Routes
- Intercepting Routes
- Middleware
- Server Components
- Error Handling（error.js）

## 🎯 主な機能
- 複数カテゴリのニュース表示
- 動的リンクによるページ遷移
- 並列ルート構成による UI 分割
- インターセプトルートを使った詳細ページ表示
- error.js を用いたクライアント側でのエラーハンドリング

## 💡 学習ポイント
- App Router の高度なルーティングパターン
- Server Component によるデータ取得と Promise の扱い
- Middleware を用いたリクエスト検証
- error.js と `use client` の取り扱い
- 可能な限り Client Component を小さく保つ設計方針
