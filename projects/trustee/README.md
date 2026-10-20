# Trustee

Trustee に関する技術調査と実証実験を管理します。

## レポート

| 日付 | レポート |
|---|---|
| 2026-10-19 | [Trustee アーキテクチャ・Attestation・PoC 調査](reports/trustee-architecture-attestation-poc-report-2026-10-19.md) |

調査対象、用語、構成図、参照元は各レポートに記載します。

Kubernetes、Kata、PodVM と Trustee の接続を俯瞰する場合は、[Confidential Containers の全体システム調査](../confidential-containers/reports/confidential-containers-system-architecture-2026-10-19.md)を参照してください。

鍵配布停止とロード済み秘密の扱い、再証明の限界、既存環境の失効・交換は、横断テーマの[常駐型TEEのリスクと対応](../../topics/tee-lifecycle-security/reports/long-running-tee-inference-security-2026-10-21.md)で扱います。

## 一次情報

- [Trustee 公式リポジトリ](https://github.com/confidential-containers/trustee)
- [guest-components 公式リポジトリ](https://github.com/confidential-containers/guest-components)

対象バージョンや参照 commit は各レポートで確認してください。

## 配置

- `reports/`：調査レポート。
- `experiments/<name>/`：検証の手順・設定・結果。検証資料を追加する際に作成します。
- `assets/`：画像・図・補足資料。必要に応じて作成します。

[対象技術一覧へ](../README.md) · [リポジトリのトップへ](../../README.md)
