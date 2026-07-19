# nokku

**AI-native product studio by a solo developer** — 設計から実装・運用までのフルループを、AIエージェントを開発フローの中核に組み込んで高速に回しています。

## What I build

- 🤖 **[nokku-ops-architecture](https://github.com/nokku-dev/nokku-ops-architecture)** — 自律型AIエージェント組織の設計ドキュメント。Dispatcher / Executor / Auditor / Reviewer / Briefer の5役割を Mac mini 上に常駐させ、タスク処理〜コードレビュー〜週次監査まで無人で回す仕組み（本体リポは private・設計は公開）
- 🛠 **[dev-loop-kit](https://github.com/nokku-dev/dev-loop-kit)** — 1リポで完結する AI 開発ループのテンプレート。設計判断（ADR）・文脈・検証ゲートを repo に閉じ込め、**上記の組織基盤なしで**同じ回し方を再現できる形にしたもの。auto-merge の条件で自律度を調整でき、開発中の知見が repo に書き戻る経路を含む
- 📱 **knockon** — if-then 習慣形成アプリ（React Native / Expo）— 開発中
- 🔍 **Tazna** — AIエージェントの意思決定ポイントを抽出・可視化し、人間の判断を支援するデスクトップツール（Tauri / TypeScript）— 開発中

## Background

モバイル・VRゲーム開発 6年（Unity / C#、テクニカルリード）。週1本ペースの高速リリース体制と、KPI設計〜A/Bテストのデータドリブンな改善サイクルを創業期から構築。現在はフリーランス。

設計判断は ADR（判断ログ）として蓄積し、現在 58 本。「なぜその選択をしたか」を残すことで、AIエージェントが過去の判断と矛盾しない実装を出せる状態を維持しています。
