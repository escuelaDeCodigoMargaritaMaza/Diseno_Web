<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animaciones CSS</title>
  <style>
    @keyframes movimiento-lateral {
      from {
          left: 0px;
      }
      to {
          left: 1000px;
      }
    }   

    #anim {
      animation-name: movimiento-lateral;
      animation-duration: 3s;
      animation-iteration-count: infinite;
      animation-direction: alternate;/*para que vuelva a su posicion inicial */
      width: 100px;
      background-color: Teal;
      color: #fff;
      position: relative;
      padding: 2px;
    }
  </style>
</head>
<body>
  
  <div id="anim">Esto es una animación</div>

</body>
</html>
