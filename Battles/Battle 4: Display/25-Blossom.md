# Battle #4 - Display

## #25 - Blossom

[Link to the problem](https://cssbattle.dev/play/25)

![result](../../Images/Battle%204/25-Blossom.png)

```html
<div>
  <div class='green'></div>
  <div class='yellow'></div>
</div>
<div>
  <div class='green'></div>
  <div class='yellow'></div>
</div>
<style>
  body{background: #998235;}
  div{position: absolute;}
  .green {
    width: 80px;
    height: 100px;
    background: #1A4341;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
  }
  div:first-child {
    .green {
      top: 52;
      left: 102;
    }
    .yellow {
      top: 172;
      left: 102;
    }
  }
  .yellow {
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
  }
  div:last-of-type{
    .green {
      transform: rotateY(180deg);
      top: 132;
      left :202;
    }
    .yellow {
      transform:rotateY(180deg);
      top: 52;
      left: 202;
    }
  }
</style>
```