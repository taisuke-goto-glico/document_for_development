## 1.要件定義書:「何を作るか」を決める重要な文書

主な役割：お客様の要望が技術的に実現できるかどうかを検討

- 事業部が作成する要件の技術的な実現可能性を検証
- 非機能要件（性能、セキュリティ）の具体的な要件を検討&追加
- ユースケースの技術的な実現方法を調査&検討
    - ベンダーとの技術的な対話の際の判断材料として活用

## 2.基本設計書:「どのように作るか」の大枠を決める文書

主な役割：技術的なレビュアー

- インフラ構成の妥当性確認
- API設計の評価（REST原則、セキュリティ要件との整合性）
- 画面遷移の技術的な実現可能性の確認
- パフォーマンス・拡張性や性能・スケーラビリティの観点からの評価

## 3.詳細設計書: プログラムの設計図

主な役割：技術的な評価者

- クラス設計の妥当性確認
- シーケンス図の論理的な整合性チェック
- 保守性、拡張性の観点からの評価
- 技術的な制約との整合性確認

## 4.データベース設計書

主な役割：設計レビュアー

- ER図の論理的整合性の確認
- インデックス設計の妥当性評価
- パフォーマンスの観点からの検証
- データ整合性制約の確認

## ５.テスト計画書: 検査項目

主な役割：技術的なテスト項目の定義者

- 技術的な観点からのテストケース追加
- テスト環境の要件定義
- 負荷テスト、セキュリティテストの計画策定
- テストデータの技術的な妥当性確認

## 6.プロジェクト計画書: 開発全体の計画を示す文書

主な役割：技術的な実現可能性の評価者

- 技術的なタスクの工数見積もり
- 技術的なリスクの特定と対策提案
- 開発フェーズの順序の妥当性確認

## 7.運用・保守設計書: システムを運用・維持するための計画書

主な役割：技術的な運用要件の定義者

- 監視項目の技術的な定義
- バックアップ/リカバリ手順の技術的な妥当性確認
- 障害時の技術的な対応手順の確認
- パフォーマンスチューニング計画の評価

## 重要なポイント：

1. レビュー時の主なチェックポイント
    - 技術的な実現可能性
    - コストと期間の妥当性
    - セキュリティリスク
    - 保守性と拡張性
    - パフォーマンス要件との整合性
2. 効率的な関与方法
    - 各ドキュメントのテンプレート作成
    - チェックリストの整備
    - レビュー会議での重点ポイントの明確化
    - 技術的な判断基準の文書化
3. コミュニケーションの工夫
    - 非エンジニアにもわかる説明の準備
    - 技術的な課題の可視化
    - 代替案の提示
    - リスクの定量的な説明
