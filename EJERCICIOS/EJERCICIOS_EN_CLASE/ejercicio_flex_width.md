Realiza los siguientes ejercicios

![image](https://user-images.githubusercontent.com/91554777/165660509-162d9595-8341-4f94-8fc7-40e0cc3bfe95.png)


![image](https://user-images.githubusercontent.com/91554777/165660558-75c213fa-8010-4299-acd2-e9016e6c1b35.png)

![image](https://user-images.githubusercontent.com/91554777/165660630-c9e10e15-7d9f-4961-9d88-98cd2b67fe86.png)


solución

        <!DOCTYPE html>
        <html lang="en">
        <head>
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <meta http-equiv="X-UA-Compatible" content="ie=edge">
          <title>align-items</title>
          <style>
            body {
              background-color: aquamarine;
              font-family: sans-serif;
            }
            ul, li {
              padding: 0; 
              list-style: none;
            }
            ul {
              display: flex;
              margin: 10px;
              margin-top: 0;
              background-color: #666;
              justify-content: space-between;
              height: 100px;
            }
            li {
              width: 10%;
              height: 50px;
              background-color: orangered;
              font-size: 1.5em;
              font-weight: bold;
              text-align: center;
              color: #fff;

            }
            h1 {
              margin: 20px 20px 4px 15px;
              font-size: 1.3em;
              color: darkblue;
            }
            .flexstart {
              align-items: flex-start;
            }
            .flexend {
              align-items: flex-end;
            }
            .flexcenter {
              align-items: center;
            }
            .stretch {
              align-items: stretch;
            }
            .center{
                justify-content: center;
            }
            .between{
                justify-content: space-between;
            }
            .around{
                justify-content: space-around;
            }
            .end{
                justify-content:end;
            }
            .start{
                justify-content:start;
            }

            .cuadros{
                display: flex;
                justify-content: space-around;
            }
            .cuadros img{
                width: 100%;
                height: 300px;
            }
            .cuadro1{
                width: 30%;
                background-color: #666;
                border-radius: 10px;
                color: #fff;
                text-align: justify;
                font-weight: bold;
            }
            .cuadros h2{
                text-align: center;
                font-size: 40px;
            }
            .cuadros p{
                margin: 0 20px;
            }

          </style>
        </head>
        <body>
            <h1>align-items</h1>
          <div>
            <h1>flex-start</h1>
            <ul class="flexstart">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>flex-end</h1>
            <ul class="flexend">
              <li>1</li>
              <li>2</li>
              <li >3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>center</h1>
            <ul class="flexcenter">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>justify-content</h1>
            <h1>center</h1>
            <ul class="center">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>space-between</h1>>
            <ul class="between">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>space-around</h1>>
            <ul class="around">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>end</h1>>
            <ul class="end">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>
          <div>
            <h1>start</h1>>
            <ul class="start">
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
            </ul>
          </div>

          <div class="cuadros">
              <div class="cuadro1">
                  <h2>HTML</h2>
                  <img src="https://th.bing.com/th/id/OIP.9I54Zms0h1-EH9X3XpXRYAHaEh?pid=ImgDet&rs=1" alt="html">
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab incidunt fugiat maxime molestiae reiciendis sint. Inventore unde recusandae reiciendis quasi atque eum quia, asperiores quaerat pariatur placeat ut distinctio tempore eligendi iste nihil optio velit similique nemo illum possimus esse consequuntur nam architecto vitae? Sit quaerat placeat iste aspernatur nisi.</p>
              </div>
              <div class="cuadro1">
                <h2>CSS</h2>
                <img src="https://th.bing.com/th/id/OIP.37tqsVNN5gIUNN2VZqo0QAHaEe?pid=ImgDet&rs=1" alt="css">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab incidunt fugiat maxime molestiae reiciendis sint. Inventore unde recusandae reiciendis quasi atque eum quia, asperiores quaerat pariatur placeat ut distinctio tempore eligendi iste nihil optio velit similique nemo illum possimus esse consequuntur nam architecto vitae? Sit quaerat placeat iste aspernatur nisi.</p>
            </div>
            <div class="cuadro1">
                <h2>JS</h2>
                <img src="https://th.bing.com/th/id/R.e80bdf5bb4520e5544870337faf3fdf4?rik=geSBdKO7ZtsS%2bw&pid=ImgRaw&r=0" alt="js">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab incidunt fugiat maxime molestiae reiciendis sint. Inventore unde recusandae reiciendis quasi atque eum quia, asperiores quaerat pariatur placeat ut distinctio tempore eligendi iste nihil optio velit similique nemo illum possimus esse consequuntur nam architecto vitae? Sit quaerat placeat iste aspernatur nisi.</p>
            </div>
          </div>

        </body>
        </html>
