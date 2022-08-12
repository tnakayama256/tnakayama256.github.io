# Markdown 学習メモ

> We're living the future so
> the present is our past. 
> - Kanye West

```markdown
シンタックスハイライト付きのコードブロック

# 見出し1
## 見出し2
### 見出し3
...
###### 見出し6

- 点の
- リスト
  * 点の
  * リスト

1. 数字の
2. リスト

""ボールド""

_イタリック_ 

`コード` 

普通の文章

[リンク](アドレス)
![画像](アドレス)

引用:
> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

タスクリスト:
- [x] 完了済み
- [ ] 未完

テーブル:
見出し1 | 見出し2
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

ストライクスルー:
~クロスアウト~

絵文字:
:+1: , :sparkles: , :camel: , :tada: , :rocket: , :metal: , :octocat: , etc.
 
backslash エスケープ
\ followed by {\,`,*,_,{,},[,],(,),#,+,-,.,!}

```

### Syntax guide(basic):
- Headers:#
- Emphasis:*,_
- List:*,[0-9]
- Img:![name](path), Format: ![Alt Text](url)
- Link:http://url - automatic, [link name](url)
- Quotes:>
- Inline code:`code`

### GFM(GitHub Flavored Markdown)
- Syntax highlighting: ```
- Task Lists
- Tables
- SHA references
- Issue references within a repository
- @mentions
- Automatic linking(URL)
- Strikethrough:
- Emoji: :+1:


# 見出し1
## 見出し2
### 見出し3
...
###### 見出し6

- 点の
- リスト
  * 点\*の
  * リスト

1. 数字の
2. リスト

""ボールド""

_イタリック_ 

`Code` 

普通の文章

[リンク](https://mapotofu9.github.io/)
![画像](octocat(2).png)

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

タスクリスト:
- [x] 完了済み
- [ ] 未完


> I wonder why.  I wonder why.  
I wonder why I wonder.   
I wonder why I wonder why I wonder why I wonder! 

> \.\.\.\.\.\.\.\.\.\.\.\.\.\.\.

> Uh wugga wuh. Uh wugga wuh  
Uh wugga wugga wugga.  
I wugga wuh uh wugga wuh Uh wugga wugga wugga.  
"Aha!" I say. "That's my theme!"

>  "Surely You're Joking, Mr. Feynman!"

> When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!
> If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

テーブル:
見出し1 | 見出し2
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

Strikethrough:

~クロスアウト~

Emoji:
:+1: , :sparkles: , :camel: , :tada: , :rocket: , :metal: , :octocat: , etc.

- https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji

- https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

see [this cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) and [this](https://guides.github.com/features/mastering-markdown/) for reference.
