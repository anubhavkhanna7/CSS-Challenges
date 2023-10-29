# Battle #6 - Conic

## #32 - Band Aid

[Link to the problem](https://cssbattle.dev/play/32)

![result](../../Images/Battle%206/31-Equals.png)

```html
<div></div>
<style>
  div {
    width:50px;
    height:200px;
    background:#F3AC3C;
    position:absolute;
    transform:rotate(315deg);
    top:50;
    left:175;
  }
  div:before{
    content:'';
    width:50px;
    height:200px;
    background:#A3A368;
    position:absolute;
    transform:rotate(90deg);
  }
  div:after{
    content:'';
    width:50;
    height:50;
    background:#FBE18C;
    position:absolute;
    top:75;
  }
</style>
```