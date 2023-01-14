
       <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <style>
            /* barra */
            ::-webkit-scrollbar{
                width: 12px;
                background-color: blue;
            }
            ::-webkit-scrollbar-thumb{
                border-radius: 10px;
                background-color: blueviolet;

            }
            ::-webkit-scrollbar-track{
                border-radius: 10px;
                box-shadow: inset 0 0 6px rgba(0,0,0,0.9);
                background-color: aqua;
            }
            /* secciones */
            .section1{
                height: 100vh;
                background-color: pink;
                display: flex;
                align-items: center;
            }
            .section2{
                height: 100vh;
                background-color: rgb(209, 6, 40);
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .section3{
                height: 20vh;
                background-color: rgb(49, 13, 19);
                display: flex;
                align-items: center;
            }
            /* desplazamiento */
         @keyframes movimiento-lateral { from { left: 0px; } to { left: 1000px; } }
            #anim {
              animation-name: movimiento-lateral;
              animation-duration: 3s;
              animation-iteration-count: infinite;
              animation-direction: alternate;/*para que vuelva a su posicion inicial */
              width: 200px;
              background-color: Teal;
              color: #fff;
              position: relative;
              padding: 2px;
            }
           /* imagen */
            img{
                width: 10%;
            }
            .img1:hover{
                border-radius: 50%;
                box-shadow: 0 0 15px 15px orangered;
                transform: rotate(360deg);
                transition: all .5s ease-in-out;
            }
            .section3{
                opacity: 0;
                transform: translateX(1500px);
                animation: fadeIn .8s linear forwards;
            }
            .section3 p{
                font-size: 100px;
                color: white;
            }
            @keyframes fadeIn{
                to{
                    transform: translateX(0px);
                    opacity: 1;
                }
            }

            /* reflejo */

            .svg {
                max-height: 40vh;
                -webkit-box-reflect: 
                below -1px 
                linear-gradient(to bottom, transparent, 
                rgba(0, 0, 0, 0.8));
            }
            .section4{
                height: 100vh;
                background-color: rgb(145, 228, 106);
                display: flex;
                align-items: center;
            }

            /* maquina escribir */
            .section5{
                height: 100vh;
                background-color: rgb(15, 15, 15);
                display: flex;
                align-items: center;
            }

                .olivetti {
                    font-size: 2rem;
                    font-family: monospace;
                    color: white;
                    width: 50%;
                    animation: olivetti 5s steps(30), pampalluga 0.5s step-end infinite alternate;
                    white-space: nowrap;
                    overflow: hidden;
                    border-right: 2px solid white;
                }

                @keyframes olivetti {
                    from {
                        width: 0;
                    }
                }

                @keyframes pampalluga {
                    50% {
                        border-color: transparent;
                    }
                }


            </style>
    </head>
    <body>
        <div class="section1">
          <p id="anim">  Esto es una animación</p>
        </div>
        <div class="section3">
            <p>HOLA MUNDO</p>
          </div>
          <div class="section2">
            <img class="img1" src="https://stylecaster.com/wp-content/uploads/2012/02/157728_13288080041.jpg" alt="">

          </div>
          <div class="section4">
             <img class="svg" src="https://pngimg.com/uploads/orange/orange_PNG749.png" alt="">
          </div>

          <div class="section5">
            <div class="olivetti">
    DAVID SANTILLAN BRETON
        </div>


    </body>
    </html>
