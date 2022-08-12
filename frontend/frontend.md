# html,css,javascriptについての学習(emmet,Bootstrap,JQuery)
前提: [VSCode](https://code.visualstudio.com/Download)

## html
- Webページの構造を記述 
- htmlタグ内にhead+body
  - head(メタ属性,リンク,見た目を記述したスタイルシートの読み込みなどページをレンダー(ブラウザで読み込みをして表示)したときに見えない部分(インスペクタを使用すれば見える))
  - body(ヘッダー,フッター,中心となるメインコンテンツなどのリンクや画像を含む文章や構造,ページをレンダーしたときに見える部分)
- title,header,main,footerの中身を適当に入力する(hello webpage,header,main,footer)
- サイドバーの表示されている(されていない場合はcmd+b)htmlファイルをクリックしてcmd+alt+c
- 適当なブラウザー(chrome/safari/edge/firefox/brave/opera/tor...)のurlを入力できる場所にペースト,enter
- 雛形htmlが表示される
- emmetを使うとタグを効率的に記述できる
- [HTMLメモ](htmlMemo.md)

## css
- ページの見た目(フォント,文字サイズや文字色,背景色,ヘッダーフッターなど各要素の幅と高さやその大きさの割合など)を記述
- 変数も使える
- デバイスによって違う見た目を生成するようにレスポンシブに設定することもできる
- フレームワーク(Bootstrap)やLESS,SASS/SCSSなどのツールがたくさんある
- Bootstrapを使うとグリッドレイアウトや余白などの構成を効率的に記述できる
- ちょっとしたアニメーションも作れる
- html作成時にcmd+クリックして作ったファイルを編集。
- [CSSメモ](cssMemo.md)

## javascript
- ユーザのアクションに応じたページの動きをスクリプトで記述(インタラクティブなページを作成できる)
- ライブラリ,SDK,フレームワークやツールが超たくさんある(react,vue,node,hadlebars,jquery,underscore,backbone,angular,grunt,d3,express,phantom,selenium,...)
- バックエンドからフロントエンドまでの開発がすべて可能(node,react,vue,...)
- ライブラリを使用してサーバレス開発もできる(node.js)
- 2021年3月時点ではgithubのプロジェクト数が最も多いプログラミング言語
- JQueryを使うとjavascriptをよりシンプルに記述できる
- フルスタック(MERN, MEAN, MEVNなど)
- [GitHub上で一番人気のプログラミング言語](https://insights.dice.com/2020/12/03/10-most-popular-programming-languages-on-github/)
- [javascriptメモ](jsMemo.md)

## Bootstrap
- レスポンシブなサイトのデザインで頻繁に使われるコンポーネントを提供してくれるCSSとjavascriptのライブラリ
- html内のdivタグのclass属性としてmt-3 display-4 w-25などのように記述すると自動でスタイルを設定してくれる
- class="container"やbtn,navbar-togglerなどの値を指定するとボタンやハンバーガーメニューなどを自動で設定してくれる
- [Bootsrapメモ](bootsrapMemo.md)

## 静的サイトの公開とホスティング
- フロントエンドのコードだけでサイトの見た目は完成するので静的ウェブサイトとして世界に公開することが可能
- AWSやGCPなどのクラウドサービスや、github pagesにコードをアップロードして少しの設定をすると公開できる
- AWSを使用するときは料金システムについてしっかりと理解すること
- [ホスティングメモ](hosting.md)

## リンク
- http://www.w3schools.com/
- https://developer.mozilla.org/
- http://eloquentjavascript.net/
