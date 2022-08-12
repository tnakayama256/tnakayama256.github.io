# CSSの学習メモ

## 概要
- Cascading Style Sheets(cascade(流れ落ちる)するスタイル(見た目)のシート(紙))
- Webページの見た目の記述, ちょっとしたアニメーション
- 指定がない場合はuser agentによってブラウザ指定のスタイルシートが適用される
- grid, flexbox, 
- 適用方法
  - head内のstyleタグに記述
  - head内のlinkタグでrel="stylesheet" href="style.css"として外部cssファイルを指定
  - bodyなどのhtmlタグのstyle属性として記述

## 文法
` セレクタ{属性:値} `

### htmlタグのstyle属性:
` <div style="background:skyblue;"> `

### セレクタ
- *: 全ての要素をセレクトする 

` * { box-sizing: border-box;} `

- nth-child(): n番目の要素をセレクトする

```
li:nth-child(n-3){}
li:nth-child(2){}
p:nth-child(2n){}
```

### 属性
- box-sizing: 値をborder-boxとするとpaddingとmarginをborderに合わせてくれる(初期値はcontent-box)


## flex
[サンプルコード](flexdemo.html)
