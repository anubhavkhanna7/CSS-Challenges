# Battle #11 - Overflow

## #56 - Skull

[Link to the problem](https://cssbattle.dev/play/56)

![result](../../Images/Battle%2011/56-Skull.png)

```html
<div class='base'>
  <div class='eye left'></div>
  <div class='eye'></div>
</div>
<div class='nose'></div>
<div class='jaw'>
  <div class='teeth'></div>  
  <div class='teeth mid'></div>  
  <div class='teeth right'></div>  
</div>
<style>
  body {background:#191919;margin: 85 140}
  div{background:#4F77FF}
  .base{
    width:120;
    height:100;
    border-top-left-radius:60px;
    border-top-right-radius:60px;
    border-bottom-left-radius:10px;
    border-bottom-right-radius:10px
  }
  .eye{
    background:#191919;
    width:40;
    height:40;
    border-radius:50%;
    display:inline-block
  }
  .left{margin:53 6 0 15}
  .jaw{
    width:80;
    height:30;
    border-bottom-left-radius:20px;
    border-bottom-right-radius:20px;
    margin-left:20
  }
  .teeth{
    background:#191919;
    width:10;
    height:10;
    display:inline-block;
    margin:20 0 0 20;
    border-top-left-radius:5px;
    border-top-right-radius:5px
  }
  .mid{margin-left:1}
  .right{margin-left:1}
  .nose{
    width:20;
    height:20;
    position:absolute;
    border-radius:50%;
    background:#191919;
    top:176;
    left:190
  }
</style>
```