# 概要
学位申請用論文のテンプレートです。
基本的には`bxjsbook`クラスをそのまま使ってあります。
`Thesis.sty`は主にパッケージの読み込みやマクロの定義などに使っています。
参考文献のフォーマットは`jecon.bst`を使って航空宇宙系のものに合わせてあります。

# 使い方
`_root.tex`をコンパイルしてください。

- 同ファイル中の`\usepackage[]{Thesis}`は、`\usepackage[draft]{Thesis}`のように`draft`オプションをつけると画像が非表示になるので文章だけ確認したいときに便利です。
- 博士論文はネットで公開するため学籍番号を非表示にする必要があり、`phd`オプションで実現できます。
- `print`オプションをつけると、のりしろを考慮した余白になります

## Thesis.sty
Texstudio使用者は`Thesis.cwl`を`%APPDATA%\texstudio\completion\user`に入れるとエディタで補完が効くようになります。
