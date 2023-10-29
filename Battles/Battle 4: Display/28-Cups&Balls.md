# Battle #4 - Display

## #28 - Cups and Balls

[Link to the problem](https://cssbattle.dev/play/28)

![result](../../Images/Battle%204/28-Cups&Balls.png)

```html
<div></div>
<div class='yellow curved flip'></div>
<div class='curved flip'></div>
<div class='yellow'></div>
<div class='yellow curved'></div>
<div></div>
<div class='yellow'></div>
<div class='curved '></div>
<style>
  body {background: #1A4341;margin: 90 0 0 70;}
  .yellow {background: #F3AC3C;}
  .curved {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
  }
  .flip {
    transform: rotate(180deg);
  }
  div {
    display: inline-block;
    width: 50px;
    height: 50px;
    background: #998235;
    border-radius: 50%;
    margin: 0 16 16 0;
  }
</style>
```