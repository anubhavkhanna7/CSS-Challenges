# Battle #1 - Pilot Battle

## #6 - Missing Slice

[Link to the problem](https://cssbattle.dev/play/6)

![result](../../Images/Battle%201/6-Missing%20Slice.png)

```html
<div class='flex'>
  <div class='common'>
    <div class='blue'></div>
    <div class='white'></div>
  </div>
  <div class='common'>
    <div class='yellow'></div>
  </div>
</div>
<style>
  body {
    background: #E3516E;
    margin: 50px 100px;
  }
  .flex {
    display: flex;
  }
  .common {
    flex-direction: column;
  }
  .common div {
    width: 100px;
    height: 100px;
  }
  .blue {
    background: #51B5A9;
    border-top-left-radius: 100px;
  }
  .yellow {
    background: #FADE8B;
    border-top-right-radius: 100px;
  }
  .white {
    background: #F7F3D7;
    border-bottom-left-radius: 100px;
  }
</style>
```