# Battle #9 - Margin

## #46 - Mountains

[Link to the problem](https://cssbattle.dev/play/46)

![result](../../Images/Battle%209/46-Mountains.png)

```html
<div class='circle'>
  <div class='mountain'></div>
  <div class='mountain left'></div>
</div>
<style>
  body{background:#293462;margin: 50 0 0 100}
  .circle {
    width: 200px;
    height: 200px;
    background: #FFF1C1;
    border-radius:50%;
    overflow: hidden;
  }
  .mountain {
    width: 200;
    height:150;
    background:#FE5F55;
    transform: rotate(315deg);
    margin: 108 0 0 24;
  }
  .left {
    margin: -80 0 0 -88;
  }
</style>
```