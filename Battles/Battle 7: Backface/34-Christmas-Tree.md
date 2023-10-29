# Battle #7- Backface

## #34 - Christmas Tree

[Link to the problem](https://cssbattle.dev/play/34)

![result](../../Images/Battle%207/34-Christman-Tree.png)

```html
<div class='first'></div>
<div class='second'></div>
<div class='third'></div>
<style>
  body {background: #007065;}
  div {
    width: 0;
    border-right: 125px solid transparent;
    border-left: 125px solid transparent;
    border-bottom: 100px solid #FFEECF;
    position: relative;
    left: 67;
  }
  .first {
    top: 42;
    z-index: 1;
  }
  .second {
    border-bottom: 100px solid #F5C181;
    top: -8;
  }
  .third {
    border-bottom: 100px solid #00A79D;
    top: -58;
    z-index:-2;
  }
</style>
```