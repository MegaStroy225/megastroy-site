
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>МегаСтрой Маркет</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(to right, #f1f2f6, #ffffff);
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #002b45, #005a87);
      padding: 40px 20px;
      text-align: center;
      color: white;
      position: relative;
      overflow: hidden;
    }
    header::after {
      content: "";
      position: absolute;
      width: 400px;
      height: 400px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 50%;
      top: -100px;
      left: -100px;
    }
    header img {
      width: 120px;
      margin-bottom: 15px;
      z-index: 1;
      position: relative;
    }
    h1 {
      font-size: 2.5rem;
      margin: 0;
      z-index: 1;
      position: relative;
    }
    p.slogan {
      font-size: 1.3rem;
      color: #fdd835;
      z-index: 1;
      position: relative;
    }
    section {
      padding: 50px 20px;
      text-align: center;
    }
    .highlight {
      font-size: 1.8rem;
      font-weight: 700;
      color: #005a87;
    }
    .card {
      background: white;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
      max-width: 600px;
      margin: 20px auto;
      padding: 30px;
    }
    .contacts a {
      display: inline-block;
      margin: 10px 15px;
      padding: 12px 25px;
      border-radius: 30px;
      background: #005a87;
      color: white;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }
    .contacts a:hover {
      background: #007ab8;
    }
    footer {
      background: #002b45;
      color: #ccc;
      text-align: center;
      padding: 20px 10px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="МегаСтрой Маркет" />
    <h1>МегаСтрой Маркет</h1>
    <p class="slogan">Строй вместе с МегаСтрой!</p>
  </header>

  <section>
    <div class="card">
      <p class="highlight">Мы — ваш надёжный партнёр в мире строительства</p>
      <p>Найдите всё для ремонта, стройки и уюта в одном месте. Быстро, выгодно, удобно.</p>
    </div>
  </section>

  <section>
    <div class="card contacts">
      <h2>Свяжитесь с нами</h2>
      <a href="tel:+77001402525">📞 Позвонить</a>
      <a href="https://wa.me/77001402525" target="_blank">💬 WhatsApp</a>
      <a href="https://2gis.kz/almaty/geo/70000001090143028" target="_blank">📍 Адрес в 2ГИС</a>
    </div>
  </section>

  <footer>
    &copy; 2025 МегаСтрой Маркет | Все права защищены
  </footer>
</body>
</html>
