# Battle #5 - Inline

## #29 - Suffocate

[Link to the problem](https://cssbattle.dev/play/29)

![result](../../Images/Battle%205/29-Suffocate.png)

```html
<div>
  <p></p>
</div>
<style>
  body {background: #F3AC3C;margin: 0 0 0 0;}
  div {
    width: 133px;
    height: 133px;
    background: #dd6b4d;
    transform: translate(134px, 83px) rotate(45deg);
    background: #1A4341;
  }
  div:before {
    content: '';
    width: 133px;
    height: 171px;
    background: #F3AC3C;
    position: absolute;
    border-radius: 50%;
    top: -18;
    left: -108;
  }
  div:after {
    content: '';
    width: 133px;
    height: 171px;
    background: #F3AC3C;
    position: absolute;
    border-radius: 50%;
    top: -18;
    left: 108;
  }
  p:before {
    content: '';
    background: #F3AC3C;
    width: 170px;
    height: 140px;
    position: absolute;
    border-radius: 50%;
    top: 109;
    left: -20;
  }
  p:after {
    content: '';
    background: #F3AC3C;
    width: 170px;
    height: 140px;
    position: absolute;
    border-radius: 50%;
    top: -114;
    left: -20;
  }
</style>
```