# dot-is-dot

ChatGPT dotへの作業委任・進捗管理・引き継ぎのための横断リポジトリです。

このリポジトリ自体は各ゲームの実装リポジトリではありません。実装コード・ゲーム個別の確定仕様は原則としてそれぞれのリポジトリを正本とし、ここには全体方針・横断タスク・作業記録を置きます。

> 初期資料 v0.1 / 2026-10-14 時点の会話から整理。記載された作業候補は、すべてが未着手・実行承認済みという意味ではありません。実行前に現状確認が必要です。

## 読む順番

1. [docs/HANDOFF.md](docs/HANDOFF.md) — 背景、確定方針、プロジェクト概要、制約
2. [docs/BACKLOG.md](docs/BACKLOG.md) — 1か月のPro＋dot活用に向けた作業候補
3. [docs/OPERATIONS.md](docs/OPERATIONS.md) — Issue・Codex・レビュー・安全な作業運用
4. [docs/3D_ASSET_SPECS.md](docs/3D_ASSET_SPECS.md) — NEKOLPOS 3D小物の共通仕様、給餌器・給水器・全自動猫トイレの外観と拡張用構造（元画像は別途共有）
5. [docs/DOT_3D_TASK_PROMPT.md](docs/DOT_3D_TASK_PROMPT.md) — dotにそのまま渡せる3D制作依頼文
6. [docs/DOT_3D_LITTER_TASK_PROMPT.md](docs/DOT_3D_LITTER_TASK_PROMPT.md) — 全自動猫トイレのdot向け制作依頼文
7. [Issue #1（自動給餌器）](https://github.com/kissho222/dot-is-dot/issues/1) / [Issue #2（自動給水器）](https://github.com/kissho222/dot-is-dot/issues/2) / [Issue #3（全自動猫トイレ）](https://github.com/kissho222/dot-is-dot/issues/3) — モデル制作タスク

## 当面の優先順位

- **Pro加入後〜10月23日**：管理環境の整備、ネコルポスの3D小物制作、開発支援環境、必要な試作。
- **10月24日以降**：発売予定の『Warrior Cats: Clans of the Forest』日本語化の技術調査・翻訳準備に優先的にリソースを配分。
- **翻訳作業環境の確立後**：3D制作、ネコルポス本体開発の支援、新作ゲーム試作に配分を戻す。

日付は日本時間。発売日・Pro加入日・利用枠の状況は実行時に再確認すること。

## 運用の基本

- **docs**：仕様、背景、採用理由、保留条件を記録する。
- **GitHub Issues**：具体的な調査・制作・実装タスクを管理する。
- **Codexへの実装指示**：対象ゲームのリポジトリでIssueを作成し、必ず **codex-task** ラベルを付ける。Issueの作成とCodexの実行は区別する。
- **dot**：作業状況の確認、成果物制作、調査、タスク分解、Issue整備、結果報告を担当する。
- **人間の最終確認**：大きな仕様変更、破壊的操作、公開、配布、課金、重要なマージは所有者の承認を得る。

## 注意事項

このリポジトリは**公開**です。秘密情報、個人情報、認証情報、第三者ゲームから抽出した原文・アセット、非公開の外注資料などを投入しないでください。

## dotの最初の仕事

各文書を読み、既存プロジェクトと現状を照合する。重複・完了済み・未確認タスクを区別し、Issue構成、優先順位、依存関係、作業上の不明点を提案する。検証せずに既存仕様やタスク状態を確定扱いしない。
