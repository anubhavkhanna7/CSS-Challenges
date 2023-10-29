# Battle #2 - Visibility

## #16 - Eye of the Tiger

[Link to the problem](https://cssbattle.dev/play/16)

![result](../../Images/Battle%202/16-Eye-Of-The-Tiger.png)

```html
<div class='left'></div>
<div class='center'></div>
<div class='right'></div>
<style>
  body {background: #0B2429;}
  div {
    position: absolute;
  }
  .left {
    margin: 72 0 0 122;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #0B2429;
    border: 45px solid #F3AC3C;
    z-index: 1;
  }
  .right {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    top: 60;
    left: 110;
    background: #0B2429;
    z-index: 0;
  }
  .center {
    width: 180px;
    height: 180px;
    transform: rotate(45deg);
    border-top-left-radius: 100px;
    border-bottom-right-radius: 100px;
    top: 50;
    left: 100;
    z-index: -1;
    background: #998235;
    border: 10px #998235 solid;
  }
</style>
```
