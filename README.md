# TeX用レポートテンプレート

report_form.sty は，普段私が講義の提出レポートに使っているレポートテンプレートに関するスタイルファイルです．A4サイズのレポート作成用に作ってあります．

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
- sectionについては四角囲み，subsectionについては()囲みにしてある([\example\compile_example.pdf](https://github.com/Loschmidt-constant/TeX_report-template/tree/main/example)参照)


