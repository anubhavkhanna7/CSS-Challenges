# Battle #7- Backface

## #37 - Tunnel

[Link to the problem](https://cssbattle.dev/play/37)

![result](../../Images/Battle%207/37-Tunnel.png)

```html
<div></div>
<style>
  body {background:#6592CF;margin: 25 0 0 75;}
  div {
    width: 250px;
    height: 250px;
    background: #243D83;
  }
  div:before {
    content: '';
    background: #6592CF;
    width: 150px;
    height: 150px;
    position: absolute;
    transform: rotate(15deg);
    top: 75;
    left: 125;
  }
  div:after {
    content: '';
    background: #243D83;
    width: 75px;
    height: 74.8px;
    position: absolute;
    transform: rotate(30deg);
    top: 113;
    left: 163;
  }
</style>
```