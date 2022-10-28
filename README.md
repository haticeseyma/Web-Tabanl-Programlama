# Web-Tabanl-Programlama
/*index.html*/
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basit Web Sitesi-1</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="#">LOGO</a>
            </div>
            <ul>
                <li><a href="#" class="active">Ana Sayfa</a></li>
                <li><a href="#">Hakkımızda</a></li>
                <li><a href="#">Hizmetler</a></li>
                <li><a href="#">Ürünler</a></li>
                <li><a href="#">İletişim</a></li>

            </ul>
        </div>
        <div class="center">
            <h1>Basit Web Sitesine</h1>
            <h2>Hoşgeldiniz </h2>
            <div class="buttons">
                <button>Daha Fazla...</button>
                <button>Abone Ol</button>
            </div>
        </div>
    </div>
</body>

</html>

/*style.css*/
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&disp
* {
}

.container {
    background: url(doğa-mazara-4.jpg);
    height: 100vh;
    background-size: 100% 100%;
}

.container .navbar {
    width: 100%;
    height: 80px;
    background: rgb(113, 100, 100, 0.4);
}

.navbar .logo {
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
}

.navbar .logo a {
    text-decoration: none;
    font-size: 30px;
    font-family: sans-serif;
    color: azure;
}

.navbar ul {
    float: right;
    margin-right: 20px;
}

.navbar ul li {
    list-style: none;
    display: inline-block;
    margin: 0 8px;
    line-height: 80px;
}

.navbar ul li a {
    color: azure;
    text-decoration: none;
    font-size: 20px;
    padding: 6px 13px;
    font-family: Roboto;
    transition: .5s;
}

.navbar ul li a.active,
.navbar ul li a:hover {
    background: blueviolet;
    border-radius: 2px;
}

.container .center {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: sans-serif;
    user-select: none;
}

.center h1 {
    color: #0c0b0c;
    font-size: 40px;
    font-weight: bold;
    width: 800px;
    text-align: center;
}

.center h2 {
    color: rgb(21, 22, 22);
    font-size: 40px;
    font-weight: bold;
    width: 785px;
    margin-top: 10px;
    text-align: center;
}

.center .buttons {
    margin: 35px 320px;
}

.buttons button {
    height: 55px;
    width: 150px;
    font-size: 15px;
    font-weight: bold;
    color: rgb(8, 7, 8);
    background: rgb(215, 210, 219);
    border: solid 1px rgb(201, 190, 191);
    cursor: pointer;
    outline: none;
    border-radius: 25px;
    transition: .5s;
}

.buttons button:hover {
    background: rgb(121, 81, 81);
}
