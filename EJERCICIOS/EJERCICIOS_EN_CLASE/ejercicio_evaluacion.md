![image](https://user-images.githubusercontent.com/91554777/165175601-f95d8714-091a-4687-a21b-70a75beae3ea.png)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Título de página</title>
    </head>
    <body>

        <header>
            <h1 class="sombra">ENCABEZADO NIVEL 1</h1>
            <nav>
                <ul>
                    <li><a href="" id="enl1">ENLACE 1</a></li>
                    <li><a href="" id="enl2">ENLACE 2</a></li>
                    <li><a href="" id="enl3">ENLACE 3</a></li>
                    <li><a href="" id="enl4">ENLACE 4</a></li>
                </ul>
            </nav>
        </header>


        <main>

            <article class="espacio">
                <h2 class="subtitulos sombra">Encabezado nivel 2</h2>
                <p>Aqui va el texto del primer <b><span  class="subtitulos"> Párrafo</span></b></p>
                <p>Aqui va el texto del segundo párrafo</p>
            </article>

            <aside class="espacio sombra">
                <h2  class="subtitulos sombra">Apartado</h2>
                <p>Elige una opción</p>
                <form action="">
                    <input type="radio" name="opcion">Opción 1 <br>
                    <input type="radio" name="opcion">Opción 2 <br>
                    <input type="radio" name="opcion">Opción 3 <br>
                    <input type="submit" value="Enviar">
                </form>
            </aside>

        </main>


        <footer class="espacio">
            <p>Sección de información de contacto, derechos de autor, etc</p>

        </footer>

    </body>
    </html>


## AGREGA EL CSS NECESARIO A LA PÁGINA.


             /* SELECTOR UNIVERSAL */
            *{
                margin: 0;
                padding: 0;
                font-family: 'Open Sans', sans-serif;
            }

            /* ESTILOS DEL HEADER */
            header{
                background-color: rgb(68, 67, 67);
                
            }
            h1{
                font-size: 40px;
                color: aquamarine;
                text-align: center;
                padding-top: 30px; 
                padding-bottom: 30px;
                        
                }
            nav{
                background-color: aquamarine;
                text-align: center;
            }
            nav a{
                text-decoration: none;
                }

            /*ESTILOS DEL ARTICLE  */
            article{
                background-color: rgb(45, 134, 218);
            }

            /* ESTILOS DEL ASIDE */
            aside{
                background-color: rgb(250, 15, 199);
            }

            /* ESTILOS DEL FOOTER */
            footer{
                background-color: yellow;
                letter-spacing: .5em;
            }

            /* CLASE PARA SOMBRA DE TEXTO */
            .sombra{
                text-shadow: 3px 3px 2px rgb(212, 111, 98);
            }

            /* ESTILOS PARA LOS BOTONES DEL MENU */
            #enl1{
                border: 1px solid rgb(245, 9, 9);
                background-color: blueviolet;
                color: #fff;
            }
            #enl2{
                border: 1px solid rgb(245, 9, 9);
                background-color: rgb(34, 4, 63);
                color: #fff;
            }
            #enl3{
                border: 1px solid rgb(245, 9, 9);
                background-color: rgb(218, 188, 247);
                color: #fff;
            }
            #enl4{
                border: 1px solid rgb(245, 9, 9);
                background-color: rgb(60, 41, 78);
                color: #fff;
            }

            /* ESTILOS PARA LOS CONTENEDORES */
            .espacio{
                padding: 50px 0 50px 0;
                text-align: center;
                border: 1px solid black;
            }

            /* ESTILOS PARA LOS SUBTIRULOS */
            .subtitulos{
                color: red;
                font-size: 30px;
                font-weight: bold;
                letter-spacing: .5em;
            }
