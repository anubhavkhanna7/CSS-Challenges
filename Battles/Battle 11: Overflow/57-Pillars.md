# Battle #11 - Overflow

## #57 - Pillars

[Link to the problem](https://cssbattle.dev/play/57)

![result](../../Images/Battle%2011/57-Pillars.png)

```html
<div class='box'></div>
<div class='circle'>
  <div class='yellow'>
    <div class='blue'></div>
  </div>
</div>
<div class='circle right'>
  <div class='yellow'>
    <div class='blue'></div>
  </div>
</div>
<div class='circle right bottom'>
  <div class='yellow'>
    <div class='blue'></div>
  </div>
</div>
<div class='circle left-down'>
  <div class='yellow'>
    <div class='blue'></div>
  </div>
</div>
<style>
  body {background:#191919;margin: 95 145}
  div{background:#4F77FF}
  .box{height:110;width:110}
  .circle {
    width:60;
    height:60;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:75;
    left:125;
  }
  .yellow{
    width:45;
    height:45;
    background:#F9E492;
    border-radius:50%;
  }
  .blue{
    width:30;
    height:30;
    background:#4F77FF;
    border-radius:50%;
  }
  .right{
    margin-left:90;
    transform:rotate(90deg)
  }
  .bottom {
    margin-top: 90;
    transform:rotate(180deg)
  }
  .left-down {
    margin-top:90;
    transform:rotate(270deg)
  }
</style>
```