# Battle #4 - Display

## #22 - Cloud

[Link to the problem](https://cssbattle.dev/play/22)

![result](../../Images/Battle%204/22-Cloud.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    background: #F5D6B4;
    margin: 115 0 0 100;
  }
  div {
    background: #D86F45;
    border-radius: 50%;
  }
  div:first-child {
    width: 100px;
    height: 100px;
    position: absolute;
    top: 85;
    left: 180;
  }
  div:nth-child(2) {
    width: 100px;
    height: 100px;
  }
  div:nth-child(3) {
    width: 50px;
    height: 50px;
    position: absolute;
    top: 165;
    left: 250;
  }
  div:nth-child(4) {
    position: absolute;
    border-radius:0;
    width: 123px;
    height: 50px;
    top: 165px;
    left: 150px;
  }
</style>
```