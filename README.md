# Markdown
Markdownについての技法の自分用のメモ

-  見出し

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

- 文字のスタイル

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

- 引用テキスト

    引用テキストは **>** でする
    ```
    >  （例）引用テキストです。
    >> 二重引用テキスト
    ```
    >  （例）引用テキストです。
    >> 二重引用テキスト

- 引用符

    ```
    `(バックククォート)` で記述
    ```
    `(バックククォート)` で記述

    ```
    コードとかテキストの独自ブロックは、```トリプルバッククォートで記載する
    ```

- リンク集

    ```
        このリンク先は[Google](https://www.google.com/)
    ```
    このリンク先は[Google](https://www.google.com/)

- セクションリンク

    ```
    [セクションリンク](#section1)
    # section1
    ```
    [セクションリンク](#section1)
    # section1

- 相対リンク

    絶対パスで書くと後々面倒なのはお約束（全部書き直さないといけなくなるのでそういう手間をなくす）

    ```
    [相対リンク](/README.md)
    ```
    [相対リンク](/README.md)

- リスト

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
    
- タスクリスト

    ```
    - [x] First Task
    - [ ] Second Task
    - [ ] Thaad Task
    ```
    - [x] First Task
    - [ ] Second Task
    - [ ] Thaad Task

- エスケープ

    エスケープが必要なときは ` \(バックスラッシュ)` でエスケープ！

- 個人もしくはチームにメンション

    ```
    @hoge_user              : ユーザーにメンション
    @organization/team-name : チームメンバー全員にメンション
    ```

- 絵文字

    `:emojicode:` を追記したら絵文字が入る
    
    使える絵文字の一覧はこのリンクから→[https://www.webfx.com/tools/emoji-cheat-sheet/](https://www.webfx.com/tools/emoji-cheat-sheet/)

    （例）:+1: OK！ octocat！ :octocat:
