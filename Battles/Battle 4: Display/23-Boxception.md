# Battle #4 - Display

## #23 - Boxception

[Link to the problem](https://cssbattle.dev/play/23)

![result](../../Images/Battle%204/23-Boxception.png)

```html
<div></div>
<div></div>
<div></div>
<style>
  body {background: #F3AC3C;}
  div:first-child {
    margin: 50 0 0 92;
    width: 200px;
    height: 200px;
    background: #1A4341;
  }
  div:nth-child(2) {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #998235;
    top: 150;
    left: 100;
  }
  div:nth-child(3) {
    position: absolute;
    width: 50px;
    height: 50px;
    background: #F3AC3C;
    top: 200;
    left: 150;
  }
</style>
```