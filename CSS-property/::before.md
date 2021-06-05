`::before`と`::after`を擬似要素と呼ぶ。
これらを使うことで適当なクラスをつけなくてもcssを書くことができる。
基本的には空のspanがあると思っておけばいい。
```
.btn{
  &.slide-bg{
      &::before {
        content: "";
        display: inline-block;
        width: 100%;
        height: 100%;
        background-color: $cBlack;
        position: absolute;
        top: 0;
        left: 0;
        transform: translateX(-100%);
        transition: transform 0.3s;
        z-index: -1;
      }
    }
  }
```
**contentの中身を必ず設定すること。**　　
**contentの中には文字列も可。**　　
**同じHTMLに設定できる`before``after`はそれぞれ1つずつのみ。**　　
**2つ以上ある場合は詳細度の高い方が優先される。**
**`img`では`before`などの擬似要素は使用できない。**　　

