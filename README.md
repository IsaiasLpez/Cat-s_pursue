<html>
<head>
<link rel="stylesheet" href="css/estilo examen.css">
</head>
<body id="b1">

<audio id="screamer" >
  <source src="audio/scream4.mp3" type="audio/mpeg">
</audio>

  <img id= "i6" src="img/Satanas.png" style="display:none;">

<button id="miBoton" onclick="reproducir()" type="button">x̴̡͈̘̋̌͠͝</button>
<button id="salida" onclick="susto()">y̸̢͍̲̪͔̹̱̭̅̑̑͐̎́͛̀͒̓̈̈́̕̕͜͝</button>


<script>

document.getElementById("salida").addEventListener("click", salvacion);

function salvacion() {
  window.location.href = "file:///C:/Users/hp/OneDrive/Desktop/programacion%20creativa/html/Examen/sala_principal.html";
}

document.getElementById("miBoton").addEventListener("click", susto);

function susto() {
  var img = document.getElementById("i6");
  img.style.display = "block";
}
var x = document.getElementById("screamer");

function reproducir() {
  x.play();
}

</script>


</div>
</body>
</html>
