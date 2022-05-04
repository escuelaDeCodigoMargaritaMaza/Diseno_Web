# Clona la siguiente página

![image](https://user-images.githubusercontent.com/91554777/165874800-e4757824-1207-4357-9426-c956fe3abc55.png)


    <!DOCTYPE html>
    <html lang="en">
    <head>
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&family=Tapestry&display=swap" rel="stylesheet">
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <style>
        /* SELECTOR UNIVERSAL */
        *{
          margin: 0;
          padding: 0;
          font-family: 'Tapestry', cursive;

        }
        body {
          background: url("https://th.bing.com/th/id/R.7049f96a7ab04d4ffe56f6b7a180dd31?rik=KXuBl64z1lEW%2fw&riu=http%3a%2f%2fwww.solofondos.com%2fwp-content%2fuploads%2f2015%2f11%2fFondos-para-paginas-web-profesionales-3D.jpg&ehk=lWv3MXhrf5twGIElvqeFkf1879q3Y4fb8nZFCm8U5hQ%3d&risl=&pid=ImgRaw&r=0");
          background-repeat: no-repeat;
          background-position: center;
          background-size: cover;
        }
        /* MENU Y LOG */
        header{
          color: #fff;
          height: 100vh;
        }
        #logo{
          font-size: 40px;
          color: blue;
          text-shadow: -3px -3px 6px red;
        }
        .barra{
          display: flex;
          justify-content: space-between;
          margin: 20px 20px;
        }
        nav ul{
          display: flex;
          align-items: flex-end;
          list-style-type: none;
        }
        nav li{
          margin-right: 20px;
          background: linear-gradient(rgba(235, 114, 114,.6),rgba(122, 122, 230,.6));
          border-radius: 50px;
          color: #fff;
          padding: 10px;
        }
        /* CONTENEDOR */
        .contenedor{
          height: 90%;
          width: 50%;
          display: flex;
          align-items: end;
          padding-left: 30px;
          padding-bottom: 30px;
        }

        /* CONTENEDOR MAS PEQUEÑO */
        .contenedor2{

          background: linear-gradient(rgba(235, 114, 114,.6),rgba(122, 122, 230,.6));
          border-radius: 50px;
          padding: 30px;
        }
        /* IMAGEN FLOAT */
        .contenedor2 img {
        float: right;
        }

        /* TEXTO FLOAT */
        .contenedor2 
          p{
            text-shadow: 0px 0px 4px  black;
          }


        </style>
      <title>Document</title>
    </head>
    <body>
      <header>
        <div class="barra">
            <p id="logo">LOGO</p>
            <nav>
              <ul>
                <li>MENU1</li>
                <li>MENU2</li>
                <li>MENU3</li>
              </ul>
            </nav>
         </div>
         <div class="contenedor">
            <div class="contenedor2">
              <h1>LANDING PAGE</h1>
              <p><img src="https://th.bing.com/th/id/R.d9fc4731a5ac9affe2511d0bdc3d3210?rik=%2fLtHkxv%2f%2fBsFuQ&pid=ImgRaw&r=0" alt="ADIP" style="width:70px;height:70px;margin-left:15px;">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia officiis repellat ab esse iste explicabo reprehenderit illo officia ullam nam autem, modi facere nobis, tempore labore ipsam laboriosam quod delectus itaque numquam? Vero fuga consectetur cum quaerat libero ad molestias. Dolores amet praesentium nisi nemo at non quidem et ab in! Sit repudiandae dolore expedita eos quod nemo libero voluptatem recusandae fugiat, molestias ipsum ad minima ratione inventore nostrum aliquid, ipsam reprehenderit voluptas magnam omnis error fugit deleniti! Blanditiis repellat explicabo, nemo tenetur ad ducimus saepe voluptate fuga rerum magnam ipsam ut odio amet voluptatibus architecto illum! Voluptatibus maxime fuga ad cupiditate porro incidunt dolores? Cum culpa illum qui labore sint quia molestiae id sunt veniam natus corrupti consequuntur quaerat laudantium,   </p>
            </div>
         </div>
      </header>



    </body>
    </html>
