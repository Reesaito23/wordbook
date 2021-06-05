# Markdownの基礎
  このページは:point_down:のまとめです。  
  [Github docs](https://docs.github.com/ja/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
<!-- START doctoc -->
### もくじ  
1. [Heading](#heading)
2. [Decorating_Text](#decorating_text)
3. [Quotation_text](#quotation_text)
4. [Quotation_code](#quotation_code)
5. [Quotation_Block](#quotation_block)
6. [Link_out](#link_out)
7. [Link_in](#link_in)
8. [List](#list)
9. [Check-box](#check-box)
10. [Mention](#mention)
11. [EMOJI](#emoji)
<!-- END doctoc -->


- ## Heading  
  タイトルを書きたいときはそれのなめに`#`を入れる。  
  レベルは１〜６まである。　　
  ```
  # Title  
  ## Title  
  ### Title  
  #### Title  
  ##### Title  
  ###### Title  
  ```
  # Title
  ## Title
  ### Title
  #### Title
  ##### Title
  ###### Title  
  [もくじに戻る](#もくじ)
  
- ## Decorating_Text  
  テキストに装飾をしたいときの書き方:point_down:
  ```
  **Bold letter** (command + b)
  _Italic letter_ (command + i)
  ~~Strike-out line~~
  **Bold and _important(italic)_ letters**
  ***Bold and Italic letters***
  ```
  **Bold letter**  
  _Italic letter_  
  ~~Strike-out line~~  
  **Bold and _important(italic)_ letters**  
  ***Bold and Italic letters***  
  [もくじに戻る](#もくじ)
  
- ## Quotation_text  
  引用文の前には`>`を記入する。
  ```
  This is a quotation from text books.
  > Apple is red color.  
  ```
  This is a quotation from text books.
  > Apple is red color.  
  
  [もくじに戻る](#もくじ)
  
- ## Quotation_code  
  `　バッククォート（｀）　`で挟んだ中の部分だけがcode形式になる。
  ```
  Apple have `two` colors.
  ```
  Apple have `two` colors.  
  [もくじに戻る](#もくじ)
  
- ## Quotation_Block  
  `｀｀｀`で挟むことで挟まれた中のBlock部分はBlockごとcode形式になる
  ```
      Apple and Orange is my friends name.
      ```
      git status
      git add
      git commit
      ```
  ```
  Apple and Orange is my friends name.
  ```
  Apple is my close friend.
  Orange is not my close friend.
  ```
  
  [もくじに戻る](#もくじ)
  
- ## Link_out  
  リンクもとのサイトを`[]`で囲み、`()`のなかにリンクのURLを書く。(command + k)
  ```
  [GitHub Pages](https://github.com/Rieru-Saito-poo/til/edit/main/2021-06/0604.md)
  [gougle](https://docs.github.com/ja/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
  ```
  [GitHub Pages](https://github.com/Rieru-Saito-poo/til/edit/main/2021-06/0604.md)  
  
  [gougle](https://docs.github.com/ja/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)　　
  
  [もくじに戻る](#もくじ)
  
- ## Link_in　　
  同じページの中での移動→セクション間での移動
  ```
  [表示したい名前](#タイトル名(＊小文字開始))
  ```
  [表示したい名前](#タイトル名)  
  ##### タイトル名  
  [もくじに戻る](#もくじ)
  
- ## List  
  行の前に`-`か`*`お書くことで順序が関係なしのリストが作られる。
  ```
  - one
  - two
  - three
  ```
  - one
  - two
  - three
  
  番号を書くことで順序が決まる。　　
  ```
  1. one
  2. two
  3. three
  ```
  1. one
  2. two
  3. three
  
  段落を下げることで入れ子のリストになる。　　
  ```
  1. one
     1. one-one
     2. one-two
  2. two
  3. three
    
  - one
    - one-one
    - one-two
  - two
  - three
  ```
  1. one
     1. one-one
     2. one-two
  2. two
  3. three
    
  - one
    - one-one
    - one-two
  - two
  - three  
  
  [もくじに戻る](#もくじ)
  
- ## Check-box
  check-boxを書くには`[ ]`を書くと空白のチェックボックスになり、中に`x`を書くことでcheck入りのボックスになる。
  ```
  - [x] apple
  - [ ] orange
  - [ ] green
  ```
  - [x] apple
  - [ ] orange
  - [ ] green
  
  もし内容の先頭が`（）`の場合は`()`の前に`\`を書かなければならない。
  ```
  - [x] \(sister's)apple
  - [ ] (brother's)apple
  ```
  - [x] \(sister's)apple
  - [ ] (brother's)apple  
  
  [もくじに戻る](#もくじ)
  
- ## Mention
  `@`の後にuser_nameを書くことでメンションができる。　　
  後ろをteam-nameにするとチーム内の全ての人に通知がいく。
  ```
  @Rieru-Saito-poo
  @team-name
  ```
  @Rieru-Saito-poo  
  @team-name  
  [もくじに戻る](#もくじ)
  
- ## EMOJI  
  `:EMOJICODE:`を入力して、書き込みに絵文字を追加できます。
  詳しくは[Emoji_cheetsheet](docs/MarkDown_cheetsheet)を参照
  ```
  :+1:today's dinner so good.
  ```
  :+1:today's dinner so good.  
  [もくじに戻る](#もくじ)
  
  
