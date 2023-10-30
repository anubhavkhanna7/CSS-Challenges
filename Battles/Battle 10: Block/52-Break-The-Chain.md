# Battle #10 - Block

## #52 - Break The Chain

[Link to the problem](https://cssbattle.dev/play/52)

![result](../../Images/Battle%2010/52-Break-The-Chain.png)

```html
<div class='pin'><p></p></div>
<div class='pin'><p></p></div>
<div class='pin'><p></p></div>
<div class='pin'><p></p></div>
<div class='pin'><p></p></div>
<div class='pin'><p></p></div>
<div class='pin'><p></p></div>
<div class='circle'></div>
<div class='circle big'></div>
<div class='circle right'></div>
<style>
  body {background:#6592CF;margin:140 0;}
  .pin:first-of-type {
    margin-left: 45px;
  }
  .pin:nth-of-type(4) {
    margin-left:30
  }
  .pin {
    width: 10;
    height: 50;
    background: #243D83;
    border-top-left-radius:5px;
    border-top-right-radius:5px;
    display: inline-block;
    margin: 0 31 0 0;
    
  }
  .pin p {
    width: 20;
    height: 20;
    background: #243D83;
    border-radius: 50%;
    margin: -10 0 0 -5;
  }
  .circle {
    background: #EEB850;
    width:40;
    height:40;
    border-radius:50%;
    position:absolute;
    top: 120;
    left:30;
    z-index:-1;
  }
  .big {
    width:60;
    height:60;
    top: 100;
    left:65;
  }
  .right {
    left: 120
  }
</style>
```