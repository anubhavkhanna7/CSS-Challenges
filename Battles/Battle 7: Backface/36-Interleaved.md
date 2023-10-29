# Battle #7- Backface

## #36 - Interleaved

[Link to the problem](https://cssbattle.dev/play/36)

![result](../../Images/Battle%207/36-Interleaved.png)

```html
<div></div>
<div></div>
<div></div>
<style>
  body {background: #1A4341; margin: 100 0 0 25;}
  div {
    display: inline-flex;
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
  }
  div:nth-child(2) {
    transform: translate(96px, 0);
  }
  div:nth-child(3) {
    transform: translate(192px, 0);
  }
  div:first-child:before{
    content: '';
    width: 50px;
    height: 200px;
    background: #998235;
    position: absolute;
    top: 0;
    left: 100;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 25px;
  }
  div:first-child:after{
    content: '';
    width: 50px;
    height: 200px;
    background: #998235;
    position: absolute;
    top: 0;
    left: 250;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 25px;
  }
</style>
```