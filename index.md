<!DOCTYPE html>
<html>

<head>
<style>
    html{
        background-image: url("files/Background.jpg");
        cursor:url(files/mycur.png), auto;
    }

    .button{
        background-color: firebrick;
        border: firebrick;
        color: white;
        padding: 15px 25px;
        text-align: center;
        font-size: 30px;
        cursor: pointer;
        transition-duration: 0.4s;
    }

    .button:hover {
        background-color:black;
    }

    #mainText{
        margin: 0 auto;
        border: 1px solid black;
        width: 1000px;
        height: 500px;
        background-color: #ff0000;
        color: white;
        font-size: 75px;
        animation: textRotate 10s infinite;
        
    }

    #video{
        /*margin-left: 30%;
        margin-right: 30%;
        margin-top: 100px;*/
        /*margin: 0 auto;*/
        margin-top: 100px;
    }

    @keyframes textRotate{
        50% {transform: rotate(720deg); background-color: #0000ff; color: black;}
    }

    @keyframes videoRotate{
        50%{transform: rotate(720deg);}
    }

</style>
</head>

<body>

    <form action="https://cary-hoco.org">
        <button class=button type=submit>Check out my other work!</button>
    </form>

    <div id="mainText" style="text-align: center;">
        <h1>Carter 4 Webmaster</h1>
    </div>

    <div id="video" style="text-align: center;">
        <iframe width="640" height="360" src="https://www.youtube.com/embed/OwVgE-DNfYY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

</body>

</html>