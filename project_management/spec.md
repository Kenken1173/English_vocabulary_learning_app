# このファイルには作業を進めていくためのTODOを記載し、それに対する現在の進捗状況を記録します。

## 進捗サマリー

| フェーズ | タスク | ステータス |
|---|---|---|
| Phase 0 | plan.md に企画書初版を作成 | ✅ 完了 (2026-03-17) |
| Phase 0 | 塾長ヒアリング実施・要件確定 | 🔲 未着手 |
| **Phase 0.5** | **環境構築** | **🔲 未着手** |
| Phase 1 | 画面設計（UIラフ案） | 🔲 未着手 |
| Phase 2 | DB設計 | 🔲 未着手 |
| Phase 3 | MVP実装 | 🔲 未着手 |

---

## Phase 0.5：環境構築 タスク詳細

### ① Node.js / npm の確認
- [x] Node.js がインストールされているか確認（推奨：v20以上）
- [x] バージョン確認コマンド：`node -v` / `npm -v`

### ② Reactプロジェクトの作成
- [x] Vite + React でプロジェクトを作成
- [x] コマンド：`npm create vite@latest . -- --template react`

### ③ Tailwind CSS の導入
- [x] Tailwind CSS をインストール・設定
- [x] 動作確認（簡単なスタイルが当たるか）

### ④ Supabase プロジェクトの作成
- [x] Supabase アカウント作成・新規プロジェクト作成
- english_vocaburary プロジェクトを新規作成
- [x] Supabase クライアントライブラリをインストール：`npm install @supabase/supabase-js`
- [ ] 環境変数（`.env`）に接続情報を設定

### ⑤ PWA 設定
- [ ] `vite-plugin-pwa` を導入
- [ ] manifest.json の基本設定（アプリ名・アイコン）

### ⑥ 動作確認
- [ ] `npm run dev` でローカル起動確認
- [ ] Supabase への接続テスト

---

## 現在のフォーカス

**Phase 0：要件定義 ＋ Phase 0.5：環境構築（並行して進める）**

- 環境構築はヒアリング前でも着手可能
- 実装作業は、ヒアリングで未確定事項が埋まってから開始する
