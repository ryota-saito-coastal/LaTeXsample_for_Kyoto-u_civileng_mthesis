# LaTeXsample_for_Kyoto-u_civileng_mthesis

## 概要
このリポジトリは、**京都大学大学院 工学研究科 社会基盤工学専攻／都市社会工学専攻**の修士論文を
**LuaLaTeX** 環境で執筆するためのサンプルプロジェクトです。

- **作成者**：サイトウ リョウタ（2024年度 山上研究室 修士修了）
- **最終更新日**：2025年2月19日

> **すいちゃんは今日もかわいい～～！**  
> アイドル“星街すいせい”のスピリットをちょっぴり加味した LaTeX テンプレートになっています☆

---

## 特徴
1. **LuaLaTeX** でのコンパイルを想定  
2. **京都大学土木系**の修士論文フォーマットに対応（章番号、図表キャプションの和文など）
3. **デバッグモード**を実装  
   - `\submissionmode=0` で背景を黒、文字を白にして目を労わるモード  
4. **日本語フォント**に MS Mincho、英語フォントに Times New Roman を指定  
5. **パッケージ**：`amsmath`, `luatexja`, `graphicx`, `booktabs` など、基本的なものをあらかじめ読み込み済み

---

## ファイル構成

```plaintext
LaTeXsample_for_Kyoto-u_civileng_mthesis/
├─ README.md                         // 本ファイル
├─ mthesis_ja_sample_suisei.tex      // メインのLaTeXソース
├─ img/
│   ├─ title/kyodai.png              // タイトルページ用ロゴの例
│   └─ chap2/computer_tokui_boy.png  // サンプル画像
└─ （必要に応じ .bib などを追加）

