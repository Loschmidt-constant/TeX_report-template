# TeX用レポートテンプレート

report_form.sty は，普段私が講義の提出レポートに使っているレポートテンプレートに関するスタイルファイルです．

A4サイズのレポート作成用に作ってあります．

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
- 私が良く使うマクロを入れたままにしております( [\report_form.sty](https://github.com/Loschmidt-constant/TeX_report-template/blob/main/report_form.sty) 内の"macro"の部分を参照)．適宜，追加・削除などを行ってください．

## 4.参考文献




