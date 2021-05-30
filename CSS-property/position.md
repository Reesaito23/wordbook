- ```position: static;```
  これがpositionの既存のproperty
- ```position: relative;```=親要素
- ```position: absplute;```=重ねたい子要素
- ```z-index: 00;```=重ね順を変えたい時に設定する、大きい方が全面
  （※positionのpropertyにstatic以外の何かが設定されている時のみ有効）
  
- ```
  <div-1></div-1>
  <div-2></div-2>
  <div-3>
    <div-4></div-4>
  </div-3>

  ```
  z-indexは同じ段階のみで効くけど、この場合、div-3のz-indexがautoの場合、div-1,2,4重なり順を調節できる。
  
- ```position: fixed;``` = ウィンドウの範囲で特定の場所に固定
- ```position: sticky;``` = 上の段階で、div-4にこのpropertyをつけ、```top: 30px;```(div-3に```height: 1000px;```とかの高さを設定する)とかってつけると、div-３の範囲以内で、スクロールして、div-4がtopの30pxに到達した段階から、その場でfixedと同じように固定される。
  （div-3のheightno1000pxまでで終わる。）
  （fixed = 親関係ない。　sticky = 親の中でのみ）
  （親要素に```overflow: hidden;```がある場合は使えなくなる。）
