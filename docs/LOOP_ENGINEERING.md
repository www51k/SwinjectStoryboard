# Loop Engineering — SwinjectStoryboard

対象: 古いStoryboard依存注入OSSの参考/フォーク。上流由来のコードを保護。

正本: README.md、SwinjectStoryboardの既存ソース/テスト、依存定義

## 1タスク1サイクル
1. AGENTS.md、README、Issue、既存差分、環境、停止/承認状態を確認する。
2. READY表示がなくても、既存の未完了に根拠があれば独立した小タスク1件を選ぶ。例: ユーザー固有の既存issue/テスト失敗に再現根拠がある場合のみ小変更を1件。
3. 仮説・再現条件・最小変更・合格条件を定義し、コード修正を実施する。
4. テスト/検証: 当該Xcode/Swift toolchainが存在する場合の既存のテスト。非互換はBLOCKED_ENV。未実施の理由を残す。
5. 実測でPASS/BLOCKED_INPUT/BLOCKED_ENV/TEST_INFRA_ERROR/TASK_FAILを分類する。
6. 変更ファイル・検証結果・ブロッカー・次タスクを引き継ぐ。

## 注意点
上流OSSの仕様・ライセンス・依存を無許可で一括更新しない。開発タスクがなければNO_TASK。。権限不足であれば別案件へ。無限再試行、既存コードの無関係変更、勝手な公開をしない。OSスケジューラーがなければ定期起動はしない。監視/文書更新は実装成果ではない。
