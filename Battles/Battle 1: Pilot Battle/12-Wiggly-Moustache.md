# Battle #1 - Pilot Battle

## #12 - Wiggly Moustache

[Link to the problem](https://cssbattle.dev/play/12)

![result](../../Images/Battle%201/12-Wiggly%20Moustache.png)

```html
<div class='left curve'></div>
<div class='mid'></div>
<div class='right curve'></div>
<div class='edge left-edge'></div>
<div class='edge right-edge'></div>
<style>
  body {
    background: #F5D6B4;
  }
  div {
    border: #D86F45 solid;
    height: 30px;
    position: absolute;
    width: 60px;
    top: 25;
  }
  .edge {
    width: 17px;
    height: 17px;
    background: #D86F45;
    border-radius: 50%;
    position: absolute;
    top: 140;
  }
  .left-edge {left: 70;}
  .right-edge {left: 310;}
  .mid {
    margin-top: 75px;
    border-radius: 175px 175px 0 0;
    border-width: 20px 20px 0 20px;
    left: 150;
  }
  .curve {
    margin-top: 125px;
    border-radius: 0 0 175px 175px;
    border-width: 0 20px 20px 20px;
  }
  .left {
    left: 70;
  }
  .right {
    left: 230;
  }
</style>
```