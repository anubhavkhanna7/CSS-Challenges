# Battle #4 - Display

## #27 - Lock Up

[Link to the problem](https://cssbattle.dev/play/27)

![result](../../Images/Battle%204/27-Lock-Up.png)

```html
<div></div>
<div></div>
<style>
  body {background: #E38F66;}
  body:before {
    content: '';
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: #AA445F;
    position: absolute;
    top: 50;
    left: 100;
  }
  div {
    width: 40px;
    height: 40px;
    position: absolute;
  }
  div:first-child {
    border-top-right-radius: 100px;
    border-top: 30px solid #F7EC7D;
    border-right: 30px solid #F7EC7D;
    top: 80;
    left: 200;
  }
  div:last-of-type {
    border-bottom-left-radius: 100px;
    border-bottom: 30px solid #F7EC7D;
    border-left: 30px solid #F7EC7D;
    top: 150;
    left: 130;
  }
</style>
```