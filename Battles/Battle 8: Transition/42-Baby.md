# Battle #8- Transition

## #42 - Baby

[Link to the problem](https://cssbattle.dev/play/42)

![result](../../Images/Battle%208/42-Baby.png)

```html
<div class='face'>
  <div class='hair'></div>
  <div class='hair right'></div>
  <div class='eye'></div>
  <div class='eye'></div>
  <div class='lip'></div>
</div>
<style>
  body{background:#293462;margin:0;z-index:2}
  div {background:#FFF1C1;border-radius:50%;display:inline-block;}
  .face {
    width: 200px;
    height: 200px;
    overflow: hidden;
    background: #FE5F55;
    margin: 50 100;
    border-top-left-radius: 100px;
    border-top-right-radius: 100px;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  }
  .eye {
    width: 60px;
    height:60;
    display: inline-block;
    margin: 40 16 0 20;
  }
  .lip {
    width:40;
    height:10;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border-bottom-right-radius: 5px;
    border-top-left-radius: 5px;
    margin: 16 0 0 80;
  }
  .hair {
    width: 99;
    height: 96;
    margin: -46 0 0 1;
  }
  .right {
    margin: -96 0 0 100;
  }
</style>
```