# scss-template
SCSSの初期設定、function、mixinなどを定義した、最低限のSCSSフレームワークです。
SCSSのコンパイル環境があれば、style.scss(css)を読み込むことで使用できます。

## settings

`variables`
ブレークポイントや色の設定などを定義します。

`mixins` 
メディアクエリや絶対配置などよく使うスタイルのmixin集です。

`functions`
variablesで設定した値の取得などの関数などを定義しています。

## globals

`base`
ページ全体のフォントの設定、リンク設定など

`layout`
レイアウトに関するclassを定義

`reset`
リセットCSS

`typography`
テキストに関するclassを定義

`utils`
マージンやフォントサイズ調整用のユーティリティclassを定義
@forの数値を変えることで定義する幅を変更できます。