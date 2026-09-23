# 第4章草案への移行表

## 今回作成したもの

| 新構成 | 草案ファイル | 移行元・内容 |
|---|---|---|
| 4.0 この章の地図 | `section_00_map/section.tex` | `chapter4 draft/01_本文草案.md` の導入部をLaTeX化 |
| 4.1 差分と離散的な微積分 | `section_01_difference_calculus/section.tex` | 既存 `chapter_04_appendix/section_02_difference_calculus/section.tex` を移植 |
| 4.2 反復・不動点・非線形漸化式 | `section_02_iteration/section.tex` | 既存の力学系・メビウス変換・特殊関数型の翻訳部分を統合 |

## 次の移行予定

- 4.3 収束・安定性・漸近解析: `section_11_asymptotics`
- 4.4 離散と連続を結ぶ: `section_04_discrete_to_continuous`
- 4.5 近似を設計する漸化式: `section_05_newton_and_approximation`
- 4.6 線形漸化式と線形代数: `section_06_linear_algebra`
- 4.7 母関数: `section_09_generating_functions`
- 4.8 特殊関数への入口: `section_07_chebyshev` と `section_08_special_functions_bridge` を再編
- 4.9 直交多項式とさらに広がる構造: 特殊関数節から直交多項式・行列部分を分離
- 4.10 一般項がなくても数列を理解する: `section_12_combinatorics_probability` と `section_13_when_closed_forms_fail`
- 4.11 章の地図を閉じる: `section_14_closing_map`

## 方針

既存の `chapter_04_appendix` は現行版として保存する。新構成の草案が一通り確認できた段階で、必要な節だけ本体へ反映する。
