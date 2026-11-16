# SwinjectStoryboard / Loop Engineering Codexプロンプト

AGENTS.mdとdocs/LOOP_ENGINEERING.mdおよび既存正本（README.md、SwinjectStoryboardの既存ソース/テスト、依存定義）を確認。未完了1件の存在を確かめ、現状→仮説→最小実装→テスト→結果分類→次タスク決定を1回実行。候補: ユーザー固有の既存issue/テスト失敗に再現根拠がある場合のみ小変更を1件。未完了の証拠がなければNO_TASK、環境不足ならBLOCKED_ENV。

検証: 当該Xcode/Swift toolchainが存在する場合の既存のテスト。非互換はBLOCKED_ENV。上流OSSの仕様・ライセンス・依存を無許可で一括更新しない。開発タスクがなければNO_TASK。。

必須報告：task_id、変更ファイル、検証コマンド/結果、分類、未検証範囲、次タスク。実装や検証の証拠がなければPASS禁止。自動再試行や公開、無限ループを行わない。
