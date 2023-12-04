<html>
<head>
<link rel="stylesheet" href="css/estilo examen.css">
</head>
<body>
  <audio id="ronroneo" >
    <source src="audio/prrr.mp3" type="audio/mpeg">
  </audio>


  <button id="prrr" onclick="feliz()">Has encontrado a tu minino</button>

<img id= "i13" src="img/gato_feliz.png" >
<button id="volver" onclick="inicio()">volver a jugar</button>
          <script>

  document.getElementById("volver").addEventListener("click", inicio);


  function inicio() {
            window.location.href = "file:///C:/Users/hp/OneDrive/Desktop/programacion%20creativa/html/Examen/Inicio.html";
          }

  document.getElementById("prrr").addEventListener("click", feliz);

  function feliz() {
            var img = document.getElementById("prrr");
            img.style.display = "block";
          }
          var x = document.getElementById("ronroneo");

  function feliz() {
            x.play();
          }

  </script>

</body>
</html>
