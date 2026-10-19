# Confidential Containers

Confidential Containers（CoCo）の全体システム、Kubernetes／Kata Containers との接続、TEE 内での処理、Attestation と秘密情報配布を調査します。

## レポート

| 確認日 | レポート |
|---|---|
| 2026-10-19 | [Confidential Containers 全体システム俯瞰技術調査](reports/confidential-containers-system-architecture-2026-10-19.md) |

全体の読み方は上記レポート、Trustee 単体の構築・鍵・API の詳細は [Trustee の調査一覧](../trustee/README.md) を参照してください。レポートの正本を対象ごとに管理し、他の領域からリンクします。

## 一次情報

- [Confidential Containers 公式 docs](https://confidentialcontainers.org/docs/)
- [CoCo コミュニティ・リリースノート](https://github.com/confidential-containers/confidential-containers)
- [CoCo Helm Charts](https://github.com/confidential-containers/charts)
- [Kata Containers](https://github.com/kata-containers/kata-containers)
- [guest-components](https://github.com/confidential-containers/guest-components)
- [Trustee](https://github.com/confidential-containers/trustee)

## 配置

- `reports/`：確認日と参照リビジョンを記録した調査レポート。
- `experiments/<name>/`：今後実施する検証の手順・設定・実測結果。
- `assets/`：今後必要となる図・補足資料。

[対象技術一覧へ](../README.md) · [リポジトリのトップへ](../../README.md)
