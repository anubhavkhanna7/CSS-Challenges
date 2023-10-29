# Battle #4 - Display

## #21 - Sitepoint Logo

[Link to the problem](https://cssbattle.dev/play/21)

![result](../../Images/Battle%204/21-Sitepoint-Logo.png)

```html
<div class='top'></div>
<div class='bottom'></div>
<style>
  body {background: #222;}
  div {
    width: 70px;
    height: 50px;
    border-top: 30px solid #F2994A;
    border-left: 30px solid #F2994A;
  }
  .top {
    margin: 86 0 0 130;
    border-top-left-radius: 10px;
    transform: rotate(315deg);
  }
  .bottom {
    position: absolute;
    top: 134;
    width: 70;
    height: 50;
    left: 160;
    border-color: #2D9CDB;
    transform: rotate(135deg);
    border-top-left-radius: 10px;
  }
</style>