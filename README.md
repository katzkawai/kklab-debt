# 日本の国債残高の推移

日本の普通国債残高（各年度末）と対GDP比を時系列でグラフ化したページです。

**公開ページ:** https://katzkawai.github.io/kklab-debt/

## データ

- 期間: 昭和40年度（1965）〜令和8年度（2026、見込み）
- 2024年度までは実績、2025年度は補正後見込み、2026年度は当初予算ベースの見込み
- 出典: 財務省「[国債発行額の推移（実績ベース）](https://www.mof.go.jp/jgbs/reference/appendix/hakkou02.pdf)」（[国債等関係諸資料](https://www.mof.go.jp/jgbs/reference/appendix/index.htm)）
- 残高は億円単位の原数値を兆円に換算（小数第1位まで）

`data.csv` に同じデータを収録しています。

## 構成

- `index.html` — グラフページ本体（依存ライブラリなしの静的HTML + SVG）
- `data.csv` — 年度・普通国債残高（兆円）・対GDP比（%）

## 作成について

このページは [Claude Code](https://claude.com/claude-code) で作成しました。財務省の公表資料からのデータ抽出、グラフの実装、GitHub Pagesへの公開までを Claude Code が行っています。
