# 概要
学位申請用論文のテンプレートです。
基本的には`bxjsbook`クラスをそのまま使ってあります。
`Thesis.sty`は主にパッケージの読み込みやマクロの定義などに使っています。
参考文献のフォーマットは`jecon.bst`を使って航空宇宙系のものに合わせてあります。

# 使い方
`_root.tex`をコンパイルしてください。

- 同ファイル中の`bxjsarticle`の読み込み時に`draft`オプションをつけると画像が非表示になるので、文章だけ確認したいときに便利です。
- 博士論文はネットで公開されるため、学籍番号を非表示にする必要があります。そのためのThesisクラスへのオプションが`phd`です。
- Thesis読み込み時に`print`オプションをつけると、のりしろを考慮した余白になります

## Thesis.cwl
Texstudio使用者は`Thesis.cwl`を`%APPDATA%\texstudio\completion\user`に入れると、エディタで補完が効くようになります。
