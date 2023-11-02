# Battle #11 - Overflow

## #54 - Black Lives Matter

[Link to the problem](https://cssbattle.dev/play/54)

![result](../../Images/Battle%2011/54-Black-Lives-Matter.png)

```html
<div class='fingers'><div></div><div></div><div></div><div></div></div>
<div class='palm'></div>
<div class='wrist'></div>
<div class='thumb'></div>
<style>
  body {background:#F9E492;margin: 78 0 0 155;}
  div:not(.fingers) {background:#191919}
  .fingers div {
    width:20;
    height:45;
    display:inline-block;
    border-radius:50px;
    margin-right: 5;
  }
  .fingers div:nth-of-type(2){height:55}
  .fingers div:nth-of-type(4){height:35}
  .palm{
    width:100;
    height:40;
    margin: 5 0 0 -5;
    border-bottom-left-radius:10px;
    border-bottom-right-radius:10px;
  }
  .wrist{
    width:50;
    height:45;
    margin:0 0 0 20;
    border-bottom-left-radius:10px;
    border-bottom-right-radius:10px;
  }
  .thumb{
    width:20;
    height:65;
    border-radius:50px;border:5px solid #F9E492; position:absolute;transform:rotate(60deg);top:104;left:152}
</style>
```