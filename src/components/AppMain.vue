<template>
  <div class="main">
    <div class="main__wrapper">
    <h3 class="main__title">Выберите рассылки, которые подходят именно вам</h3>
    <div class="main__input--wrapper">
      <input type="text" class="main__input" placeholder="Электронная почта" />
      <button class="main__input--botton">Подписаться</button>
    </div>
    <div class="main__checkbox--wrapper">
      <AppCheckboxCastom class="main__checkbox" />
      <p class="main__checkbox--text">Подписаться на все рассылки</p>
    </div>

    <div class="mailings">
      <ul class="mailings__list">



        <li class="mailings__item">
            <div class="mailings__header">
                <div>
                    <p class="mailings__recommendation">Перед рассветом</p>
                    <h4 class="mailings__title">Утренний бухгалтер</h4>
                    <p class="mailings__specification">
                        Самые важные новости и события за день. Кратко, по делу,
                        структурировано.
                    </p>
                </div>
                <div class="mailings__img--wrapper">
                    <img src="./../../logo/Frame 3505.png" class="mailings__logo"></img>
                </div>
            </div>

            
            <ul class="mailings__description--list">
                <li class="mailings__description--item">
                    <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                    <p class="mailings__deskription--text">Новости для бухгалтеров, ИП и директора</p>
                </li>
                <li class="mailings__description--item">
                    <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                    <p class="mailings__deskription--text">Подборка статей за день</p>
                </li>
            </ul>
            <div class="mailings__subscribers--wrapper">
                <AppCheckboxCastom />
                <p class="mailings__subscribers--text">
                  Уже получает 59 342 человек
                </p>
            </div>
        </li>


        <li class="mailings__item">
            <div class="mailings__header">
                <div>
                    <p class="mailings__recommendation">После заката</p>
                    <h4 class="mailings__title">Ночной бухгалтер</h4>
                    <p class="mailings__specification">
                        Самая краткая газета о налогах и бухучете в мире — современная
                        рассылка для чтения.
                    </p>
                 </div>
                <div class="mailings__img--wrapper">
                    <img src="./../../logo/Frame 3507.png" class="mailings__logo"></img>
                </div>
            </div>
            <ul class="mailings__description--list">
                <li class="mailings__description--item">
                    <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                    <p class="mailings__deskription--text">Анализ, оценка и только самое главное</p>
                </li>
                <li class="mailings__description--item">
                    <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                    <p class="mailings__deskription--text">Лучшие комменты юзеров в обзоре</p> 
                </li>
            </ul>
            <div class="mailings__subscribers--wrapper">
                <AppCheckboxCastom />
                <p class="mailings__subscribers--text">
                    Уже получает 37 480 человек
                </p>
            </div>
        </li>


        <li class="mailings__item">
            <div class="mailings__header">
                <div>
                    <p class="mailings__recommendation">Раз в две недели</p>
                    <h4 class="mailings__title">Ножницы скидок</h4>
                    <p class="mailings__specification">
                        Подборка самых выгодных и полезных спецпредложений от надежных
                        компаний.
                    </p>
                </div>

                <div class="mailings__img--wrapper">
                    <img src="./../../logo/Frame 3509.png" class="mailings__logo"></img>
                </div>
            </div>
            <ul class="mailings__description--list">
                <li class="mailings__description--item">
                    <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                    <p class="mailings__deskription--text">Акции и скидки от лидеров рынка</p>
                </li>
                <li class="mailings__description--item">
                    <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                    <p class="mailings__deskription--text mailings__deskription--text-smiley">Те, кто подписался – экономят много денег</p>
                </li>
            </ul>
            <div class="mailings__subscribers--wrapper">
                <AppCheckboxCastom />
                <p class="mailings__subscribers--text">
                    Уже получает 92 118 человек
                </p>
            </div>
        </li>



        <li class="mailings__item">
            <div class="mailings__header">
                <div>
                    <p class="mailings__recommendation">По мере появления анонсов</p>
                    <h4 class="mailings__title">Чемодан вебинаров</h4>
                    <p class="mailings__specification">
                        Подборка с анонсами бесплатных вебинаров на самые топовые темы при
                        участии экспертов.
                    </p>
                </div>
                <div class="mailings__img--wrapper">
                    <img src="./../../logo/Frame 3511.png" class="mailings__logo"></img>
                </div>
            </div>
            <ul class="mailings__description--list">
                <li class="mailings__description--item">
                        <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                        <p class="mailings__deskription--text">Никогда не пришлем платные вебинары</p>
                </li>
                <li class="mailings__description--item">
                        <img src="./../../logo/Vector.svg" class="mailings__logo--description"></img>
                        <p class="mailings__deskription--text">Подборка топовых тем для вебинаров</p>
                </li>
            </ul>
            <div class="mailings__subscribers--wrapper">
                <AppCheckboxCastom />
                <p class="mailings__subscribers--text">
                    Уже получает 92 082 человек
                </p>
            </div>
        </li>


      </ul>
    </div>
    <img src="./../../logo/Frame 3539.png" class="footer__logo"></img>
  </div>
  </div>
</template>

<script setup lang="ts">
import AppCheckboxCastom from "./AppCheckboxCastom.vue";
</script>



<style scoped lang="scss">
.main {
  width: 1024px;
  height: 788px;
  background: #f5f5f8;
  border-radius: 16px;
  font-family: "Roboto", sans-serif;

  &__title {
    padding: 0;
    font-size: 24px;
    line-height: 32px;
    text-align: center;
    padding-top: 48px;
  }

  &__input--wrapper {
    width: 928px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    background-color: white;
    border-radius: 16px;
    border-top-right-radius: 100px;
    border-bottom-right-radius: 100px;
    margin-top: 24px;
  }

  &__input {
    width: 765px;
    height: 56px;
    border: 1px solid white;
    border-top-left-radius: 16px;
    border-bottom-left-radius: 16px;
    border-right: none;
    padding: 0;
    padding-left: 16px;
    font-size: 16px;
  }

  &__input--botton {
    width: 163px;
    height: 56px;
    border: 1px solid #316fee;
    border-radius: 100px;
    background-color: #316fee;
    color: white;
    font-size: 16px;
  }

  &__checkbox--wrapper {
    width: 240px;
    display: flex;
    justify-content: space-between;
    margin-top: 18px;
    margin-left: 49px;
  }

  &__checkbox {
    margin-top: 8px;
  }

  &__checkbox--text {
    font-size: 12px;
  }
}

.mailings {
  &__list {
    padding: 0;
    margin: 0;
    width: 976px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin: 32px auto 0 auto;
  }

  &__item {
    padding: 0;
    margin: 0;
    list-style: none;
    width: 452px;
    // height: 244px;
    padding-left: 24px;
    background-color: white;
    border-radius: 16px;
    margin-bottom: 24px;
    padding-bottom: 32px;
  }

  &__header {
    display: flex;
    justify-content: space-between;

  }

  &__recommendation {
    padding: 0;
    margin: 0;
    font-size: 13px;
    color: #999999;
    padding-top: 24px;
  }

  &__title {
    padding: 0;
    margin: 0;
    font-size: 20px;
    margin-top: 8px;
  }

  &__specification {
    padding: 0;
    margin: 0;
    color: #666666;
    margin-top: 8px;
    font-size: 13px;
    margin-top: 16px;

  }

  &__description--list {
    padding: 0;
    margin: 0;
    margin-top: 16px;
  }

  &__description--item {
    padding: 0;
    margin: 0;
    list-style: none;
    font-size: 14px;
    margin-bottom: 12px;
    display: flex;
  }

  &__logo--description {
    padding-right: 8px;
  }

  &__deskription--text {
    padding: 0;
    margin: 0;
  }

  &__subscribers--wrapper {
    display: flex;
    justify-content: left;
    margin-top: 22px;
  }

  &__subscribers--text {
    padding: 0;
    margin: 0;
    margin-left: 8px;
  }

  &__img--wrapper {
    margin-top: 24px;
    margin-right: 24px;
    margin-left: 20px;
  }

  &__logo {
    width: 80px;
    height: 80px;
  }
}


.footer__logo {
    display: block;
    width: 194px;
    margin: 0 auto;
    padding-bottom: 200px;
}

@media screen and (max-width: 730px) {
    .main {
        width: 375px;
        height: 1420px;


        &__title {
            font-size: 22px;
            margin: 8px 16px 0 16px;
            text-align: left;
            padding-top: 32px;
        }

        &__input--wrapper {
            width: 343px;
        }

        &__input--botton {
            display: block;
            width: 130px;
            font-size: 0px;
            background-image: url("./../../logo/ArrowBotton.svg");
            background-repeat: no-repeat;
            background-position: 50% 50%;
        }

        &__checkbox--wrapper {
            width: 240px;
            display: flex;
            justify-content: space-between;
            margin-top: 18px;
            margin-left: 16px;
        }
    }

    .mailings {
        &__list {
            flex-wrap: wrap;
            margin: 24px auto 0 auto;
            width: 343px;
        }

        &__item {
            // height: 252px;
            margin-bottom: 24px;
            position: relative;
        }

        &__logo {
            position: absolute;
            top: 24px;
            right: 16px;
            width: 40px;
            height: 40px;
        }

        &__subscribers--wrapper {
            margin: 0;
            padding: 0;
            margin-top: 26px;
        }

        &__subscribers--text {
            margin-left: 0px;
            font-size: 14px;
        }


        &__deskription--text {
            font-size: 12px;
        }

        &__deskription--text-smiley::after {
            content: '\1F911';
        }
        
    }
}
</style>
