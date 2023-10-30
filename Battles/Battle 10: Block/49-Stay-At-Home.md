# Battle #10 - Block

## #49 - Stay At Home

[Link to the problem](https://cssbattle.dev/play/49)

![result](../../Images/Battle%2010/49-Stay-At-Home.png)

```html
<div class='roof'></div>
<div class='house'>
  <div class='light'></div>
  <div class='door'></div>
</div>
<style>
  body{background:#6592CF;margin:125 125}
  .roof {
    width:0;
    border-bottom: 100px solid #243D83;
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
    position: absolute;
    top: 50;
    left: 100;
    z-index: -1;
  }
  .house {
    background: #243D83;
    height: 105;
    width: 125;
    border-radius: 10px;
    padding: 20 0 0 25;
  }
  .light {
    background: #EEB850;
    width: 100px;
    height: 10px;
    border-radius: 20px;
  } 
  .door {
    background: #EEB850;
    width: 50;
    height: 50;
    margin: 45 0 0 25;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
  }
</style>