# Battle #10 - Block

## #47 - Corona Virus

[Link to the problem](https://cssbattle.dev/play/47)

![result](../../Images/Battle%2010/47-Corona-Virus.png)

```html
<div class='circle'>
  <div class='spot'></div>
  <div class='spot mid'></div>
  <div class='spot small'></div>
</div>
<div class='stick'></div>
<div class='stick right'></div>
<div class='stick left'></div>
<style>
  body{background:#1A4341;margin:100 150}
  div{background: #F3AC3C}
  .circle {
    width: 100px;
    height: 100px;
    border-radius: 50%;
  }
  .stick {
    height:180;
    width:10;
    border-radius:5px;
    margin: -150 0 0 45;
  }
  .right{
    transform: rotate(60deg);
    margin: -175 0 0 54;
  }
  .left {
    transform: rotate(300deg);
    margin: -170 0 0 54;
  }
  .spot {
    background: #998235;
    position:absolute;
    top: 120;
    left: 170;
    border-radius: 50%;
    width: 30px;
    height: 30px;
    z-index:1
   }
  .mid {
    width: 20px;
    height: 20px;
    top: 165;
    left: 190;
  }
  .small {
    width: 10px;
    height: 10px;
    top: 120;
    left: 220;
  }
</style>
```