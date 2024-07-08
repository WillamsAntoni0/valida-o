<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
#btn{
      position: absolute;
      left: 38%;
      top:80%;
      padding: 11px;
      border-radius: 5px;
      border: none;
      width:70%;
      position: relative;
      left: 16%;
      background: green;
      cursor: pointer;
      color:white;
      padding: 10px;
      user-select:none;
}

#btn:hover{
        background: rgb(71, 231, 71);
}

h1{
    color:green;
    user-select: none;
}

input{
      outline-color:green;
      padding: 7px;
      border-radius:6px ;
      border: none;
      
}

div{
      padding: 40px;
     background-color: black;
     position: absolute;
     top:50%;
     left:50%;
    transform: translate(-50%,-50%);
    border-radius:6px ;
    }

    body{
         font-family: Arial, Helvetica, sans-serif;
         background-color: #201d1dce;
    }

</style>
</head>
<body>
     <div>
      <form>
        <h1>Login</h1>
        <input placeholder="Email" type="email" required>
         <br><br><br>
       <input placeholder="úsuario" type="text" required>
        <br><br><br>
        <input placeholder="servidor" type="text" required>
        <br><br><br>
        <button id="btn">Válidar</button>
      </form>
    </div>
</body>
</html>
