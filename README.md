<!DOCTYPE html>
<html><head><title>display 프로퍼티</title>
<style>
div {
    border: 2px solid yellowgreen;
    color:blue;
    background: aliceblue;
}
span {
    border : 3px dotted red;
    background: yellow;
}
</style></head>
</head>
<body>
    
<h3>인라인, 인라인 블록, 블록</h3>
<hr>
나는 <div style="display:none">
        div(none)</div>입니다<br><br>
나는 <div style="display:inline">
        div(inline)</div>입니다<br><br>
나는 <div style="display:inline-block; height:50px">
        div(inline-block)</div>입니다<br><br>
나는 <div>div<span style="display:block">
                    span(block)</span>입니다.
</body>
</html>
