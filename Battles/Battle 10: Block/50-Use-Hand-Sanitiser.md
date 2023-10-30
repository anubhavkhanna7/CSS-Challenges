# Battle #10 - Block

## #50 - Use Hand Sanitiser

[Link to the problem](https://cssbattle.dev/play/50)

![result](../../Images/Battle%2010/50-Use-Hand-Sanitiser.png)

```html
<div class='tap'></div>
<div class='pipe'></div>
<div class='cap'></div>
<div class='bottle'></div>
<div class='bottle green'></div>
<div class='dropper abs'></div>
<div class='drop abs'></div>
<div class='drop abs second-drop'></div>
<div class='circle'></div>
<div class='circle yellow'></div>
<style>
  body{background:#1A4341;margin:50 150}
  .a{position:absolute}
  div{background: #F3AC3C}
  .tap {
    height:20;
    width:150;
    border-radius:20px;
  }
  .pipe{
    height:20;
    width:20;
    margin-left:40
  }
  .cap{
    width:50;
    height:20;
    border-top-left-radius:10px;
    border-top-right-radius:10px;
    margin-left: 25;
  }
  .bottle {
    height: 140;
    width: 100;
    border-radius: 20px;
    clip-path: inset(0 0 80px 0);
  }
  .green {
    margin: -140 0 0 0;
    clip-path: inset(0 0 60px 0);
    transform:rotateX(180deg);
    background: #998235;
  }
  .dropper {
    width: 20;
    height: 30;
    top:60;
    left: 280;
    border-bottom-right-radius:10px;
    border-bottom-left-radius:10px;
  }
  .drop {
    width: 20;
    height: 20;
    border-radius: 50%;
    background:#998235;
    top:100;
    left:280;
  }
  .second-drop {top:130}
  .circle {
    height:70;
    width:50;
    background:#998235;
    border-top-left-radius:30px;
    border-top-right-radius:30px;
    position:absolute;
    z-index:2;
    top:140
  }
  .yellow {
    background:#F3AC3C;
    height:50;
    left:200;
    top:140;
    transform:rotateX(180deg);
  }
</style>
```