コンパイルまでの流れ（例）

 端末で $emacs &

 M-RETもくしは画面最大化（この２つには違いがある。画面最大化）

 C-x 3 画面分割

 C-x o 画面移動

 M-x eshell emacs版コマンドプロンプト的な

 C-x o 画面移動

 C-x C-f ファイル作成

 プログラムを書く。時々保存しながら

 C-x o 画面移動

 シェルのところにいるはずなので、そこでコンパイル。

 C-x C-c emacs終了

これを覚えておけばどうにかなる。

その他キーバインド集

http://www.aise.ics.saitama-u.ac.jp/~gotoh/EmacsKeybind.html


よく使うemacsのコマンド M-x　コマンド名

 version :emacsのバージョンを調べる(コマンドプロンプトで$emacs -versionするのと同じ)

 eshell :emacs版コマンドプロンプト的な

 count-lines-regions :文字カウント

 set-alpha :エディタの透明度変更

 initchart-visualize-init-sequence :起動するまで時間の表を作成 保存場所を聞かれるので、~/initchart.svgとかで保存する


yatex（やてふ）

 .tex ファイルは自動でやてふモードになる

 C-c t j :platex　を実行

 C-c t d :platex と dvipdfmx を実行

 C-c t p :evince
 