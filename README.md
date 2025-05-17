# HTML
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Los juegos mas famosos de la ultima decada</h1>
  </header>
  <div class="brawl">
    <a href="https://supercell.com/en/games/brawlstars/"><button>Brawl Stars</button></a>
    <p>Este juego estuvo en su prime en 2024, aun lo sigue estando, pero poco a poco va callendo con eventos malos</p>
  </div>
  <div class="fortnite">
    <a href="https://www.fortnite.com/?lang=es-ES"><button>Fortnite</button></a>
  <p>Juego que marco una epoca con grandes creadores de contenido</p>
</div>
<div class="clash">
  <a href="https://supercell.com/en/games/clashroyale/"><button>Clash Royale</button></a>
<p>El juego va resurgiendo por los cambios que esta teniendo gracias a los nuevos managers</p>
</div>
<div class="fifa">
<a href="https://www.ea.com/es-es/games/fifa"><button>Fifa ?</button></a>
<p>De los mejores juegos de esta ultima decada, aunque hubo mas fifas antes del 2015</p>
</div>
<div class="barra">
  <h1>Si clicas el nombre del juego te lleva a la pagina oficial</h1>
</div>

</body>
</html>

# CSS

header h1{
font-size: 50px;
text-align: center;
border: 3px solid rgb(248, 244, 244);
padding: 10px;
background-color: lightgrey;
}
.brawl p{
  font-size: 20px;
}
.brawl{
  border: 3px solid rgb(252, 250, 250);
  width: 300px;
  text-align: center;
  margin: 10px;
  background-color: lightyellow;
  padding: 13px;
}

.brawl button{
  font-size: 27px;
  

}
.brawl button:hover{
  color: blue;
}
.fortnite button{
  font-size: 27px;
}
.fortnite p{
  font-size: 20px;
}
.fortnite button:hover{
  color: blue;
}
.fortnite {
  border: 3px solid rgb(245, 240, 240);
  width: 270px;
  background-color: lightcoral;
  position:absolute;
  right: 680px;
  top: 118px;
  padding: 23px;
  text-align: center;
  margin: 10px 0 10px auto;

}
.clash button{
 
  font-size: 27px;
}
.clash button:hover{
  color: blue;
}
.clash p{
  font-size: 20px;
  text-align: center;
}
.clash {
  border: 3px solid rgb(250, 247, 247);
  position: absolute;
  right: 343px;
  top: 126px;
  padding: 12px;
  text-align: center;
  width: 300px;
  background-color: lightblue;
}
body{
  background-image: url(gaming.jpeg);
}
.fifa{
  border: 3px solid rgb(252, 250, 250);
  background-color: lightgreen;
  text-align: center;
  position: absolute;
  right: 17px;
  width: 290px;
  top: 126px;
  padding: 11px;

}
.fifa p{
  font-size: 20px;
}
.fifa button{
  font-size: 27px;

}
.fifa button:hover{
  color: blue;
}
.barra{
  border: 5px solid rgb(243, 239, 239);
  text-align: center;
  background-color: white;
padding: 15px;
 border-radius: 90px;
 margin-right: 280px;
 margin-left: 280px;
 

}
.barra h1{
  font-size: 25px;
  
}
