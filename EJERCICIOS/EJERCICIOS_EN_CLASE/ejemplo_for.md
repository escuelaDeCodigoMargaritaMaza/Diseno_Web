<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>FORMMULARIOS</h2>

    <form action="https://formspree.io/f/mnqwwjon"  method="POST">
        <fieldset>
          <legend>Información del usuario:</legend>
          Introducir nombre<br>
          <input type="text" id="name" name="name"><br>
          Introducir contraseña<br>
          <input type="Password" id="pass" name="pass"><br>
          <label for="lang">Language</label>
          <select name="languages" id="lang">
            <option value="javascript">JavaScript</option>
            <option value="php">PHP</option>
            <option value="java">Java</option>
            <option value="golang">Golang</option>
            <option value="python">Python</option>
            <option value="c#">C#</option>
            <option value="C++">C++</option>
            <option value="erlang">Erlang</option>
          </select><br><br>
          <input type="submit" value="Submit">
        </fieldset>
      </form> 

</body>
</html>
