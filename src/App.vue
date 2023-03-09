<script lang="ts" setup>
import HideText from './components/hide-text.vue';
</script>

<template>
  <main class="f fd-col rg-4">
    <section class="main_banner f jc-c p-3 bg-second-100">
      <div class="container f g-4 ai-c">
        <div class="w-100 f jc-c">
          <img
            height="300"
            src="@/assets/images/logo.svg"
            alt="Logo"
          />
        </div>
        <div class="w-100 f fd-col bg-default py-3 px-4 br-3">
          <h2 class="fw-regular" style="font-family: 'Roboto Condensed'">
            <span class="c-brand"> Н2глобус</span> дает ответ вашим экологичным
            запросам самым чистым и выгодным способом
          </h2>
        </div>
      </div>
      <img class="slide-1" src="@/assets/images/alex-nerovnya017-768x926.jpg" />
      <img class="slide-2" src="@/assets/images/headslide2.jpg" />
    </section>

    <section class="f jc-c p-3">
      <div class="container f g-4">
        <div class="w-100">
          <img
            class="w-100 br-3"
            src="@/assets/images/alex-nerovnya017-768x926.jpg"
            alt="Image"
          />
        </div>
        <div class="w-100 f fd-col rg-3">
          <h1
            class="c-brand fw-medium"
            style="font-family: 'Oswald'; font-weight: 600"
          >
            - Миссия -
          </h1>

          <h4 style="font-family: 'Comfortaa'">
            ЕСЛИ ХОЧЕШЬ ИЗМЕНИТЬ МИР, ТО НАЧНИ С СЕБЯ
          </h4>

          <div class="f fd-col rg-2 mission">
            <p>
              Базовой мыслью, источником идеи о создании данного проекта,
              является мысль о будущем планеты, на которой жить нашим детям. У
              нашей команды нет точных данных о том, что нашу Планету губит
              высокий уровень СО2, как и нет их ни у кого на Планете. Но здравый
              смысл подсказывает, что очень важно прекратить использовать
              ископаемое топливо.
            </p>

            <HideText styles="opacity: 0.7">
              <p>
                Ключевым элементом, позволяющим произвести переход от
                ископаемого топлива к полноценному использованию возобновляемых
                видов энергии, является
                <span class="c-brand">Водород</span>.
                <br />
                Основатели проекта, ООО «<a
                  class="c-danger"
                  href="https://cornelius.md/"
                  >Корнелиус</a
                >», семейное предприятие.
              </p>

              <p>
                Мы, пользуясь нашим опытом в сфере газоснабжения, решили начать
                достижение наших глобальных целей со своего скромного хозяйства,
                что даст нам в будущем существенные преимущества:
                <br />
                — шаг за шагом мы начинаем переводить свое хозяйство на уровень
                — «нейтральный к СО2»; <br />
                — мы осваиваем первые в своем регионе новые технологии, которые
                надеемся дадут источник дохода нашим детям еще минимум 100 лет;
                <br />
                — мы производим обновление нашего технопарка на новое
                оборудование, которое имеет в 2 и более раз долгий срок службы,
                как правило основано на технологиях с минимальным количеством
                трущихся частей и с отсутствием необходимости частого
                обслуживания; <br />
                — мы являемся новаторами
              </p>
            </HideText>
          </div>
        </div>
      </div>
    </section>

    <div class="f fd-col rg-3">
      <section class="f ai-c cg-4 px-3">
        <div class="w-100"></div>
        <h1
          class="w-100 c-brand"
          style="font-family: 'Oswald'; font-weight: 600"
        >
          - Продукт -
        </h1>
      </section>
      <section class="f g-4">
        <div class="w-100">
          <img class="w-100" src="@/assets/images/diagram.png" />
        </div>
        <div class="w-100 f fd-col rg-3">
          <div class="bg-brand p-4 h-100 f fd-col jc-c">
            <p class="c-default f fd-col rg-2">
              Станция заправки водородным топливом H2Globus<br />«Подключите
              воду и электричество к Станции H2Глобус. Получите автономный
              источник водорода для экологичного энергоснабжения дома,
              транспорта и любых других нужд. Все это будет длиться более 20 лет
              безотказной службы. В сочетании с возобновляемыми источниками
              электроэнергии Станция делает ваше домашнее хозяйство и транспорт
              независимым от углеводородного топлива и его коммуникаций.»
              <HideText>
                «Н2Глобус объединил оборудование, работающее на основе
                электро-химических процессов, без трущихся частей, способное
                дать от 2 кг/день водорода чистотой 99,9999..% давлением до 700
                бар.<br />Станция может масштабироваться от 2 до 100 кг
                водорода/день. Управление и мониторинг осуществляется с
                мобильного телефона с использованием искусственного интеллекта.
                Опционально Станция может осуществлять альтернативное
                теплоснабжение и электроснабжение зданий, а также генерацию
                кислорода – от 8,5 до 425 кг/день»
              </HideText>
            </p>
          </div>
        </div>
      </section>
    </div>

    <section class="f jc-c p-4">
      <div class="container f fd-col rg-4 ta-c">
        <h1 class="c-brand" style="font-family: 'Oswald'; font-weight: 600">
          - Документация -
        </h1>

        <div
          class="banner-list f jc-sb g-3 c-second-100"
          style="font-family: 'Roboto'"
        >
          <div class="f fd-col banner rg-3">
            <div class="image">
              <img src="@/assets/images/alex-nerovnya017-768x926.jpg" />
            </div>
            <h2>Флаер Станция Н2Глобус</h2>
            <h4 class="fw-regular">Версия для ПК</h4>
            <a
              href="https://h2globus.com/wp-content/uploads/2022/08/Flaer-PK-H2Globus.pdf"
              target="_blank"
            >
              Скачать
            </a>
          </div>

          <div class="f fd-col banner rg-3">
            <div class="image">
              <img src="@/assets/images/2022-08-13-142907.png.png" />
            </div>
            <h2>Флаер Станция Н2Глобус</h2>
            <h4 class="fw-regular">Версия для смарфона</h4>
            <a
              href="https://h2globus.com/wp-content/uploads/2022/08/Flaer-smartfon-H2Globus.pdf"
              target="_blank"
            >
              Скачать
            </a>
          </div>

          <div class="f fd-col banner rg-3">
            <div class="image">
              <img src="@/assets/images/kolonka-4k.png.png" />
            </div>
            <h2>Технические данные Станции Н2Глобус</h2>
            <a
              href="https://h2globus.com/wp-content/uploads/2022/08/TX4-_1.pdf"
              target="_blank"
            >
              Скачать
            </a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="mt-5 f jc-c bg-brand p-3">
    <div class="container f ai-c jc-sb g-4" style="font-family: 'Roboto'">
      <div class="w-100 f fd-col rg-3">
        <h1 class="c-default">Контакты</h1>

        <ul class="socials f fd-col rg-2">
          <li>
            <a
              class="f ai-c cg-2"
              href="mailto:office@h2globus.com"
              target="_blank"
              rel="nofollow"
            >
              <span class="material-symbols-outlined c-default"> mail </span>
              office@h2globus.com
            </a>
          </li>
          <li>
            <a
              class="f ai-c cg-2"
              href="tel:37379535511"
              target="_blank"
              rel="nofollow"
            >
              <span class="material-symbols-outlined c-default"> phone </span>
              +37379535511
            </a>
          </li>
          <li>
            <a
              class="f ai-c cg-2"
              href="https://api.whatsapp.com/send?phone=37379535511"
              target="_blank"
              rel="nofollow"
            >
              <img
                src="https://cdn-icons-png.flaticon.com/512/3781/3781677.png"
                height="16"
                style="filter: invert(100%)"
              />
              WhatsApp
            </a>
          </li>
          <li>
            <a
              class="f ai-c cg-2"
              href="viber://chat?number=%2B37379535511"
              target="_blank"
              rel="nofollow"
            >
              <img
                src="https://cdn-icons-png.flaticon.com/512/1946/1946553.png"
                height="16"
                style="filter: invert(100%)"
              />
              Viber
            </a>
          </li>
          <li>
            <a
              class="f ai-c cg-2"
              href="https://t.me/livada_organica"
              target="_blank"
              rel="nofollow"
            >
              <img
                src="https://www.freepnglogos.com/uploads/telegram-logo-12.png"
                height="16"
                style="filter: invert(100%)"
              />
              Telegram
            </a>
          </li>
          <li class="f ai-c cg-2">
            <span class="material-symbols-outlined c-default">
              location_on
            </span>
            Молдова, г.Тирасполь, ул. Карла-Либкнехта 385, каб. 201, 202, 204
          </li>
          <li class="f ai-c cg-2">
            <span class="material-symbols-outlined c-default">
              location_on
            </span>
            с. Суклея, ул. Котовского 81
          </li>
        </ul>
      </div>

      <div class="w-100 f jc-c">
        <img height="300"  src="@/assets/images/logo.svg" />
      </div>

      <div class="w-100 f fd-col rg-3">
        <h2 class="c-default">h2globus в соц. сетях</h2>

        <div class="links f g-3">
          <a
            class="elementor-icon elementor-social-icon elementor-social-icon-facebook elementor-repeater-item-3903f53"
            href="https://www.facebook.com/H2Globus-108068427649298/"
            target="_blank"
            rel="nofollow"
          >
            <img src="@/assets/images/59439.png" height="32" />
          </a>

          <a
            class="elementor-icon elementor-social-icon elementor-social-icon-instagram elementor-repeater-item-ae04d4f"
            href="https://www.instagram.com/h2globus/"
            target="_blank"
            rel="nofollow"
          >
            <img src="@/assets/images/87390.png" height="32" />
          </a>
        </div>

        <p class="c-default">
          Являемся участниками проекта по развитию Водородных технологий
        </p>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&family=Oswald:wght@200;300;400;500;600;700&family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300;400;500;600;700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.material-symbols-outlined {
  font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 48;
  font-size: 16px;
}

.main_banner {
  position: relative;
  overflow: hidden;
  min-height: 800px;
  > img.slide-1 {
    top: 0;
    left: 0;
    position: absolute;
    object-fit: cover;
    width: 100%;
    height: 100%;
    filter: blur(2px) brightness(60%);
    animation: banner1 10s infinite;
  }
  > img.slide-2 {
    top: 0;
    left: 0;
    position: absolute;
    object-fit: cover;
    width: 100%;
    height: 100%;
    filter: blur(2px) brightness(60%);
    animation: banner2 10s infinite;
  }
  .container {
    z-index: 10;
    // color: #828282;
  }
}

@keyframes banner1 {
  0% {
    opacity: 0;
    scale: 1;
  }
  50% {
    scale: 1.5;
  }
  75% {
    opacity: 1;
  }
  100% {
    scale: 1;
  }
}
@keyframes banner2 {
  0% {
    scale: 1;
    opacity: 1;
  }
  50% {
    scale: 1.5;
  }
  75% {
    opacity: 0;
  }
  100% {
    scale: 1;
  }
}

.banner-list {
  flex-wrap: wrap;
  .banner {
    width: calc((100% - 32px) / 3);
    min-width: 200px;
    flex-grow: 1;
    div.image {
      overflow: hidden;
      aspect-ratio: 16/9;
      transition: 0.5s;
      img {
        object-fit: cover;
        width: 100%;
        height: 100%;
        transition: 0.5s;
        background-color: var(--n-default);
      }
      &:hover {
        filter: brightness(60%);
        img {
          scale: 1.1;
        }
      }
    }
  }
}

footer {
  min-height: 572px;
  .links {
    a {
      opacity: 0.8;
      border: 3px solid black;
      padding: 8px;
      border-radius: 50%;
      aspect-ratio: 1;
      display: inline-flex;
      align-items: center;
      justify-content: center;
    }
  }

  .socials {
    a {
      color: var(--n-base);
    }
  }
}

a:hover {
  filter: brightness(150%);
}

div.bg-brand,
footer.bg-brand {
  background-color: none;
  background-color: linear-gradient(210deg, #0091f6 0%, #72c4ff 100%);
}
footer {
  overflow: hidden;
  background-image: url(https://h2globus.com/wp-content/uploads/2022/04/hydrogen-fuel-illustration-cropped.jpg) !important;
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  background-blend-mode: soft-light;
  background-color: #6ec1e4 !important;
  .container {
    z-index: 2;
  }
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
html {
  font-size: var(--n-fs-p);
  color: var(--n-base);
}

body {
  font-family: 'Open Sans', sans-serif;
  line-height: var(--n-lh-regular);
  display: flex;
  min-height: 100vh;
  font-family: 'Rubik';
}

#app {
  width: 100%;
  display: flex;
  flex-direction: column;
}

.container {
  max-width: 1180px;
  width: 100%;
}

@media (max-width: 768px) {
  .container,
  section {
    flex-direction: column;
  }
}

a {
  text-decoration: none;
  transition: 0.15s;
  color: var(--n-second-100);
}

ul,
li {
  list-style: none;
  text-decoration: none;
}
</style>
