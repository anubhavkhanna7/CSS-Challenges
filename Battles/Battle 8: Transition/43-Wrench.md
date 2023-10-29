# Battle #8- Transition

## #43 - Wrench

[Link to the problem](https://cssbattle.dev/play/43)

![result](../../Images/Battle%208/43-Wrench.png)

```html
<div></div>
<div class='top-right'></div>
<div class='bottom-left'></div>
<div class='bottom-right'></div>
<style>
  body{background:#6592CF;}
  div {
    width: 180;
    height: 180;
    border: 30px solid #243D83;
    margin: 30 0 0 -33;
    border-top-right-radius: 70px;
    clip-path: inset(0 0 120px 170px);
  }
  .top-right {
    transform: rotateY(180deg);
    margin: -240 0 0 177;
  }
  .bottom-left {
    margin: -240 0 0 -28;
    transform: rotateX(180deg);
    border-top-right-radius: 72px;
    clip-path: inset(0 0 120px 165px);
    width: 175;
    height: 183;
  }
  .bottom-right {
    transform: rotateX(180deg) rotateY(180deg);
    margin: -240 0 0 177;
    width: 173;
    border-top-right-radius: 72px;
    clip-path: inset(0 0 120px 163px);
  }
  
</style>
```