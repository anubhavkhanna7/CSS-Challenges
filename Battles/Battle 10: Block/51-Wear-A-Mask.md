# Battle #10 - Block

## #51 - Wear A Mask

[Link to the problem](https://cssbattle.dev/play/51)

![result](../../Images/Battle%2010/51-Wear-A-Mask.png)

```html
<div class='handle'></div>
<div class='cup'>
  <div class='lip red'></div>
  <div class='lip red bottom'></div>
  <div class='red dot'></div>
</div>
<div class='handle flip'></div>
<style>
  body {background: #293462;margin: 100 0 0 65;}
  div {display:inline-block;}
  .handle {
    width: 60px;
    height: 40px;
    border: 10px solid #FFF1C1;
    border-top-left-radius: 40px;
    border-bottom-left-radius: 40px;
  }
  .cup {
    width: 150;
    height: 100;
    background:#FFF1C1;
    position: absolute;
    left: 125;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  }
  .flip {
    transform: rotateY(180deg);
    margin-left: 106;
  }
  .red {background:#FE5F55;}
  .lip {
    width: 40px;
    height: 10px;
    border-radius: 10px;
    position: absolute;
    top: 20;
    left: 20;
  }
  .bottom {
    top: 40;
  }
  .dot {
    width:40;
    height:40;
    border-radius:50%;
    margin: 40 0 0 90;
  }
</style>