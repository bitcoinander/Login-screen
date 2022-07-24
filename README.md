# Login-screen

# HTML 

```html 
<!DOCTYPE html>
<html lang="pt">

<head>
    <meta charset="utf-8">
    <title>Tela de Login</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="login">
        <h1>Login</h1>
        <div class="text1">
            <i class="i"></i>
            <input type="text" placeholder="Usuário">
        </div>

        <div class="text1">
            <input type="password" placeholder="Senha">
        </div>

        <div class-="cont">
            <button class="bnt">
                Entrar
            </button>
        </div>
    </div>
    <video autoplay muted loop>
        <source src="background.mp4" />
    </video>
</body>

</html>

```

# CSS 

```css
body {
    font-family: Arial;
    display: flex;
}

video {
    position: fixed;
    z-index: -1;
    right: 0;
    bottom: 0;
    width: 1360px;
}

body .bnt,
body {
    border: none;
    width: 250px;
    height: 50px;
    font-size: 20px;
    font-weight: 900;
    text-align: center;
    line-height: 15px;
    color: #433280;
    border-radius: 20px;
}

body .bnt {
    margin-top: 60px;
}

.login {
    width: 280px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.login h1 {
    padding: 50px 0;
    border-bottom: 15px solid white;
    margin-bottom: 15px;
    float: center;
    font-size: 70px;
    color: white;
}

.text1 {
    width: 100%;
    overflow: hidden;
    font-size: 20px;
    padding: 10px 0;
    margin: 10px 0;
    border-bottom: 2px solid white;
}

.text1 input {
    color: white;
    font-size: 20px;
    width: 80%;
    margin: 0 10px;
    border: none;
    outline: none;
    background: none;
}
```
