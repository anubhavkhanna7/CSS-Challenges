# Battle #7- Backface

## #38 - Not Simply Square

[Link to the problem](https://cssbattle.dev/play/38)

![result](../../Images/Battle%207/38-Not-Simply-Square.png)

```html
<div></div><div></div><div></div>
<style>
  body {background: #293462;margin: 0 0 0 0;}
  div {
    display: inline-block;
    margin: 0 0 0 0 ;
  }
  div:first-child{
    width: 200px;
    height: 200px;
    background: #FFF1C1;
  }
  div:nth-child(2){
    width: 100px;
    height: 200px;
    background: #FE5F55;
  }
  div:nth-child(2):before {
    content: '';
    background: #A64942;
    position: absolute;
    width: 100px;
    height: 50px;
    top: 150;
    left: 200;
    z-index: 5;
  }
  div:nth-child(2):after {
    content: '';
    background: #A64942;
    position: absolute;
    width: 50px;
    height: 100px;
    top: 200;
    left: 150;
    z-index: 5;
  }
  div:nth-child(3){
    width: 200px;
    height: 100px;
    background: #FE5F55;
  }
</style>
```