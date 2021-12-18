<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HN oldala</title>
     </head>
     <style>
         body{margin: 0;
        font-family: "Lato",sans-serif;}
        .sidebar{
            margin: 0;
            padding: 0;
            width: 200px;
            background-color: #b42d2d;
            position: fixed;
            height: 100%;
            overflow: auto;
        }
.sidebar a{
    display: block;
    color: black;
    padding: 16px;
    text-decoration: none;
}
.sidebar a.active{
    background-color: #000000;
    color: white;
}
.sidebar a:hover:not(.active){
    background-color: red;
    color: blueviolet;
}
.div.content {
    margin-left: 200px;
padding: 1px 16px;
height: 1000px;
}
@media screen and (max-width: 700px) {
  .sidebar {
    width: 100%;
    height: auto;
    position: relative;
  }
  .sidebar a {float: left;}
  div.content {margin-left: 0;}
}

@media screen and (max-width: 400px) {
  .sidebar a {
    text-align: center;
    float: none;
  }
}
     </style>
<body>
    <nav>
        <button><a href="https://github.com/norboka/kollazs/blob/main/kollazs.md" style="color: rgb(204, 28, 28);">HOME</a> |</button>
        <button><a href="https://github.com/norboka/kollazs/blob/main/keplink" style="color: rgb(30, 0, 161);">1.FELADAT</a> |</button>
        <button><a href="https://github.com/norboka/kollazs/blob/main/lista" style="color: rgb(33, 0, 124);">2.FELADAT</a> |</button>
        <button><a href="https://github.com/norboka/kollazs/blob/main/orarend.html" style="color: rgb(0, 2, 136);">3.FELADAT</a> |</button>
        
    </nav>
    <h1 style="color: aqua;"></h1>
    <h2 style="color: blueviolet;"></h2>
    <h3 style="color: brown;"></h3>
    <h4 style="color: coral;"></h4>
    <h5 style="color: darkgreen;"></h5>
    <h6 style="color: darkorange;"></h6>
    <p>1.feladat:</p>
    <a href="https://github.com/norboka/kollazs/blob/main/keplink"> képlink</a>
    <p>2.feladat:</p>
    <a href="https://github.com/norboka/kollazs/blob/main/lista">listák</a>
    <p>3.feladat:</p>
    <a href="https://github.com/norboka/kollazs/blob/main/orarend.html">órarend</a>
<p>ez itt a kollazsom:</p>
<img src="https://www.ivanics.hu/uploads/menuitems/757/big/2019_ford_ranger_raptor_performance_blue_117.jpg" alt="ford raptor" width="150px" height="150px">
<img src="https://i.ytimg.com/vi/s9-kXuszmiI/maxresdefault.jpg" alt="bmw m5 e60" width="150px" height="150px">
<img src="https://vezess2.p3k.hu/app/uploads/2020/04/8877b9cd-b253-49a3-bfec-e94c2b1d40fa-700x467.png" alt="bmw e30" width="150px" height="150px">
</body>
</html>
