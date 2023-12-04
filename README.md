<html>
<head>
<link rel="stylesheet" href="css/estilo examen.css">
</head>
<body id="b1">


  <img id= "i8" src="img/sala de estar1.png">


  <button id="puerta" onclick="mover()">a</button>
  <button id="otraPuerta" onclick="otroMover()">b</button>
  <button id="puertaC" onclick="moverC()">c</button>



  <script>

  document.getElementById("puerta").addEventListener("click", mover);


  function mover() {
    window.location.href = "file:///C:/Users/hp/OneDrive/Desktop/programacion%20creativa/html/Examen/pieza.html";
  }

document.getElementById("otraPuerta").addEventListener("click", otroMover);

function otroMover() {
  window.location.href = "file:///C:/Users/hp/OneDrive/Desktop/programacion%20creativa/html/Examen/Atico.html";
}

document.getElementById("puertaC").addEventListener("click", moverC);

function moverC() {
  window.location.href = "file:///C:/Users/hp/OneDrive/Desktop/programacion%20creativa/html/Examen/sotano.html";
}
</script>





</body>
</html>
