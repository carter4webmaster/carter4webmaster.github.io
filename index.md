<!DOCTYPE html>
<html>

<head>
<style>
    html{
        background-image: url("https://images-na.ssl-images-amazon.com/images/I/21IkEVBF1rL._AC_SX466_.jpg");
        cursor:url(files/mycur.png), auto;
    }

    .custom{
        margin: auto;
        border: 1px solid black;
        width: 800px;
        height: 500px;
        background-color: #ff0000;
        color: white;
        font-size: 75px;
        animation: billRotate 10s infinite;
        
    }

    /*#container{
        overflow: hidden;
        width: 100%;
    }*/

    #video{
        margin-left: 30%;
        margin-right: 30%;
        margin-top: 100px;
    }

    /*#left{
        float:left;
        width: 50px;
        
    }*/

    /*#right{
        float: right;
        visibility: hidden;
    }*/

    #audio{
        margin: auto;
        border: 1px solid black;
        width: 200px;
        height: 100px;
        background-color: coral;
        color: white;
        animation: billRotate 10s infinite;
        visibility: hidden;
    }

    @keyframes billRotate{
        50% {transform: rotate(720deg); background-color: #0000ff; color: black;}
    }

    @keyframes videoRotate{
        50%{transform: rotate(720deg);}
    }

</style>
</head>

<body>

<h1></h1>

<p>
    
</p>

<div class=custom>
    <h1>Carter 4 Webmaster</h1>
</div>

<!--<div id="container">-->

    <!--<div id="left">
        <p>filler text</p>
    </div>-->

    <div id="video">
        <iframe width="640" height="360" src="https://www.youtube.com/embed/vhx1iphnaNQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <!--<div id="right">
        <p>filler text</p>
    </div>>-->

<!--</div>-->

<div id="audio">
<audio controls autoplay>
    <source src=files/bashar.mp3 type="audio/mp3">
    Your browser does not support the audio element.
</audio>
</div>

</body>

</html>