
# Battle #2 - Visibility

## #15 - Overlap

[Link to the problem](https://cssbattle.dev/play/15)

![result](../../Images/Battle%202/15-Overlap.png)

```html
<div class='left'></div>
<div class='right'></div>
<style>
  body{
    background:#09042A;
    margin: 75 0 0 75;
  }
  div {
    width:150;
    height:150;
    border-radius: 50%;
    position: absolute;
  }
  .left {background:#7B3F61;}
  .right {
    background:#E78481;
    top: 75;
    left: 175;
  }
  .right:before {
    content:'';
    width:80;
    height:80;
    display:block;
    border-top-left-radius: 240px;
    border-bottom-right-radius: 220px;
    transform: rotate(315deg);
    position:absolute;
    top: 35;
    left: -16;
    background:#09042A;
}
</style>
```