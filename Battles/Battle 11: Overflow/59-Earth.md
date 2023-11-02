# Battle #11 - Overflow

## #59 - Earth

[Link to the problem](https://cssbattle.dev/play/59)

![result](../../Images/Battle%2011/59-Earth.png)

```html
<div class='circle'>
</div>
<div class='divider'></div>
<div class='divider horizontal'></div>
<div class='divider horizontal'></div>
<div class='divider vertical'></div>
<div class='longitude'></div>
<div class='longitude flip'></div>
<style>
  body {background:#191919;margin: 75 125}
  div{background:#4F77FF}
  .circle {width:150;height:150;border-radius:50%}
  .longitude {
    height:170;
    width:145;
    border-radius:50%;
    position:absolute;
    top:55;
    left:155;
    background:transparent;
    border:10px solid #191919;
  }
  .flip{transform(rotate(180deg));left:80}
  .divider{
    height:10;
    width: 150;
    margin-top: -120;
    background:#191919;
  }
  .horizontal{margin-top: 30}
  .vertical{
    transform:rotate(90deg);
    margin: -50 0 0 0;
  }
</style>
```