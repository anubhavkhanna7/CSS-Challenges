# Battle #2 - Visibility

## #14 - Web Maker Logo

[Link to the problem](https://cssbattle.dev/play/14)

![result](../../Images/Battle%202/14-Web-Maker-Logo.png)

```html
<div class='left'></div>
<div class='left-shadow'></div>
<div class='right-shadow'></div>
<div class='right'></div>
<style>
  body {background: #F2F2B6;}
  div {
    width: 0;
    border-right: 75px solid transparent;
    border-left: 75px solid transparent;
    position: relative;
  }
  .left {
    top: 77;
    left: 52;
    border-top: 130px solid #FF6D00;
    z-index: 1;
  }
  .left-shadow {
    margin: -53 0 0 72;
    border-top: 130px solid #FD4602;
  }
  .right-shadow {
    position: absolute;
    border-bottom: 130px solid #FF6D00;
    top: 85;
    left: 190;
  }
  .right {
    margin: -130 0 0 162;
    border-bottom: 130px solid #FD4602;
  }
</style>
```