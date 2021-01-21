<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

-AHOL:
<html lang="hu"> = oldal nyelve

<meta charset="utf-8"> = karakter kódolás

<link rel="icon" type="image/png" href="icon.png"> = ikon behívása (ez van a title mellett mikor megnyitod az oldalt)

<meta name="viewport" content="width=device-width, initial-scale=1"> =  különböző resolutionoknál ne essen szét a weblap

<link rel="stylesheet" type="text/css" href="style.css"> = css fájlt így hívsz be
<b>Bold</b>
<strong>vastag</strong>
<i>italic</i>
<em>emphasized szöveg</em>
<small>kicsi betű</small>
<mark>szövegkiemelő</mark>
<del>kihúzás</del>
<sub>süllyedt szöveg</sub>
<sup>felemelt szöveg</sup>

* {
    box-sizing: border-box;
}
body {
    margin-left: auto; középre rakás ezzel a kettővel!
    margin-right: auto; !!!
    background-image: url(/gyakorlas/background.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}
p {    
border: 2px dotted rgb(202, 199, 11);
}
<h5>Clearfix</h5>
.clearfix::after {
    content: "";
    clear: both;
    display: table;
  }