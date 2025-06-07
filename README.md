# Sudoku_Solver_Generator_v6.0
 Version6.0 2025.September 公開予定

# GNPX v6 HP:
 en: https://gidoo-code.github.io/Sudoku_Solver_Generator_v6/<br>
 jp: https://gidoo-code.github.io/Sudoku_Solver_Generator_v6_jp/<br>
<br><br>
# Sudoku_Solver_Generator v6
![GNPX](./images0/GNPX_start.png)<br>

## 0. GNPX v5.8- は、v6.0のベータ版<br>
 ｖ6.0の機能確認中<br><br><br>


## 1. GNPX v6.0 は、メジャーアップデート<br>
 GNPX v6 は、プログラムを全般的に再構成しました。機能整理と論理性を高めたので、コードは読み易くなりました。<br>
 新たに解析アルゴリズムを追加しました。今後も追加の予定です。<br>
 開発支援機能を追加しました。通常の実行場面では見えませんが、アルゴリズム開発時に機能します（アルゴリズムの誤り検出）。<br>
 PU向けのいくつかの機能を追加しました(GNPXのコードを読んでください)。<br>


## 2. 数独解析アルゴリズム　の追加<br>
 論理を説明するイメージ図を用いて解説します。（具体的では本質が理解しづらい）<br>
 (1) 数独解析における "Locked"<br>
 (2) ALSの拡張(AnLS)、アルゴリズムの開発<br>
 (3) eLink、ネットワークの拡張<br>
 (4) Fish ファミリーの整理<br>
 (5) SueDeCoq ファミリーの整理（Franken_SueDeCoq、Finned_Franken_SueDeCoq)<br>
 (6) DeathBlossomのアルゴリズム考察<br>
 (7) Subsetアルゴリズム<br>
 (8) Fireworkアルゴリズム<br>
 (9) Exocet(Junior/Senior) アルゴリズム(開発中)<br>

## 3. GNPX v6 プログラム<br>
 (1) UIにpageを用いて、処理内容を分類・整理<br>
 (2) 多くの解析アルゴリズムを改良。 全アルゴリズムをビット表現化(Bit81をUInt128に変更)<br>
 (3) バックグラウンドで全解を求め、アルゴリズムの正誤をモニター（試行錯誤法を用いています）。<br>
 (4) 問題作成機能を強化（パターン指定、ブロック1固定で数独の全問題を生成。並列処理。おおよそ900万パズル）。<br>

## 3. GNPX v6 VSプロジェクト＆C#ソース<br>
 (1) VisualStudioプロジェクト(C#ソース)は、Sudoku_Solver_Generator_v6 からダウンロードできます。<br>