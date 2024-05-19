<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css?family=Material+Icons|Material+Icons+Outlined|Material+Icons+Two+Tone|Material+Icons+Round|Material+Icons+Sharp" rel="stylesheet">
    <link rel="stylesheet" href="style (2).css">
    <title>Youtube</title>
</head>
<body>
<header>
    <div class="left-section">
        <i class="material icons">menu</i>
        <img src="images/youtube-logo.png" alt="">
    </div>
        <div class="mid-section">
        <form>
        <input type="text" placeholder="search">
        <button><i class="material-icons">search</i></button>
        </form>
        <i class="material-icons mic">mic</i>
    </div>
    <div class="right-section">
        <a href=""><i class="material-icons mic">video_call</i></a>
        <a href=""><i class="material-icons mic">apps</i></a>
        <a href=""><i class="material-icons mic">notifications</i></a>
        <a href=""><i class="material-icons mic">account_circle</i></a>
    </div>
</header>
</body>
</html>

 @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
    margin : 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    font-size: 10px;
}

body {
    font-family: "Roboto","Arial",sans-serif;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 56px;
    padding: 0 16px;
}

.left-section {
    display:flex;
    align-items: center;
    cursor: pointer;
}

.left-section img{
    width: 46%;
    padding-left: 16px;
}

.mid-section{
    display: flex;
    align-items: center;
    margin-left: -9%;
}

.mid-section form{
    display: flex;
    height: 40px;
    width: 628px;
}

.mid-section input {
    width: 100%;
    border-radius: 2px 2px 2px 2px;
    padding: 12px;
    font-size: 1.6rem;
    border-right: none;
}

.mid-section button{
    width: 64px;
    border: 3px dotted fuchsia;
    border-radius: 2px 2px 2px 2px;
    padding-top: 4px;
    background-color: aqua;
    cursor: pointer;
}

.mid-section button:hover {
    border-color: blue;
    background-color: turquoise;
}

.mid-section .mic{
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: blue;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 10px;
    cursor: pointer;
}

.right-section{
padding-right: 18px;
text-decoration: none;
color:black;
}




