# Cloud API Adaptor / Peer Pods

Confidential Containers の Peer Pods を実現する cloud-api-adaptor（CAA）について、Kata remote hypervisor、PodVM、ネットワーク、資源管理、Attestation と信頼境界を調査します。

## レポート

| 確認日 | レポート | 参照ソース |
|---|---|---|
| 2026-10-21 | [cloud-api-adaptor アーキテクチャ・セキュリティ技術調査](reports/cloud-api-adaptor-architecture-security-2026-10-21.md) | main 2c15720 / v0.23.0 |

構成・起動・通信・initdata の図と、14 項目の検証計画を収録しています。文献・コード調査であり、実クラウド／TEE での検証は未実施です。参照したソースの commit、blob SHA、URL は [ソース一覧](assets/cloud-api-adaptor-sources-2026-10-21.json) で追跡できます。

## 関連調査

- [Confidential Containers の全体調査](../confidential-containers/README.md)
- [Trustee の調査](../trustee/README.md)

## 一次情報

- [cloud-api-adaptor](https://github.com/confidential-containers/cloud-api-adaptor)
- [CoCo 公式 docs](https://confidentialcontainers.org/docs/)

## 配置

- `reports/`：調査日と参照 revision を固定したレポート。
- `assets/`：参照ソース一覧等の補足資料。
- `experiments/<name>/`：今後実施する検証の手順・設定・実測結果。

[対象技術一覧へ](../README.md) · [リポジトリのトップへ](../../README.md)
