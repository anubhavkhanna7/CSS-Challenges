# Battle #1 - Pilot Battle

## #11 - Eye of Sauron

[Link to the problem](https://cssbattle.dev/play/11)

![result](../../Images/Battle%201/11-Eye%20of%20Sauron.png)

```html
<div class='left side'></div>
<div class='right side'></div>
<div class='circle'></div>
<style>
  body {
    background: #191210; 
  }
  .side {
    margin-top: 125px;
    width: 60px;
    height: 30px;
    position: absolute;
    border: #ECA03D solid;
  }
  .left {
    border-radius: 0px 0px 175px 175px;
    border-width: 0 20px 20px 20px;
    top: 25;
    left: 50;
  }
  .right {
    border-radius: 175px 175px 0 0;
    border-width: 20px 20px 0 20px;
    top: -25;
    left: 250;
  }
  .circle {
    margin: 100px 0 0 142px;
    width: 50px;
    height: 50px;
    background: #84271C;
    border-radius: 50%;
    border: 25px #191210 solid;
  }
  .circle:before {
    content: ' ';
    border-radius: 50%;
    position: absolute;
    border: 20px solid #ECA03D;
    width: 100px;
    height: 100px;
    top: 80;
    left: 130;
  }
</style>
```