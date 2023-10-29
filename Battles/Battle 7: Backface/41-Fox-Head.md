# Battle #7- Backface

## #41 - Fox Head

[Link to the problem](https://cssbattle.dev/play/41)

![result](../../Images/Battle%207/41-Fox-Head.png)

```html
<div></div><div></div>
<style>
  body {
    background: #293462;
    margin: 80 0 0 150;
  }
  div {
    display: inline-block;
    width: 50px;
    height: 135px;
    background: #FE5F55;
  }
  div:first-child {
    border-top-right-radius: 40px;
  }
  div:first-child:before {
    content: '';
    width: 30px;
    height: 30px;
    position: absolute;
    top: 140px;
    left: 165px;
    background: #293462;
    border-radius: 50%;
  }
  div:first-child:after {
    content: '';
    position: absolute;
    width: 100px;
    height: 70px;
    background: #293462;
    top: 180px;
    left: 100;
    border-top-right-radius: 40px;
  }
  div:nth-child(2) {
    border-top-left-radius: 40px;
  }
  div:nth-child(2):before {
    content: '';
    width: 30px;
    height: 30px;
    position: absolute;
    top: 140px;
    left: 205px;
    background: #293462;
    border-radius: 50%;
  }
  div:nth-child(2):after {
    content: '';
    position: absolute;
    width: 100px;
    height: 70px;
    background: #293462;
    top: 180px;
    border-top-left-radius: 40px;
  }
</style>
```