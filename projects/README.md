# 対象技術別の調査

対象プロジェクト・製品・プラットフォームごとの調査資料を管理します。

## 調査一覧

| 対象 | 資料 |
|---|---|
| [Confidential Containers](confidential-containers/README.md) | 全体構成・Pod 起動・Attestation・信頼境界・導入検証 |
| [Cloud API Adaptor / Peer Pods](cloud-api-adaptor/README.md) | remote hypervisor・PodVM・ネットワーク・資源管理・信頼境界 |
| [Trustee](trustee/README.md) | アーキテクチャ・Attestation・PoC 調査 |

## 新しい対象の追加

1. `projects/<project>/` に対象のディレクトリを作成します。
2. `README.md` に調査対象の概要、資料一覧、一次情報を記録します。
3. レポートを `reports/` に追加します。
4. 本ページとトップ README の調査一覧を更新します。

実証実験は対象配下の `experiments/<name>/`、画像や補足資料は `assets/` に必要に応じて追加します。新しい分類を増やす場合は、[トップ README の分類と拡張方針](../README.md#分類と拡張方針)に沿って配置します。

[リポジトリのトップへ](../README.md)
