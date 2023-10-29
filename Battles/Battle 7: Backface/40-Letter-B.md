# Battle #7- Backface

## #40 - Letter B

[Link to the problem](https://cssbattle.dev/play/40)

![result](../../Images/Battle%207/40-Letter-B.png)

```html
<div></div>
<style>
  body {
    background: #6592CF;
    margin: 50 0 0 100;
  }
  div {
    width: 100;
    height: 100;
    border: 50px solid #243D83;
    border-top-right-radius: 100px;
    border-bottom-right-radius: 100px;
    border-bottom-left-radius: 100px;
  }
  div:before{
    content: '';
    width: 50;
    height: 50;
    position: absolute;
    top: 50px;
    background: #6592CF;
  }
</style>
```