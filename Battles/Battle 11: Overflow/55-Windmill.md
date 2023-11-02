# Battle #11 - Overflow

## #55 - Windmill

[Link to the problem](https://cssbattle.dev/play/55)

![result](../../Images/Battle%2011/55-Windmill.png)

```html
<div class='semi top'></div>
<div class='semi right yellow'></div>
<div class='semi bottom'></div>
<div class='semi left yellow'></div>
<style>
  body {background:#191919;margin: 75 125}
  div{background:#4F77FF}
  .semi {
    width:100;
    height:50;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
  }
  .yellow{background:#F9E492}
  .top{transform:rotate(90deg);margin-left:50}
  .bottom{transform:rotate(270deg);margin-top:-25}
  .right{transform:rotate(180deg);margin:25 0 0 75}
  .left{margin:-125 0 0 -25}
</style>
```