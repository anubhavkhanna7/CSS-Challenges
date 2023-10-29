
# Battle #2 - Visibility

## #17 - Fidget Spinner

[Link to the problem](https://cssbattle.dev/play/17)

![result](../../Images/Battle%202/17-Fidget-Spinner.png)

```html
<div class='circle-border circle round left'></div>
<div class='circle-border circle round right'></div>
<div class='circle-fill circle round pos-abs top'></div>
<div class='circle-fill circle round pos-abs bottom'></div>
<div class='center-connect pos-abs'></div>
<style>
  body {
    background: #09042A;
    margin: 110 0 0 100;
  }
  .circle {width: 60px;height: 60px;}
  .pos-abs {position: absolute;}
  .round {border-radius: 50%;}
  .circle-border {
    background: transparent;
    border: 10px solid #E78481;
    display: inline-flex;
    transform: rotate(45deg);
  }
  .circle-border:before {
    content: '';
    border-radius: 50%;
    background: #09042A;
    z-index: 5;
    width: 60px;
    height: 60px;
  }
  .left {border-top-right-radius: 10px;margin-right: 36px}
  .right {border-bottom-left-radius: 10px;}
  .top {
    top: 57;
    left: 160;
    border: 10px solid #09042A;
  }
  .bottom {
    top: 163;
    left: 160;
    border: 10px solid #09042A;
  }
  .circle-fill {
    background: #F5BB9C;
  }
  .center-connect {
    width: 100;
    height: 47;
    top: 125;
    left: 150;
    background: #E78481;
    z-index: -1;
  }
</style>
```