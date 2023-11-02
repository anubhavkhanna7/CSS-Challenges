# Battle #11 - Overflow

## #58 - Rose

[Link to the problem](https://cssbattle.dev/play/58)

![result](../../Images/Battle%2011/58-Rose.png)

```html
<div class='stem yellow abs'>
  <div class='circle yellow round'></div>
</div>
<div class='rose round abs'></div>
<div class='petal abs'></div>
<div class='petal-background abs'></div>
<div class='petal-2 abs'></div>
<div class='base round abs'></div>
<style>
  body {background:#191919;margin: 95 145}
  div{background:#4F77FF}
  .abs{
    position:absolute;
  }
  .yellow{background:#F9E492;}
  .round{border-radius:50%}
  .circle{width:40;height:40;margin:-30 0 0 -10}
  .stem {
    width:20;
    height:80;
    background:#F9E492;
    border-radius:10px;
    top:175;
    left:190
  }
  .rose{
    width:100;
    height:100;
    top:65;
    left:150;
    clip-path:inset(60px 0 0 0)
  }
  .petal{
    width:140;
    height:30;
    border-top-left-radius:5px;
    border-bottom-left-radius:25px;
    border-top-right-radius:5px;
    border-bottom-right-radius:25px;
    top:85;
    left:130;
  }
  .petal-background {
    width:100;
    height:30;
    background:#191919;
    top:55;
    left:140;
    border: 10px solid #191919;
    border-bottom-left-radius:35px;
    border-bottom-right-radius:35px;
  }
  .petal-2{
    width:100;
    height:30;
    top:65;
    left:150;
    border-bottom-left-radius:35px;
    border-bottom-right-radius:35px;
    border-top-left-radius:7px;
    border-top-right-radius:7px;
  }
  .base{
    width:30;
    height:30;
    border:10px solid #191919;
    top:35;
    left:175;
  }
</style>
```