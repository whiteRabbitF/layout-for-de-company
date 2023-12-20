<template>
    <header class="header">
      <div class="logo-main">
        <img src="/assets/logo-main.png" alt="Логотип">
      </div>
      <nav class="main-nav" :class="{ 'open': isMenuOpen }">
        <a href="#">Главная</a>
        <a href="#">О нас</a>
        <a href="#">Наши услуги</a>
        <a href="#">Этапы работы</a>
        <a href="#">Стоимость</a>
        <div class="dropdown">
          <a href="#">Еще</a>
          <div class="dropdown-content">
            <a href="#">Дополнительная услуга 1</a>
            <a href="#">Дополнительная услуга 2</a>
          </div>
        </div>
      </nav>
      <div class="contact-info">
        <div class="phone">
          <span style="color: #3980FF;">8 (499) 348-82-16</span>
        </div>
        <div class="email">
          <a href="mailto:hello@softerio.ru">hello@softerio.ru</a>
        </div>
      </div>
      <div class="messengers">
        <a href="#" class="whatsapp"><img src="/assets/logo-wa.png" alt="WhatsApp"></a>
        <a href="#" class="telegram"><img src="/assets/logo-tg.png" alt="Telegram"></a>
      </div>
      <div class="burger-menu" @click="toggleMenu">
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
      </div>
    </header>

    <main class="main">
        <div class="service-list">
        <h1>Разработка мобильных приложений и сервисов</h1>
        </div>
        <div class="items">
            <img src="/assets/rocket.png" alt="">
            <p>Знаем, как решить вашу задачу оптимальным способом</p>
        </div>
        <div class="items">
            <img src="/assets/goblet.png" alt="">
            <p>Подберем подходящее решение с учетом целей и возможностей</p>
        </div>
        <div class="buttons">
            <button class="order">Заказать приложение</button>
            <button class="consulting">Онлай-консультация</button>
        </div>

      <div class="instalation">
            <!-- <div class="triangle">
        <img src="/assets/triangle.png" alt="">
            </div> -->
        <div class="device-logo">
            <img src="/assets/device-logo.png" alt="">
        </div>
        <div class="sphere-1">
            <img src="/assets/sphere-1.png" alt="">
        </div>
        <div class="sphere-2">
            <img src="/assets/sphere-2.png" alt="">
        </div>
        <div class="sphere-3">
            <img src="/assets/sphere-3.png" alt="">
        </div>
    </div>

    </main>

    <main class="service">
      <div class="headers">
        <h1>Наши услуги</h1>
        <h2>Разработка мобильных приложений и веб-проектов для бизнеса и стартапов</h2>
      </div>
    <div class="blocks">
      <div class="block">
        <img src="/assets/phone-icon.png" alt="">
        <h1>Разработка мобильных приложений</h1>
        <div class="block-btns">
          <button>iOS</button>
          <button>Android</button>
        </div>
      </div>

      <div class="block-2">
        <div class="head">
        <img src="/assets/web-dev-icon.png" alt="">
        <h1>Web разработка</h1>
      </div>
      <h3 class="text">Разрабатываем сайты персонально под ваш бизнес. Анализируем рынок и целевую аудиторию в соответствии с задачами, которые вы хотите решить с помощью веб-сайта.
        <br>
        <br>
        Создаём web-сервисы для любого направления бизнеса: продажи, коммуникации, управление, серверную часть и API, гибкие административные инструменты для управления приложениями и сбора статистики.
        <br>
        <br>
        Вы получаете продукт, привлекательный для пользователей и функциональный для вас.</h3>
        <div class="block-btns">
          <button>Frontend</button>
          <button>Backend</button>
        </div>
      </div>

      <div class="block">
        <img class="pic" src="/assets/app-logo.png" alt="">
        <h1>Проектирование мобильного приложения</h1>
        <div class="block-btns">
          <button>Дизайн</button>
          <button>ТЗ</button>
        </div>
      </div>
    </div>
    </main>

    <main class="main-2">
      <h1 class="head-of-stages">Этапы разработки</h1>
      <div class="stages">



      <div class="stage">
        <img src="/assets/stages/stage-1.png" alt="">
        <div class="title">
          <h2 class="ordinal">1</h2>
        <h2> Сбор требований</h2>
        </div>
          <h4 class="desc-of-stage">Детальное изучение требований, ресурсов и исходной информации по проекту и формирование технического задания на разработку ПО.</h4>
      </div>

      <div class="stage">
        <img src="/assets/stages/stage-2.png" alt="">
        <div class="title">
          <h2 class="ordinal">2</h2>
        <h2>UI/UX Дизайн</h2>
        </div>
          <h4 class="desc-of-stage">Разработка современного функционального и удобного дизайна с применением новейших инструментов.</h4>
      </div>

      <div class="stage">
        <img src="/assets/stages/stage-3.png" alt="">
        <div class="title">
          <h2 class="ordinal">3</h2>
        <h2>Прототип (MVP)</h2>
        </div>
          <h4 class="desc-of-stage">В результате проектирования формируется прототип и отправляется для разработки продукта</h4>
      </div>

      <div class="stage">
        <img src="/assets/stages/stage-4.png" alt="">
        <div class="title">
          <h2 class="ordinal">4</h2>
        <h2> Разработка</h2>
        </div>
          <h4 class="desc-of-stage">Процесс разработки системы интеллектуального учета, мобильного приложения или веб-сайта в режиме максимальной прозрачности.</h4>
      </div>

      <div class="stage">
        <img src="/assets/stages/stage-5.png" alt="">
        <div class="title">
          <h2 class="ordinal">5</h2>
        <h2>Тестирование</h2>
        </div>
          <h4 class="desc-of-stage">В ходе тестовых запусков обеспечиваем полную отказоустойчивость продукта.</h4>
      </div>

      <div class="stage">
        <img src="/assets/stages/stage-6.png" alt="">
        <div class="title">
          <h2 class="ordinal">6</h2>
        <h2> Развертывание</h2>
        </div>
          <h4 class="desc-of-stage">Запуск готового продукта в работу (ИСУ, сайта, приложения).</h4>
      </div>
      <div class="stage">
        <img src="/assets/stages/stage-7.png" alt="">
        <div class="title">
          <h2 class="ordinal">6</h2>
        <h2>Поддержка и обслуживание</h2>
        </div>
          <h4 class="desc-of-stage">Обеспечиваем полную техническую поддержку и сопровождение по всем вопросам, возникающим после развертывания.</h4>
      </div>

      <div class="request">
        <button>Оставить заявку</button>
      </div>

    </div>
    <div class="details">
      <img class="pic-1" src="/assets/details/little-rocket.png" alt="">
      <img class="pic-2" src="/assets/details/settings-icon.png" alt="">
      <img class="pic-3" src="/assets/details/tag-figure.png" alt="">
      <img class="pic-4" src="/assets/details/white-ball-icon.png" alt="">
    </div>
    </main>

    <main class="cost">

      <div class="cost-info">
        <h1>Стоимость разработки мобильных приложений</h1>
        <h3>Мы собрали стандартные элементы приложений в пакеты, для примерного понимания стоимости разработки. Чтобы заказать мобильное приложение свяжитесь с нами, мы вас проконсультируем, проведем аудит ценовых предложений других студий. Ниже цены на типовые приложения.</h3>
      </div>
      
      <div class="price-blocks">

      <div class="price-block">
        <div class="price-title">
          <div class="flag"><img src="/assets/blue-flag.png" alt=""></div>
          <img src="/assets/price-types/base-rate.png" alt="">
          <h2>Типовой</h2>
        </div>
        <div class="price-items">
          <h3>Каталог товаров или услуг</h3>
          <img src="/assets/checkmark.png" alt="">
          <h3>Сделать заказ</h3>
          <img src="/assets/checkmark.png" alt="">
          <h3>Новости и акции</h3>
          <img src="/assets/checkmark.png" alt="">
          <h3>Обратная связь</h3>
          <img src="/assets/checkmark.png" alt="">
          <h4>Контакты</h4>
          <img src="/assets/checkmark.png" alt="">
        </div>
          <p class="price">1 000 000 руб.</p>
        <button class="to-order">Заказать приложение</button>
        </div>


        <div class="price-block">
        <div class="price-title">
          <div class="flag"><img src="/assets/blue-flag.png" alt=""></div>
          <img src="/assets/price-types/buisness-rate.png" alt="">
          <h2>Бизнес</h2>
        </div>
        <div class="price-items">
          <h3>Программа лояльности</h3>
          <img src="/assets/checkmark.png" alt="">
          <h3>Push уведомления</h3>
          <img src="/assets/checkmark.png" alt="">
          <h3>Серверная часть </h3>
          <img src="/assets/checkmark.png" alt="">
          <h4>Панель управления </h4>
          <img src="/assets/checkmark.png" alt="">
          <h4>Чаты </h4>
          <img src="/assets/checkmark.png" alt="">
        </div>
          <p class="price">2 000 000 руб.</p>
        <button class="to-order">Заказать приложение</button>
        </div>

        
        <div class="price-block">
        <div class="price-title">
          <div class="flag"><img src="/assets/red-flag.png" alt=""></div>
          <img src="/assets/price-types/custom-rate.png" alt="">
          <h2>Кастом</h2>
        </div>
        <div class="price-items">
          <h3>Автоматизация бизнес-процессов</h3>
          <img src="/assets/checkmark-red.png" alt="">
          <h3>Сложные интеграции</h3>
          <img src="/assets/checkmark-red.png" alt="">
          <h3>Маркетплейс</h3>
          <img src="/assets/checkmark-red.png" alt="">
          <h3>Корпоративные решения</h3>
          <img src="/assets/checkmark-red.png" alt="">
          <h4>Smart TV, Kit, VR \ AR</h4>
          <img src="/assets/checkmark-red.png" alt="">
        </div>
          <p class="price">3 000 000 руб.</p>
        <button class="to-order">Заказать приложение</button>
        </div>
    </div>
    </main>

    <h1 class="deploy-title">Какие задачи поможет решить запуск мобильного приложения</h1>
    <main class="deploy">
      <div class="deploy-blocks">
      <div class="deploy-block-left">
        <div class="deploy-heading">
          <h2 class="ordinal">1</h2>
        <h1>Повысить лояльность</h1>
      </div>
        <h3>Мобильное приложение работает намного быстрее сайта и может выполнять многие функции даже без интернета. Также здесь не нужно каждый раз авторизовываться, чтобы оформить заказ или отследить его статус. Все это создает положительный пользовательский опыт</h3>
      </div>

      <div class="deploy-block-left">
        <div class="deploy-heading">
          <h2 class="ordinal">2</h2>
        <h1>Автоматизировать продажи</h1>
      </div>
        <h3>С приложением легче провести пользователя по каждому этапу воронки продаж. С помощью автоматизации внутри интерфейса можно показывать ценность продукта, рассказывать о новых функциях, делать допродажи и напоминать о себе с помощью пуш-уведомлений.</h3>
      </div>
    </div>
      <div class="deploy-img"><img src="/assets/iphone-pic.png" alt=""></div>

      <div class="deploy-blocks">
      <div class="deploy-block-right">
        <div class="deploy-heading">
          <h2 class="ordinal">3</h2>
        <h1>Сократить издержки</h1>
      </div>
        <h3>Мобильный сервис помогает сэкономить на рекламном бюджете и дополнительных сотрудниках. Например, многие маркетинговые акции можно проводить в самом приложении и адаптировать рекламу под целевых пользователей, а часть работы службы поддержки делегировать автоматическим чат-ботам.</h3>
      </div>

      <div class="deploy-block-right">
        <div class="deploy-heading">
          <h2 class="ordinal">4</h2>
        <h1>Увеличить прибыль</h1>
      </div>
        <h3>Повышение уровня клиентского сервиса, экономия на закупке рекламы на других площадках и автоматизации процессов положительно скажется и на итоговой выручке. Вложения в разработку приложения быстро окупятся, если интерфейс хорошо справляется со своими задачами.</h3>
      </div>
      <div class="deploy-pics">
        <img class="pic1" src="/assets/spheres/sphere-1.png" alt="">
        <img class="pic2" src="/assets/spheres/sphere-2.png" alt="">
        <img class="pic3" src="/assets/spheres/sphere-3.png" alt="">
        <img class="pic4" src="/assets/spheres/sphere-4.png" alt="">
      </div>
    </div>
    </main>

    <h1 class="app-title">Заказать приложение</h1>

    <main class="app-order">

    <div class="budget">
      <h2>Бюджет проекта:</h2>
      <div class="buttons-order">
      <button>20 000 — 50 000 руб.</button>
      <button>50 000 — 100 000 руб.</button>
      <button>100 000 — 500 000 руб.</button>
      <button>500 000 — 1000 000 руб.</button>
      <button>1 000 000 руб. — 2 000 000 руб.</button>
      <button>2 000 000 руб. — 3 000 000 руб.</button>
    </div>
    </div>

    <div class="contacts">
      <h2>Контакты:</h2>

      <div class="inputs">
      <input type="text" placeholder="Александр">
      <label for="name"></label>
      <input type="text" placeholder="телефон">
      <label for="phone"></label>
    </div>

    <div class="textarea">
      <input type="textarea" placeholder="комментарий">
      <label for="comment"></label>
    </div>

      <button class="back-call">заказать обратный звонок</button>

    </div>
  </main>

  <footer class="footer">
    <div class="logo-main">
        <img src="/assets/logo-main.png" alt="Логотип">
      </div>
      <nav class="main-nav" :class="{ 'open': isMenuOpen }">
        <a href="#">Главная</a>
        <a href="#">О нас</a>
        <a href="#">Наши услуги</a>
        <a href="#">Этапы работы</a>
        <a href="#">Стоимость</a>
        <div class="dropdown">
          <a href="#">Еще</a>
          <div class="dropdown-content">
            <a href="#">Дополнительная услуга 1</a>
            <a href="#">Дополнительная услуга 2</a>
          </div>
        </div>
      </nav>
      <div class="contact-info">
        <div class="phone">
          <span style="color: #3980FF;">8 (499) 348-82-16</span>
        </div>
        <div class="email">
          <a href="mailto:hello@softerio.ru">hello@softerio.ru</a>
        </div>
      </div>
      <div class="messengers">
        <a href="#" class="whatsapp"><img src="/assets/logo-wa.png" alt="WhatsApp"></a>
        <a href="#" class="telegram"><img src="/assets/logo-tg.png" alt="Telegram"></a>
      </div>
      <div class="burger-menu" @click="toggleMenu">
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
      </div>
    </footer>
  </template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }
};
</script>
