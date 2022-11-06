# TeX用レポートテンプレート

report_form.sty は，普段私が講義の提出レポートに使っているレポートテンプレートに関するスタイルファイルです．

A4サイズのレポート作成用に作ってあります．

（なお，当方 overleaf 環境下でしか使用確認ができておりません．あしからず．）

## 1. 使い方

texファイルへ読み込みは，プリアンブル中で`\usepackage{report_form}`を宣言すればOKです．


## 2. 各種設定

プリアンブル中に以下を入力してください．

- \author{} ..................... *氏名*
- \stunum{} .................. *学籍番号*
- \affiliation{} .............. *所属*
- \subject{} ................. *科目名*
- \submission{} ........ *提出レポート名*
- \BANGOU{} ........... *課題番号*
- \date{} .................... *日付*（`\today`を用いれば自動的に今日の日付が出力されます．）


## 3. 備考
- sectionについては四角囲み，subsectionについては( )囲みにしています( [\example\compile_example.pdf](https://github.com/Loschmidt-constant/TeX_report-template/tree/main/example/compile_example.pdf) 参照)．
- 定理環境については，theoremstyleをdefinitionに設定し，すべて日本語表示としてあります．（変更したい人は各自調整してください．）
- 私が良く使うマクロを入れたままにしております( [\report_form.sty](https://github.com/Loschmidt-constant/TeX_report-template/blob/main/report_form.sty) 内の"macro"の部分を参照)．適宜，追加・削除などを行ってください．

***
### 参考資料  
[1] 奥村晴彦, 黒木裕介 : [LATEX2ε美文書作成入門（改訂第8版）](https://amzn.to/3F1WpcB) , 技術評論社 (2020).

[2] TeXマクロメモ :  https://www.aise.ics.saitama-u.ac.jp/~gotoh/TexMacroMemo.html

[3] クラスファイルを作ろう(5) : http://abenori.blogspot.com/2019/12/latex-class-5.html
