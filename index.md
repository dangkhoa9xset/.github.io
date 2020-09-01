<html>
<head>
<style type="text/css">
/* important styles */

.fix-column {
    float: left;
}
.thead {
    height: 40px;
    white-space: nowrap;
}
.thead > span {
    display: inline-block;
    width: 120px;
    line-height: 40px;
    box-shadow: inset 0 0 1px 0 rgba(0,0,0,.5);
    background-color: rgba(255,0,0,.3);
    text-align: center;
}
.trow {
    white-space: nowrap;
}
.trow > span {
    display: inline-block;
    width: 120px;
    box-shadow: inset 0 0 1px 0 rgba(0,0,0,.5);
    line-height: 80px;
    height: 80px;
}
.tbody {
    height: 300px;
    overflow: auto;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}
.fix-column > .tbody {
    overflow: hidden;
    /*padding-bottom: 50px;*/
}
/*.fix-column > .tbody > .trow:last-child {margin-bottom: 50px;}*/

.fix-column > .tbody > .trow {
    margin-top: -50px;
    margin-bottom: 50px;
}
.fix-column > .tbody > .trow:first-child {
    margin-top: 0px;
}

.rest-columns {
    width: 350px;
}
.rest-columns > .thead {
    /*padding-right: 50px;*/
    overflow: hidden;
}
/*.rest-columns > .thead > :last-child {margin-right: 50px;}*/
.rest-columns > .thead > span {
    margin-right: 50px;
    margin-left: -50px;
}
.rest-columns > .thead > :first-child {margin-left: 0px;}
</style>
</head>

<body>
  <div class="total-wrapper">
    <div class="fix-column">
        <div class="thead">
            <span>Int1</span>
        </div>
        <div class="tbody">
            <div class="trow">
                <span>Lorem</span>
            </div>
            <div class="trow">
                <span>Lorem</span>
            </div>
            <div class="trow">
                <span>Lorem</span>
            </div>
            <div class="trow">
                <span>Lorem</span>
            </div>
        </div>
    </div>
    <div class="rest-columns">
        <div class="thead">
            <span>Int2</span><span>Int3</span><span>Int4</span><span>Int5</span>
        </div>
        <div class="tbody">
            <div class="trow">
                <span>ipsum</span><span>dolor</span><span>sit</span><span>amet</span>
            </div>
            <div class="trow">
                <span>ipsum</span><span>dolor</span><span>sit</span><span>amet</span>
            </div>
            <div class="trow">
                <span>ipsum</span><span>dolor</span><span>sit</span><span>amet</span>
            </div>
            <div class="trow">
                <span>ipsum</span><span>dolor</span><span>sit</span><span>amet</span>
            </div>
        </div>
    </div>
</div>
</body>

<script>
 
</script>
</html>
