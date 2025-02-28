<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Простой Лендинг</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        section {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            border-bottom: 2px solid #ddd;
        }
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: white;
            padding: 10px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#section1">Раздел 1</a>
        <a href="#section2">Раздел 2</a>
        <a href="#section3">Раздел 3</a>
        <a href="#section4">Раздел 4</a>
    </nav>

    <section id="section1">
        <h1>Раздел 1</h1>
    </section>
    <section id="section2">
        <h1>Раздел 2</h1>
    </section>
    <section id="section3">
        <h1>Раздел 3</h1>
    </section>
    <section id="section4">
        <h1>Раздел 4</h1>
    </section>
</body>
</html>
