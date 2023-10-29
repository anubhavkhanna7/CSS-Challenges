# Battle #7- Backface

## #39 - Sunset

[Link to the problem](https://cssbattle.dev/play/39)

![result](../../Images/Battle%207/39-Sunset.png)

```html
<div class='green'></div>
<div class='green pos-abs flip'></div>
<div class='big pos-abs'></div>
<div class='big pos-abs flip'></div>
<div class='big pos-abs mid'></div>
<style>
  body {background: #1A4341;margin: 50 0 0 100;}
  .green {
    width: 200px;
    height: 200px;
    background: #998235;
    border-radius: 50%;
    clip-path: inset(0 0 170px 0);
  }
  .pos-abs {position: absolute;}
  .flip {
    transform: rotate(180deg);
    top: 50;
  }
  .big {
    width: 250px;
    height: 250px;
    background: #F3AC3C;
    border-radius: 50%;
    z-index: -1;
    top:25;
    left:75;
    clip-path: inset(75px 0 155px 0);
  }
  .mid {
    clip-path: inset(115px 0 115px 0);
  }
</style>
```