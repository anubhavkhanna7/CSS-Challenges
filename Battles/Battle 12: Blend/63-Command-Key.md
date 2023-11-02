# Battle #12 - Blend

## #63 - Command Key

[Link to the problem](https://cssbattle.dev/play/63)

![result](../../Images/Battle%2012/63-Command-Key.png)

```html
<div class='corner'></div>
<div class='corner flip'></div>
<div class='corner down'></div>
<div class='corner right'></div>
<div class='square'></div>
<style>
  body{background:#191919;margin:54 0 0 106}
  div {display:inline-block;border: 10px solid #5DBCF9}
  .corner {
    width:50;
    height:50;
    border-top-left-radius:35px;
    border-bottom-left-radius:35px;
    border-top-right-radius:35px;
  }
  .flip {
    transform:rotateY(180deg);
    margin:0 40 0 46;
  }
  .down {
    margin-top:46;
    transform:rotateX(180deg)
  }
  .right {
    margin-left:46;
    transform:rotate(180deg)
  }
  .square{
    width:50;
    height:50;
    position:absolute;
    top:114;
    left:166
  }
</style>
```