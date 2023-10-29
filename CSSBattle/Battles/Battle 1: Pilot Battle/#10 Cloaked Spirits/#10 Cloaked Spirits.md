# Battle #1 - Pilot Battle

## #10 - Cloaked Spirits

[Link to the problem](https://cssbattle.dev/play/10)

![result](../../../Images/Battle%201/10-Cloaked%20Spirit.png)

```html
<div class='container'>
  <div class='left yellow'><div class='circle-radius orange circle'></div></div>
  <div class='mid yellow'><div class='circle-radius red circle'></div></div>
  <div class='right yyellow'><div class='circle-radius orange circle'></div>
  </div>
</div>
<style>
  body {background: #62306D;margin: 0;position: relative;}
  .container {display: flex;flex-direction: row;}
  .container > div {width: 100px;position: fixed;bottom: 0;}
  .left {height: 100;left: 50px;}
  .right {height: 100;left: 250px;}
  .mid {height: 200;left: 150px;}
  .circle-radius {border-radius: 50%;}
  .circle {height: 60px;width: 60px;margin-top: -50;}
  .left .circle {top: 150;}
  .right .circle {top: 150;}
  .mid .circle {top: 50;}
  .orange {background: #E38F66;border: 20px solid #AA445F;}
  .red {background: #AA445F;border: 20px solid #E38F66;}
  .yellow {background: #F7EC7D;}
</style>
```