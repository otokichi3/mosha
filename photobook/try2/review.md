# 反省点
## ディレクトリ構成
- CSS をフォルダに入れていなかった
## HTML
### head
- description の meta がない
- shortcut icon がない
### body
#### header
- container をつけるのカンニングした
- .site-title を h2 にしてしまった。
- .site-title つけてない
- そもそも logo 使ってない
- svg が何か理解してない
- `<!-- ヘッダー -->` とかコメント入れてない
#### main
- alt に何を入れるべきか吟味してない
- .inner 使ったけどカンニングした
- .section-title 使ってない
- .index-list 使ってない（ol要素に直）
- .content 使ってない
- 要素ごとにちゃんと改行してない（見にくい）
- h3 と p の使い所理解してない
- .text クラス使ってない
- なんか dl に id 使っちゃってる
- パラグラフに p じゃなくて div 使っちゃってる（使い分けろよ）
- noopener noreferrer is 何
### footer
- p に id 使ってない

## CSS
- charset 書いてない
- html 全体に何もしてない
- 作った後の推敲が圧倒的に足りない（もっと自力で頑張れ）