# Battle #4 - Display

## #24 - Switches

[Link to the problem](https://cssbattle.dev/play/24)

![result](../../Images/Battle%204/24-Switches.png)

```html
<div></div>
<div class='right'></div>
<div class='off'></div>
<div class='off flip'></div>
<style>
  body {background:#62306D;margin: 100 0 0 80; display: inline-flex;}
  div {position:absolute;width:100px;height:100px;border-radius:50%;background: #F7EC7D}
  .off {
    position: absolute;
    top: 50;
    left: 80;
    border-radius: 0;
    border-top-right-radius: 50px;
    border-top-left-radius: 50px;
    height: 100px;
    background: #AA445F;
    width: 100px;
    z-index: -1;
  }
  .right {
    left: 220;
  }
  .flip {
    transform: rotate(180deg);
    top: 150;
    left: 220;
    background: #E38F66;
  }
</style>
```