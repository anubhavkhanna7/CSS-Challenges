# Battle #4 - Display

## #26 - Smiley

[Link to the problem](https://cssbattle.dev/play/26)

![result](../../Images/Battle%204/26-Smiley.png)

```html
<div></div><div></div><div class='u'></div>
<style>
  body {background: #6592CF;margin: 40 0 0 40;}
  div {
    display: inline-flex;
    width: 80px;
    height: 40px;
    border-right: 20px solid #060F55;
    border-left: 20px solid #060F55;
    border-top-left-radius: 100px;
    border-top-right-radius: 100px;
    border-top: 20px solid #060F55;
  }
  div:nth-child(2) {
    margin-left: 80px;
  }
  .u {
    margin: 100;
    transform: rotate(180deg);
  }
</style>
```