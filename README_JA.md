# No.53 v1.0 公開版

著者：Ryutaro Yonezu — Independent Researcher  
日付：2026-11-04  
区分：限定的数学プレプリント／計算機援用証明

主張は一般化部分語順序の交互2値列 `(a,b)^m`（任意の `a>b>=1`, `m>=1`）に限る。任意の合成列の単峰性を証明したとは主張しない。

- 数学：ユーザー提供のClaude v0.4再監査で MODEL / PROOF-Q2 / PROOF-MIDRANK / PROOF-BASE / PROOF-TRANSFER / COMPUTATION はPASS。
- 人間査読：未実施。AI監査を人間査読と混同しない。
- 新規性：INCONCLUSIVE。Chen・Zhang（2026）の全文未照合。
- Windows PowerShell 5.1：v0.4の実機PASS未確認。
- ライセンス：All rights reserved。
- `frozen_v0.4/` 内の旧HOLD記載は監査履歴としてそのまま保存。今回のv1.0公開許可とは矛盾しない。

再現は `frozen_v0.4/` から `python -I verify_sha256_v0.4.py`、2本のQ²検証器、および基底検証器を実行。Python 3.10以上と無償のSymPyが必要。`python -O`は禁止（assertが検証の一部）。

公開済みのURLやDOIは実物のGitHub/Zenodo確認後にだけ追記する。
