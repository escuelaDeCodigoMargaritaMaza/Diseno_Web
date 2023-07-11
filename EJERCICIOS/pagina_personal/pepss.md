<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ricardo Aguila</title>
    <link rel="stylesheet" href="index.css/estilo.css">
    <style>
    *{
        margin: 0;
        padding: 0;
        
    }
    body{
        font-family: 'Roboto Mono', monospace;/*ESTILO DE FUENTE*/
    }

    li{/*datos en cajas*/
        background: rgb(182, 252, 161);/*fondo caja*/
        color: rgb(233, 158, 233);/*color letras*/
        list-style: none;
        width: 150px;
        margin-bottom: 20px;
        padding: 20px;
        text-align: center;
        border-style: solid;
        border-color: rgb(233, 158, 233);
        border-radius: 35px;
        margin-right: 10px;
        font-size: 1em;
    }
    nav p{
        font-size: 3em;
        color: aqua;
        text-shadow: 2px 2px 2px red;
    }

    nav img{
        display: none;
    }

    li:hover{
        /*opacity: .5;(lo hace opaco) */
        background-color: rgb(251, 231, 253);/*al tocar cambia de color el fondo y*/
        border: solid;
    }

    nav{
        width: 100%;
        height: 20vh;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .menu{/*apartado de opciones*/
        display: flex;
        height: 15px;
        align-items: center;/*centrar opciones menu*/
    }
    /*termina nav*/
    /*establecemos el 100% de ancho y alto de la pantalla para header*/
    header{
        width: 100%;
        height: 70vh;
        background: url(https://github.com/peps633/Diseno_Web/blob/main/trbajoenclase/pagina%20personal/img/fondo.jpg?raw=true);
        background-repeat:no-repeat;
        background-position: center;
        background-size: cover;
    }
    .caja{
    height: 50vh;;
    display: flex;/*hace que el cuadro este al lado y no abajo*/
    }
    .cajita{
        height: 62vh;
        width: 50%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    img{
        width: 50%;
    }

    h1{
        width: 50%;
        font-size: 4em;
    }
    .cajita p{
        font-size: 2em;
        width: 80%;
    }


    span{
        color: rgba(174, 105, 238, 0.986);
    }

    /*comienza seccion */

    .contenedor{
        width: 90%;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 30vh;
        margin: auto;
    }

    .texto{
        border-style: solid;
        border-top-left-radius: 30px;
        border-bottom-right-radius: 30px;
        background: rgb(182, 252, 161);
        color: rgb(233, 158, 233);
        border-color: rgb(233, 158, 233);
        height: 20vh;
        font-size: 3.7vh;
        text-align: center;

    }

    .recorrido{
        width: 100%;
        height: 70vh;
        background: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxN1QEeWgTuU2Mh_W4q1DcMldK8OFE82szNG7Cm8thgtmUYRzGfWSZiTVQYbfPWoZzIoU&usqp=CAU);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
    }
    .cajas{
        display: flex;
        justify-content: space-around;
        height: 60vh;
        align-items: end;
    }
    .modulo{
        background:rgba(182, 252, 161, 0.699);
        width: 25%;
        height: 50vh;
    }
    .modulo img{
        width: 100%;
    }
    h3{
       color: rgba(174, 105, 238, 0.986)
    }

    .whatsapp{
        background-attachment: fixed;
        height: 4vh;
        width: 4vh;
        position: relative;/*absolute sirve para poner imagenes arriba*/
        bottom: 5px;
        right: 5px;
    }

    @media(max-width:450px){/*modelo responsivo telefono*/


    .menu{
        display: none;
    }

    nav img{
        display: block;
        height: 50px;
        width: 50px;
    }

    .caja{
        height: 80vh;
        flex-direction: column;
    }
    .cajita{
        height: 40vh;
        width: 100%;
    }

    }

    </style>
</head>
<body>
    <header>
        <nav>   
            <p>RSAC</p>
            <img src="img/menu.png">
            <ul class="menu">
                <li>INICIO</li>
                <li>ACERCA DE MI</li>
                <li>DISEÑO WEB</li>
                <li>BASE DE DATOS</li>
                <li>ESPECIALIDAD</li>
                <li>CONTACTOS</li>
            </ul>
        </nav>

        <div class="caja">
            <div class="cajita">
                <h1>Ricardo  <span>Aguila</span></h1>
                <p>Hola, bienvenido a mi pagina personal en donde encontraras todos mis proyectos de la escuela de codigo c:</p>
            </div>
            <div class="cajita">
                <img src="https://github.com/peps633/Diseno_Web/blob/main/trbajoenclase/pagina%20personal/img/shinji.png?raw=true">
            </div>
        </div>
    </header>
    <main>

<!-- SECCION ACERCA DE  -->
        <section class="contenedor">
            <div class="texto">
                <h2>ACERCA DE MI</h2>
                <p>Tengo 18 años, quiero estudiar programacion, me encanta el cine, la musica y los videojuegos</p>
                
            </div>
        </section>

<!-- SECCION MODULOS -->
        <section div class="recorrido">
            <h2>RECORRIDO</h2>
            <div class="cajas">
                <div class="modulo">
                    <h3>NOMBRE MODULO</h3>
                    <img src="https://github.com/peps633/Diseno_Web/blob/main/trbajoenclase/pagina%20personal/img/bases.png?raw=true" alt="">
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit in ex eligendi quis qui itaque cupiditate repudiandae eaque quidem nemo!</p>
                    <a href="">Ir al modulo</a>
                </div>
                <div class="modulo">
                    <h3>NOMBRE MODULO</h3>
                    <img src="https://github.com/peps633/Diseno_Web/blob/main/trbajoenclase/pagina%20personal/img/bases.png?raw=true" alt="">
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit in ex eligendi quis qui itaque cupiditate repudiandae eaque quidem nemo!</p>
                    <a href="">Ir al modulo</a>
                </div>
                <div class="modulo">
                    <h3>NOMBRE MODULO</h3>
                    <img src="https://github.com/peps633/Diseno_Web/blob/main/trbajoenclase/pagina%20personal/img/bases.png?raw=true" alt="">
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit in ex eligendi quis qui itaque cupiditate repudiandae eaque quidem nemo!</p>
                    <a href="">Ir al modulo</a>
                </div>
            </div>    
        </section>
              
            
        </main>
        <footer>
            
        </footer>
        <img src="img/whatsapp.png" class="whatsapp">
</body>
</html>
