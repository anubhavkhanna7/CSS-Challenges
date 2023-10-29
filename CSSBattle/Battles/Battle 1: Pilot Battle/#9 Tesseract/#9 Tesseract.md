# Battle #1 - Pilot Battle

## #9 - Tesseract

[Link to the problem](https://cssbattle.dev/play/9)

![result](../../../Images/Battle%201/9-Tesseract.png)

```html
<div class='blue strip'></div>
<div class='z'></div>
<div class='blue f'>
  <div class='center'></div>
</div>
<style>
  body {
    background: #222730;
    margin: 75px 0;
  }
  .blue {
    background: #4CAAB3;
  }
  .strip {
    width: 100%;
    height: 150px;
  }
  .center {
    background: #393E46;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    position: absolute;
    top: 50px;
    left: 50px;
  }
  .z {
    background: #222730;
    width: 250px;
    height: 250px;
    transform: translate(75px, -200px) rotate(45deg);
  }
  .f {
    width: 150px;
    height: 150px;
    transform: translate(125px, -400px) rotate(45deg);
  }
</style>
```