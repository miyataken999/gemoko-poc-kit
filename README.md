# 🚀 gemoko-poc-kit

8割共通化ロジック ✕ agent.md 駆動の自律型 AI エージェント PoC キット

## 💡 概要
本リポジトリは、フロントエンド（AppSheet / stlite / PyScript）とバックエンド（GAS / Google Colab / Modal / Copilot CLI）を「2つの互換ブリッジ関数」で抽象化し、業務ロジックの8割を共通化する自律型AI開発・運用アーキテクチャの公式 PoC キットです。

## 🏗️ システム構成
- **UI / 入力**: AppSheet ✕ PostgreSQL (Supabase)
- **データハブ**: Supabase API ✕ 001_GEMINI GSS
- **オーケストレーター**: GitHub Actions（メンテナンスフリー）
- **ナレッジ / SQL検索**: Hugging Face Datasets (Parquet) ✕ DuckDB
- **自律実行 AI**: Copilot CLI ✕ Gemma 4 ✕ Gemini (gemi)

---
© 2026 All Rights Reserved. First published by Miyataken / gemi
