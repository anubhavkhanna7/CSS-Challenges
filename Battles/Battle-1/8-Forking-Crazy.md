# Battle #1 - Pilot Battle

## #8 - Forking Crazy

[Link to the problem](https://cssbattle.dev/play/8)

![result](../../Images/Battle%201/8-Forking%20Crazy.png)

```html
<span>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</span>
<div class='mid'></div>
<div class='bottom'></div>
<style>
  body {
    background: #6592CF;
    margin: 50px 130px 0;
  }
  div {background: #060F55}
  span {
    height: 110px;
    width: 140px;
    display: flex;
    position: relative;
    /* top: 10px; */
  }
  span div {
    width: 20px;
  }
  span > div:nth-child(odd) {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    background: #060F55;
  }
  span > div:nth-child(even) {
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    box-shadow: 0 20px 0 3px #060F55;
    background: #6592CF;
  }
  .mid {
    width: 140px;
    height: 90px;
    border-bottom-left-radius: 75px;
    border-bottom-right-radius: 75px;
    position: absolute;
  }
  .bottom {
    position: absolute;
    bottom: 0;
    width: 20px;
    height: 60px;
    margin-left: 60px;
  }
</style>
```