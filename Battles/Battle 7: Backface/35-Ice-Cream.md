# Battle #7- Backface

## #35 - Ice Cream

[Link to the problem](https://cssbattle.dev/play/32)

![result](../../Images/Battle%207/35-IceCream.png)

```html
<div></div>
<style>
  body {background: #293462;margin: 50 0 0 150;}
  div {
    width: 100px;
    height: 150px;
    background: #FFF1C1;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
  }
  div:before {
    content: '';
    position: absolute;
    width: 30px;
    height: 50px;
    top: 200;
    left: 185;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    background: #FE5F55;
  }
  div:after {
    content: '';
    position: absolute;
    width: 30px;
    height: 10px;
    top: 200;
    left: 185;
    background: #A64942;
  }
</style>
```