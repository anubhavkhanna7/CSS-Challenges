# Battle #1 - Pilot Battle

## #3 - Ups and Downs

[Link to the problem](https://cssbattle.dev/play/4)

![result](./images/1-simply-square.png)

```html
<div class='circle'>
  <div class='down'>
    <div class='bowl'></div>
  </div>
  <div class='up'>
    <div class='bowl'></div>
  </div>
  <div class='down'>
    <div class='bowl'></div>
  </div>
</div>
<style>
  body {
    background: #62306D;
    margin: 50px 50px;
  }
  .circle {
    display: flex;
    flex-direction: row;
  }
  .bowl {
    width: 100px;
    height: 50px;
    background: #F7EC7D;
  }
  .down .bowl {
    margin-top: 100px;
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  }
  .up .bowl {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
  }
</style>
```