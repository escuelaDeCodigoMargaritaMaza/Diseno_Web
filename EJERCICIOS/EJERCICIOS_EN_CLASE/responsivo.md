
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="cs/estilos.css">
        <style>
            header{
                width: 90%;
                margin: auto;
                height: 30vh;
                background-color: rgba(94, 99, 97);
                display: flex;
                align-items: center;
                justify-content: center;
            }
            h1{
                color:rgb(94, 99, 97);
                -webkit-text-stroke: 2px black;
                font-size: 3em;
                letter-spacing: 10px;
                text-shadow: 0 0 5px rgb(233, 233, 17);
            }
            main{
                height: 70vh;
                display: flex;
                align-items: center;
                justify-content: space-around;
            }
            div{
                background-color:rgb(187, 196, 192) ;
                border-radius: 20px;
                width: 30%;
                height: 25vh;
                text-align: center;
                transition: height 1s;
            }
            div:hover{
                height: 20em;
            }
            img{
                width: 100%;
                margin-top: -80px;
            }
            footer .img1{
                display: block;
                width: 20% ;
            }
            footer .img2{
                display: none;
                width: 20% ;
            }



    @media(max-width:767px){
        body{
            background: url(https://th.bing.com/th/id/OIP.GEz7mDMUHD7i_rRNCLpDxwHaE8?pid=ImgDet&rs=1);
            background-position: center;
            background-size: cover;
            background-repeat: no-repeat;
        }
        header{
            width: 100%;
            height: 20vh;
            background-color: rgba(168, 252, 218, 0.521);
            display: flex;
            align-items: center;
            justify-content: center;
            }
        h1{
            color:rgb(168, 252, 218);
            -webkit-text-stroke: 1px black;
            font-size: 2em;
            letter-spacing: 10px;
            text-shadow: 0 0 5px rgb(233, 233, 17);
        }
        main{
            flex-direction: column;
            height: 150vh;

        }
        div{
            background-color:rgba(168, 252, 218, 0.473) ;
            border-radius: 10px;
            width: 80%;
            height: 10vh;
            text-align: center;
            margin-bottom: 50px;
            }
        img{
            width: 50%;
            margin-top: -80px;
        }
        div:hover{
            height: 10em;
        }
        footer .img1{
            display: none;
        }
        footer .img2{
            display: block;
        }

    }
        </style>
    </head>
    <body>
       <header>
            <h1>MODELO RESPONSIVE</h1> 
       </header>
       <main>
            <div>
                <img src="1.png" alt="">
                <h2>1024PX EN ADELANTE</h2>

            </div>
            <div>
                 <img src="1.png" alt="">
                <h2>1023 a 768 </h2>

            </div>
            <div>
                 <img src="1.png" alt="">
                <h2>767 a 320</h2>

            </div>

       </main>
       <footer>
        <img class="img1" src="https://th.bing.com/th/id/R.85555fae64d710fdbbc40e5df8919c74?rik=CztEdvaNM%2fBrHA&riu=http%3a%2f%2fcdn5.dibujos.net%2fdibujos%2fpintados%2f201815%2fcomputadora-la-casa-la-habitacion-11333357.jpg&ehk=eQfiOplakv8rx4GFHAvIKqKJ4Vq%2f1cC30r4xlZrozMg%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1" alt="">
        <img class="img2" src="https://th.bing.com/th/id/R.414cd3ec8a2e163a08220165680c2620?rik=SdPeHxIb1tPCBw&pid=ImgRaw&r=0" alt="">
       </footer>
    </body>
    </html>
