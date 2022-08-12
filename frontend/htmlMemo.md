# htmlについて

[ブラウザ間の互換性に注意](http://caniuse.com)

### 文法
基本的にタグを使用してページの要素を記述していく

` <タグ 属性='値'>表示される要素</タグ> `

` <!-- コメント --> `

### タグ
- カテゴリー（どの分類か）
- コンテンツモデル（どのカテゴリのタグを入れられるか）
が定義されている[W3仕様書](https://www.w3schools.com/tags/default.asp)

### 要素
- ブロックレベル要素(h1-6,p,div,section,...)
- インライン要素(span, img, a,...)

### 文書タイプ宣言
` <!DOCTYPE html> <!-- html5 --> `

### ハイパーリンク
` <a href="" target="_blank">新しいタブで開く</a> `

### 文字のフォーマット用のタグ
```
<!-- b ~= strong--> 
<!-- i ~= em --> 
<!-- u ~= ins -->
<!-- 
 br => line break(改行)
 hr => 1px-thick horizontal black line across its container(横線)
 small => 文字が小さくなる
 sub => サブスクリプト(数列の要素をAiみたいな表しかたをするときのiの部分)
 sup => スーパースクリプト(e^xの指数の部分(x))
 del => mdだと~ ~(打ち消し線)
-->
``` 

### self-closingタグ
閉じタグが不要
```
<img /> 
<link />
```


### テーブル
例:3*3
` table>thead>tr>th{tableHead}*3^^tbody>(tr>td{data}*3)*3 `.. emmet
` <td colspan=“2”> somedata with colspan 2 </td> `

### preタグ
```
<pre>
改行と
 空白を
  表示できる
</pre>

```

### 引用のためのタグ
` <blockquote cite="https://www.goodreads.com/quotes/749769-done-is-better-than-perfect">done is better than perfect</blockquote> `

### ユーザ入力
### チェックボックス,ラジオボタン,メールアドレス,URL,電話番号
labelでインプットを囲むことでクリックされた時に入力にフォーカスできる
```
	<label>
	<input type="checkbox" name="color" value="black">black
	</label> 
	<input type="checkbox" name="color" value="blue" id="blue" checked>
	<label for="red"> red</label>
	<input type="radio" name="color" value="red" checked> red
	<input type="radio" name="color" value="blue"> blue
	<input id="email" type="email" name="email" placeholder="example@example.com" />
	<input id="url" type="url" name="url" placeholder="example.com" />
	<input id="tel" type="tel" name="tel" placeholder="000.168.255" />
```

### 複数選択
```
	<select name="color" multiple size="3">
	<option value="red">red</option>
	<option value="green" selected>green</option>
	<option value="blue">blue</option>
```

### フォーム
入力をenterするとactionが実行される
``` 
<form action="#" method="GET">
	<input id="url" type="url" name="url" placeholder="example.com">
	<input type="submit" name="submit">
</form>
<!-- action==phpファイルなどデータの送信先,  method=post/getなど(HTTPメソッド) -->
<form action= "process.php" method=“post”>
	<p> Email: <input type=“text” name=“email” value="huh"></p>
</form>
```
### datalist:
```
<input type="text" id="color" list="colors"/>
<datalist id="colors">
	<option value="red"></option>
	<option value="green"></option>
	<option value="blue"></option>
</datalist>
```



### 特殊記号
- 数字文字参照 == e.g.) < is &#60;
- 文字実体参照 == e.g.) < is &lt;
```
	<p> == &lt;p&gt;
	&quot; == "
	&amp; == &
	&copy; == 著作権のマーク
```

### 音声と映像

#### 音声:
```
	<p><audio src="audio.mp3" controls>Audio element not supported by your browser</audio><br>
	<audio controls autoplay loop>
		<source src="audio.mp3" type="audio/mpeg">
		<source src="audio.ogg" type="audio/ogg">
		<source src="audio.wav" type="audio/wav"><!-- browser will use the first recognized format -->
	</audio>
```
### 映像:
```
	<p><video src="video.mp4" controls>Video element not supported by your browser</audio><br>
	<video controls autoplay loop>
		<source src="video.mp4" type="video/mpeg">
		<source src="video.ogg" type="video/ogg">
		<source src="audio.wav" type="/wav"><!-- browser will use the first recognized format -->
	</audio></p>
```

### head内の要素
- title
  - ページのタブあたりに表示されるページのタイトル
- link: 
  - 文書と関係のある外部ファイル(stylesheet, script, favicon, RSS, PDF,..)との接続(ハイパーリンクではない). 


htmlタグは基本的には装飾に使わない(div&span w/ id or class)
```
<code> ... monospace
href="#" == href="#top"
<time>2021-3-24</time>
``` 

説明リスト(list, term, detail)
```
dl>(dt+dd)*6
```
- header .. 導入
- nav ..ナビゲーション
- aside .. 広告などページ内容と直接的な関係のないもの
- main>article .. 独立したコンテンツ
- section .. 汎用
- footer .. コンクルージョン



[フロントエンドの学習メモ](frontendMemo.md)
