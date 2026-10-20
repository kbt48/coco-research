# TEEのライフサイクルとセキュリティ

TEEをいつ起動し、何を保持し、どう交換・失効させるかを、アプリケーション、Attestation、秘密情報配布を横断して調査します。

## レポート

| 確認日 | レポート |
|---|---|
| 2026-10-21 | [常駐型TEEで推論を提供する場合のリスクと対応](reports/long-running-tee-inference-security-2026-10-21.md) |

常駐時間と攻撃機会の関係、信頼境界、再証明・鍵配布停止の限界、テナント分離、クリーンな交換、受入試験を扱います。実機での検証結果とは区別した文献・実装調査です。

## 関連する技術

- [Confidential Containers](../../projects/confidential-containers/README.md)：CVM・Kata・ゲストコンポーネントを含む全体構成。
- [Trustee](../../projects/trustee/README.md)：証拠検証、ポリシー、秘密情報の配布。

[横断テーマ一覧へ](../README.md) · [リポジトリのトップへ](../../README.md)
