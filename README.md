<!DOCTYPE html>
<html>
    <head>
        <title>Image As Cursors</title>
        <link href="https://fonts.googleapis.com/ css?family=PT+Sans+Caption: 700" rel="stylesheet">
        <link rel="stylesheet" href="cursors.css">
        <style>button{
    font-size:30px;
    background-color:yellow;
    padding-left:30px;
    padding-right:30px;
    padding-top:30px;
    padding-bottom:30px;
    text-transform:uppercase ;
    width:200px;
    border-color:#05fff3;
    border-width:7px;
}
body{
    background-color:#475754;
    top:0;
    bottom:0;
    right:0;
    left:0;
}
button:nth-child(1){
    position:relative ;
    cursor:url("rocket.png"),auto ;
    margin-left:82px;
    margin-top:30px;
}
button:nth-child(2){
    position:relative ;
    cursor:url("plane.png"),auto ;
    margin-left:82px;
    margin-top:30px;
}</style>
</head>

<body>

        <div class="container">
            <button>Rocket</button>
            <button>Plane</button>
        </div>
</body>
</html>
