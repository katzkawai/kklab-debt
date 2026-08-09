# 日本の国債残高の推移

日本の普通国債残高（各年度末）と対GDP比を時系列でグラフ化したページです。

**公開ページ:** https://katzkawai.github.io/kklab-debt/

## データ

- 期間: 昭和40年度（1965）〜令和8年度（2026、見込み）
- 残高は2025年度まで実績、2026年度は当初予算ベースの見込み
- 対GDP比は2024年度まで実績、2025年度は実績残高÷政府経済見通し名目GDPの試算値、2026年度は見込み
- 内訳（建設国債・特例国債・復興債・その他）は2007年度以降の年次データ
- 出典: 財務省「[国債発行額の推移（実績ベース）](https://www.mof.go.jp/jgbs/reference/appendix/hakkou02.pdf)」「[最近20カ年間の年度末の国債残高の推移](https://www.mof.go.jp/jgbs/reference/appendix/zandaka01.pdf)」（[国債等関係諸資料](https://www.mof.go.jp/jgbs/reference/appendix/index.htm)）
- 残高は億円単位の原数値を兆円に換算（小数第1位まで）。「その他」は減税特例国債、国鉄・林野・交付税の承継債務借換国債、年金特例国債、GX経済移行債、子ども・子育て支援特例公債、半導体・AI債の合計

`data.csv` に同じデータを収録しています。

## 構成

- `index.html` — グラフページ本体（依存ライブラリなしの静的HTML + SVG）
- `data.csv` — 年度・普通国債残高（兆円）・対GDP比（%）・内訳（兆円）

## 作成について

このページは [Claude Code](https://claude.com/claude-code) で作成しました。財務省の公表資料からのデータ抽出、グラフの実装、GitHub Pagesへの公開までを Claude Code が行っています。
