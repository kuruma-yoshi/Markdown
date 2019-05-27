# Markdown

Markdownについての技法の自分用のメモ

参考ページ：https://help.github.com/en/categories/writing-on-github

## メニュー
- [見出し](#見出し)
- [文字のスタイル](#文字のスタイル)
- [引用テキスト](#引用テキスト)
- [引用符](#引用符)
- [リンク集](#リンク集)
- [セクションリンク](#セクションリンク)
- [相対リンク](#相対リンク)
- [リスト](#リスト)
- [タスクリスト](#タスクリスト)
- [エスケープ](#エスケープ)
- [個人もしくはチームにメンション](#個人もしくはチームにメンション)
- [絵文字](#絵文字)
- [段落と改行](#段落と改行)
- [テーブル](#テーブル)

## 見出し

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
# h1
## h2
### h3
#### h4
##### h5
###### h6

## 文字のスタイル

```
**太字**
__太字__
```
**太字** 

```
*イタリック体*
_イタリック体_
```
*イタリック体*

```
~~取り消し線~~
```
~~取り消し線~~ 

```
**太字と _斜体_ (より重要)**
```
**太字と _斜体_ (より重要)**

## 引用テキスト

引用テキストは **>** でする
```
>  （例）引用テキストです。
>> 二重引用テキスト
```
>  （例）引用テキストです。
>> 二重引用テキスト

## 引用符

```
`(バックククォート)` で記述
```
`(バックククォート)` で記述

```
コードとかテキストの独自ブロックは、```トリプルバッククォートで記載する
```

## リンク集

```
    このリンク先は[Google](https://www.google.com/)
```
このリンク先は[Google](https://www.google.com/)

## セクションリンク

```
[セクションリンク](#section1)
# section1
```
[セクションリンク](#section1)
# section1

## 相対リンク

絶対パスで書くと後々面倒なのはお約束（全部書き直さないといけなくなるのでそういう手間をなくす）

```
[相対リンク](/README.md)
```
[相対リンク](/README.md)

## リスト

```
順不同リスト
- 1
- 2
- 3

もしくは

* 1
* 2
* 3
```
- 1
- 2
- 3

```
番号付リスト
1. First
2. Second
3. Thaad
```
1. First
2. Second
3. Thaad

```
ネストリスト
1. First
    - Second
        - Thaad 
```
1. First
    - Second
        - Thaad
    
## タスクリスト

```
- [x] First Task
- [ ] Second Task
- [ ] Thaad Task
```
- [x] First Task
- [ ] Second Task
- [ ] Thaad Task

## エスケープ

エスケープが必要なときは ` \(バックスラッシュ)` でエスケープ！

Markdownの技法も無視出来るみたい

（例）\*Markdown\* フォーマット無視出来てる
 
## 個人もしくはチームにメンション

```
@hoge_user              : ユーザーにメンション
@organization/team-name : チームメンバー全員にメンション
```

## 絵文字

`:emojicode:` を追記したら絵文字が入る
使える絵文字の一覧はこのリンクから→[https://www.webfx.com/tools/emoji-cheat-sheet/](https://www.webfx.com/tools/emoji-cheat-sheet/)

（例）:+1: OK！ octocat！ :octocat:

## 段落と改行

行間の間に空白行を入れると新しい段落にできるよ

## テーブル

`|(パイプ)` をテーブル内に入れるときはエスケープすれば入れれる。

```
シンプルなテーブル
| First Header | Second Header | : ヘッダー行
| --- | --- |                    : セルの設定
| Content Call | Content Call |  : データ行
| Content Call | Content Call |  : データ行
```
| First Header | Second Header |
| --- | --- |
| Content Call | Content Call |
| Content Call | Content Call |

```
コンテンツのフォーマットは変更出来る
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
```
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

```
文字の左・中央・右に揃えることが出来る
| Left-aligned | Center-aligned | Right-aligned |
| :--- | :---: | ---: |
| git status | git status | git status |
| git diff | git diff | git diff |
```
| Left-aligned | Center-aligned | Right-aligned |
| :-- | :--: | --: |
| git status | git status | git status |
| git diff | git diff | git diff |

