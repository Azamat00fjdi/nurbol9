<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8">
  <title>Қорқыт ата</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, black, darkred); /* Қара-қызыл фон */
      color: #000;
    }

    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .box {
      display: flex;
      align-items: center;
      background: rgba(255, 255, 255, 0.95); /* Аздап мөлдір ақ фон */
      border: 4px solid gold;
      border-radius: 10px;
      padding: 25px;
      gap: 30px;
      box-shadow: 0 0 20px rgba(0,0,0,0.4);
    }

    img {
      width: 280px;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0 0 10px rgba(0,0,0,0.4);
    }

    .text {
      max-width: 450px;
    }

    h1 {
      color: darkred;
      margin-top: 0;
    }

    p {
      font-size: 18px;
      line-height: 1.5;
      color: #222;
    }

    a {
      display: inline-block;
      margin-top: 10px;
      background: darkred;
      color: white;
      text-decoration: none;
      padding: 8px 16px;
      border-radius: 6px;
      font-size: 16px;
    }

    a:hover {
      background: red;
    }

    .author {
      position: fixed;
      bottom: 10px;
      right: 15px;
      font-size: 14px;
      color: white;
      background: rgba(0, 0, 0, 0.6);
      padding: 4px 8px;
      border-radius: 6px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="box">
      <img src="https://assembly.kz/upload/iblock/8a6/8a6439fea48cbae8e17e848729a4c8cc.jpg"
           alt="Қорқыт ата суреті"
           onclick="window.open('https://kk.wikipedia.org/wiki/%D2%9A%D0%BE%D1%80%D2%9B%D1%8B%D1%82_%D0%B0%D1%82%D0%B0', '_blank')">

      <div class="text">
        <h1>Қорқыт ата</h1>
        <p>Қорқыт ата — IX ғасырда өмір сүрген ойшыл, жырау және күйші. 
        Ол Сырдария өзенінің бойында, қазіргі Қызылорда облысы аумағында дүниеге келген. 
        Қорқыт ата түркі халықтарының мәдениетінің символы болып саналады.</p>

        <a href="https://kk.wikipedia.org/wiki/%D2%9A%D0%BE%D1%80%D2%9B%D1%8B%D1%82_%D0%B0%D1%82%D0%B0" target="_blank">Википедия оқу</a>
      </div>
    </div>
  </div>

  <div class="author">
    Автор: +7 700 118 2575 osp280807@gmail.com
  </div>
</body>
</html>
