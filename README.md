# cv
Сайт-визитка на HTML 
index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="./normalize.css" rel="stylesheet" />
    <link href="./style.css" rel="stylesheet" />
    <title>Document</title>
  </head>
  <body>
    <header class="header">
      <img src="./avatar.jpg" width="300" height="300" alt="avatar" class="header__avatar" />
      <h1 class="header__title">Уланбекова Айкокуль</h1>
      <h3 class="header__subtitle">QA Engineer/тестировщик</h3>
    </header>
    <main>
      <section class="links">
        <h2 class="links__header">My contacts</h2>
        <ul class="links__container">
          <li class="links__link">
            <p class="links__title">Telegram</p>
            <a class="linsk__link" href="http://t.me/@aikokul_ulanbekova">@aikokul_ulanbekova</a>
          </li>
          <li class="links__link">
            <p class="links__title">Email</p>
            <a class="linsk__link" href="aikaulanbekova@mail.ru"
              >aikaulanbekova@mail.ru</a
            >
          </li>
          <li class="links__link">
            <p class="links__title">Facebook</p>
            <a class="linsk__link" href="?!"
              >aikokul.ulanbekova</a
            >
          </li>
          <li class="links__link">
            <p class="links__title">LinkedIn</p>
            <a class="linsk__link" href="?!">Aikokul Ulanbekova</a>
          </li>
          <li class="links__link">
            <p class="links__title">GitHub</p>
            <a class="linsk__link" href="https://github.com/AikokulUlan-qa">github.com/AikokulUlan-qa/</a>
          </li>
        </ul>
      </section>
      <section class="links">
        <h2 class="links__header">My project in my free time</h2>
        <ul class="links__container">
          <li class="links__link">
            <p class="links__title">Guide</p>
            <a class="linsk__link" href="https://www.google.com/maps/@55.7475218,37.5092962,13z/data=!4m2!10m1!1e1?entry=ttu/">Restaurants in Moscow/</a>
          </li>
          <li class="links__link">
            <p class="links__title">Make </p>
            <a class="linsk__link" href="https://www.acouplecooks.com/coffee-drinks/">different ways of coffee recipe</a>
          </li>
        </ul>
      </section>
      <section class="links">
        <h2 class="links__header">My work portfolio</h2>
        <ul class="links__container">
          <li class="links__link">
            <p class="links__title">Guide</p>
            <a class="linsk__link" href="https://miro.com/app/board/uXjVNJ5coJw=/">Miro</a>
          </li>
        </ul>
      </section>
      </section>
      <section class="links">
        <h2 class="links__header">My resumes</h2>
        <ul class="links__container">
          <li class="links__link">
            <p class="links__title">Resume</p>
            <a class="linsk__link" href="?!">HH</a>
          </li>
          <li class="links__link">
            <p class="links__title">CV</p>
            <a class="linsk__link" href="?!">JSON</a>
          </li>
        </ul>
      </section>
    </main>
    <footer>
      <button type = "button" class="button-link" href=""> Кредо </button>
    </footer>
    <script type="text/javascript" src="js.js"></script>
  </body>
</html>
