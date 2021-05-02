<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css">
    <link rel="stylesheet" href=" https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Login</title>
</head>

<body>
    <!--alt + shift + f = identar-->

    <div class="container">

        <div class="box1">
            <p>Bem vindo de volta!</p>
            <h4>Caso você ja tenha feito registro </br>é só logar abaixo</h4>
            <Button class="btn1" onclick="calcular()">Logar</Button>
        </div>
        <div class="box2">
            <p>Criar sua conta</p>
            <div class="redes">

                <div class="social-container">
                    <a href="#" class="social"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="social"><i class="fab fa-google"></i></a>
                    <a href="#" class="social"><i class="fab fa-linkedin-in"></i></a>
                </div>
                <h4>Ou use seu Email para registro</h4>
            </div>
            <form class="form">
                <input type="text" placeholder='Name'>

                <input type="email" neme = "email" class="campo" maxlength="40" required autofocus placeholder='Email'>
                <input type="password" name="password" class="campo" placeholder='Password'>
                <button class="btn2">Sign Up</button>

            </form>
        </div>
    </div>

    </div>
</body>

</html>