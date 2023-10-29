# Battle #7- Backface

## #33 - Birdie

[Link to the problem](https://cssbattle.dev/play/32)

![result](../../Images/Battle%207/33-Birdie.png)

```html
<div></div>
<style>
  body {
    background: #1A4341;
    margin: 75 0 0 125;
  }
  div {
    width: 75px;
    height:150px;
    background: #998235;
    border-top-left-radius: 100px;
    border-bottom-left-radius: 100px;
  }
  div:before {
    content: '';
    height: 30;
    width: 30;
    background: #0B2429;
    position: absolute;
    border-radius: 50%;
    top: 105;
    left: 155;
  }
  div:after {
    content: '';
    height: 100;
    width: 100;
    background: #F3AC3C;
    border-top-right-radius: 100px;
    position: absolute;
    top: 50;
    left: 200;
  }
</style>
```