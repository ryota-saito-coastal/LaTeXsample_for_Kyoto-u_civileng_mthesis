# LaTeXsample_for_Kyoto-u_civileng_mthesis

## 概要
このリポジトリは、**京都大学大学院 工学研究科 社会基盤工学専攻／都市社会工学専攻**の修士論文を
**LaTeX** (**LuaLaTeX**) 環境で執筆するためのサンプルプロジェクトです．

- **作成者**：サイトウ リョウタ（2024年度 山上研究室 修士修了）
- **最終更新日**：2025年2月19日

---

## 特徴
1. **LuaLaTeX** でのコンパイルを想定
2. **京都大学土木系**の修士論文フォーマットに対応（章番号，図表キャプションの和文など）
3. **デバッグモード**を実装
   - `\submissionmode=0` で背景を黒，文字を白にできます
4. **日本語フォント**にMS Mincho，英語フォントに Times New Romanを指定
5. **パッケージ**：`amsmath`, `luatexja`, `graphicx`, `booktabs` など

---

## ファイル構成

```plaintext
LaTeXsample_for_Kyoto-u_civileng_mthesis/
├─ README.md                         // 本ファイル
├─ master_ja_sample.tex      // メインのLaTeXソース
├─ master_ja_sample.pdf      // 作成者の環境でコンパイルしたpdf
├─ img/
│   ├─ title/kyodai.png              // タイトルページ用ロゴの例
│   └─ chap2/computer_tokui_boy.png  // サンプル画像
└─ （必要に応じ .bib などを追加）
```

## 使いかた
ターミナルなどで
```bash
git clone https://github.com/ryota-saito-KyotoU/LaTeXsample_for_Kyoto-u_civileng_mthesis.git
```

または，「Code」→「Download ZIP」．

## ライセンス
このフォーマットは京大土木系のオフィシャルなものではありません．このフォーマットを用いて論文を作成し，如何なる
問題が発生したとしても，作成者は一切の責任を負いません．使用に際しては，必ず自身の指導教員や関係者と相談し，
適切なフォーマットであるかをご確認の上ご利用ください．

また，本フォーマットは自由に改変・再配布可能なMITライセンスですが，あくまで参考用テンプレートとしての提供です．
**正式な提出フォーマットとは異なる**可能性があります．各自，**専攻HPで提供されるガイドラインを必ず確認の上**，適宜修正してください．

## 作者・連絡先
- **作成者**：サイトウ リョウタ
- **現職**　：国立研究開発法人海上・港湾・航空技術研究所　港湾空港技術研究所　海洋利用研究領域　海洋利用研究グループ　研究官（2024年度 山上研修士修了）
- **Twitter**：@pokitamazaing

> **すいちゃんは～？今日もかわいい～！**
> Happy \LaTeX ing! 彗星のごとく仕上げちゃおう！

