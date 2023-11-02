# Battle #11 - Overflow

## #60 - Evil Triangles

[Link to the problem](https://cssbattle.dev/play/60)

![result](../../Images/Battle%2011/60-Evil-Triangles.png)

```html
<div class='background-blue'></div>
<div class='container-w'>
  <div class='slant'></div>
  <div class='slant flip'></div>
  <div class='slant right'></div>
  <div class='slant flip right'></div>
</div>
<div class='container-w-down'>
  <div class='slant'></div>
  <div class='slant flip'></div>
  <div class='slant right'></div>
  <div class='slant flip right'></div>
</div>
<div class='cover'></div>
<div class='cover end'></div>
<style>
  body{background:#191919;margin:0}
  .cover{
  background:#191919;height:55;width:25;margin-left:75;position:absolute;
  }
  .end{left:225}
  .background-blue{
    width:200;
    height:50;
    background:#4F77FF;
    margin: 75 0 0 100;
  }
  .container-w-down {
    position:absolute;
    top:158;
    left:72;
  }
  .container-w-down div{
    background:#4F77FF;
    height:35;
  }
  .container-w{
    position:absolute;
    top:107;
    left:72;
  }
  .slant {
    display:inline-block;
    width: 106px;
    height: 36px;
    background: #191919;
    transform:rotate(45deg);
  }
  .flip{
    transform:rotate(315deg);
    margin: 0 0 0 -60;
  }
  .right{
    margin: -1 0 0 -60;
  }
</style>
```