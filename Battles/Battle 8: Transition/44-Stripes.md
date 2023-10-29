# Battle #8- Transition

## #44 - Stripes

[Link to the problem](https://cssbattle.dev/play/44)

![result](../../Images/Battle%208/44-Stripes.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div class='c'></div>
<div class='c f'></div>
<style>
  body{background:#1A4341;margin:60 0 0 100}
  div:not(.c) {
    width: 200px;
    height: 20;
    background: #F3AC3C;
    margin: 0 0 20 0;
  }
  .c {
    width: 300;
    height: 300;
    border-radius: 50%;
    background: #1A4341;
    position: absolute;
    top: 0;
    left: -150.2;
  }
  .f {
    transform: rotateY(180deg);
    left: 250.2;
  }
</style>
```