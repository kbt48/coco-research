# Confidential Computing Research

Confidential Computing に関する技術調査、設計整理、実証実験を管理するリポジトリです。対象技術ごとの調査と、技術を横断するテーマを整理して蓄積します。

## 調査一覧

| 対象 | 内容 |
|---|---|
| [Trustee](projects/trustee/README.md) | アーキテクチャ、Attestation、PoC の調査レポート |

対象技術の一覧と追加方法は [projects](projects/README.md) を参照してください。

## 現在の構成

```text
coco-research/
├── README.md
└── projects/
    ├── README.md
    └── trustee/
        ├── README.md
        └── reports/
            └── trustee-architecture-attestation-poc-report-2026-10-19.md
```

## 分類と拡張方針

`projects/` を対象技術ごとの入口とします。以下の拡張先は資料を追加する際に作成します。

| パス | 用途 |
|---|---|
| `projects/<project>/reports/` | 対象プロジェクト・製品・プラットフォームごとの調査レポート |
| `projects/<project>/experiments/<name>/` | 再現可能な検証の手順・設定・結果 |
| `projects/<project>/assets/` | 対象技術の画像・図・補足資料 |
| `topics/<topic>/` | Attestation、鍵管理など複数技術にまたがる概念・課題 |
| `comparisons/<subject>/` | 複数技術・製品・実装の比較 |
| `glossary/` | 複数レポートで共有する用語集 |
| `templates/` | 調査・検証に使用するテンプレート |

レポートの正本は一箇所に置き、他の分類からはリンクします。対象固有の検証はその対象の `experiments/` に置き、横断比較の手順・結果は該当する `comparisons/<subject>/` にまとめます。各ディレクトリの README は資料一覧と読み方を案内します。

## 文書の管理

- ディレクトリ名には英小文字とハイフンを使用します。
- レポート名は原則 `<subject>-YYYY-MM-DD.md` とし、調査時点を識別できるようにします。
- 本文には調査日、対象バージョンまたは commit、一次情報へのリンクを記録します。
- 技術の説明には必要に応じて Mermaid 図を使用します。
- 文書間の参照には相対リンクを使用します。
- 検証資料には実行条件、手順、結果、再現に必要な設定を記録します。
- 新しい対象を追加する際は、このページと `projects/README.md` の調査一覧を更新します。
