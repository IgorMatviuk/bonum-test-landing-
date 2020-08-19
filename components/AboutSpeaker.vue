<template>
  <div class="section-about-speaker">
    <div class="section-about-speaker__man"></div>
    <div class="section-about-speaker__Rectangle100"></div>
    <div class="section-about-speaker__button">
      <button class="buttonBlue2">Максим Орыщак</button>
    </div>
    <div class="section-about-speakerCard">
      <div class="section-about-speakerCard__wrapper"></div>
      <div class="section-about-speakerCard__content">
        <div>
          <div class="section-about-speakerCard__content__title">
            ФИНАНСОВЫЙ ЭКСПЕРТ
          </div>
          <div class="section-about-speakerCard__content__text">
            ПРО СПИКЕРА
          </div>
        </div>
        <div class="section-about-speakerCard__content__colomnContainer">
          <div class="section-about-speakerCard__content__colomnOne">
            <div>
              <div>
                <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
              </div>
              <div class="section-about-speakerCard__content__block-title">
                <p>Управляющий</p>
              </div>
              <div class="section-about-speakerCard__content__block-text">
                <p>
                  Управляющий дистанционного офиса компании “Центр биржевых
                  технологий”
                </p>
              </div>
            </div>
            <div>
              <div>
                <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
              </div>
              <div class="section-about-speakerCard__content__block-title">
                <p>Аналитик</p>
              </div>
              <div class="section-about-speakerCard__content__block-text">
                <p>
                  Аналитик и инвестор с 8 летним опытом (с 2011 года), банкир
                </p>
              </div>
            </div>
            <div>
              <div>
                <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
              </div>
              <div class="section-about-speakerCard__content__block-title">
                <p>Медийная личность</p>
              </div>
              <div class="section-about-speakerCard__content__block-text">
                <p>
                  Личные блоги на ресурсах компании Центр биржевых технологий”,
                  Минфин, thepage.ua, YouTube, Telegram
                </p>
              </div>
            </div>
          </div>
          <div class="section-about-speakerCard__content__colomnTwo">
            <div>
              <div>
                <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
              </div>
              <div class="section-about-speakerCard__content__block-title">
                <p>Финансовый эксперт</p>
              </div>
              <div class="section-about-speakerCard__content__block-text">
                <p>
                  Во главе команды опытных финансовых экспертов, предоставляет
                  клиентам возможность заработка на финансовом рынке и оказывает
                  всестороннюю консультационную поддержку в вопросах торговли и
                  инвестирования на финансовых рынках.
                </p>
              </div>
            </div>
            <div>
              <div>
                <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
              </div>
              <div>
                <p class="section-about-speakerCard__content__block-title">
                  Эффективный спикер
                </p>
              </div>
              <div class="section-about-speakerCard__content__block-text">
                <p>
                  Максим разработал обучающий курс по заработку на финансовом
                  рынке «Smart Value Invest». Показатели эффективности его
                  работы красноречиво выразились в цифрах — за 8 лет подготовил
                  более 1000 успешных трейдеров и сформировал более 100
                  высоколиквидных инвестиционных портфелей.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section-about-speaker {
  background-color: #4069a7;
  height: 840px;
  display: flex;
  position: relative;
  &__button {
    display: flex;
    position: absolute;
    z-index: 6;
    margin: 740px 0px 0px 650px;
  }
  &__Rectangle100 {
    display: flex;
    background-image: url("../assets/image/1_main/1080x1920/Rectangle 150.svg");
    position: absolute;
    z-index: 3;
    width: 589px;
    height: 674px;
    margin: 55px 0px 0px 350px;
  }
  &__man {
    display: flex;
    background-image: url("../assets/image/1_main/1080x1920/man.png");
    position: absolute;
    z-index: 3;
    width: 600px;
    height: 800px;
    margin: 43px 0px 0px 400px;
  }
}
.section-about-speakerCard {
  background-color: #1d2b46;
  height: 840px;
  display: flex;
  width: 1185px;
  height: 920px;
  position: absolute;
  z-index: 2;
  bottom: 0px;
  left: 730px;
  &__wrapper {
    background-image: url("../assets/image/bg/Blueprint.svg");
    position: absolute;
    z-index: 3;
    width: 1185px;
    height: 920px;
  }
  &__content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 270px;
    &__title {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: #75acff;
    }
    &__text {
      font-weight: bold;
      font-size: 35px;
      line-height: 50px;
      text-transform: uppercase;
      color: #ffffff;
      display: flex;
    }
    &__colomnContainer {
      display: flex;
      img {
        margin-top: 50px;
      }
    }
    &__colomnOne {
      display: flex;
      flex-direction: column;
    }
    &__colomnTwo {
      display: flex;
      flex-direction: column;
      padding-left: 100px;
    }
    &__block-title {
      font-weight: bold;
      font-size: 18px;
      line-height: 23px;
      letter-spacing: 0.1em;
      color: #ffffff;
      display: flex;
    }
    &__block-text {
      width: 300px;
      font-weight: normal;
      font-size: 14px;
      line-height: 18px;
      color: #ffffff;
      p {
        margin-top: 0px;
      }
    }
  }
}
@media (max-width: 768px) {
  .section-about-speaker {
    background-color: #4069a7;
    height: 570px;
    display: flex;
    position: relative;
    &__button {
      display: flex;
      position: absolute;
      z-index: 6;
      margin: 511px 0px 0px 270px;
    }
    &__Rectangle100 {
      display: flex;
      background-image: url("../assets/image/1_main/360x640/ramki/ramka_header.svg");
      position: absolute;
      z-index: 3;
      width: 317px;
      height: 472px;
      margin: 75px 0px 0px 20px;
    }
    &__man {
      display: flex;
      background-image: url("../assets/image/1_main/360x640/man_mob.png");
      position: absolute;
      z-index: 3;
      width: 300px;
      height: 420px;
      margin: 150px 0px 0px 20px;
    }
  }
  .section-about-speakerCard {
    background-color: #1d2b46;
    height: 840px;
    display: flex;
    width: 658px;
    height: 630px;
    position: absolute;
    z-index: 2;
    bottom: 0px;
    left: 271px;
    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg") no-repeat;
      position: absolute;
      z-index: 4;
      width: 958px;
      height: 570px;
      right: 0px;
    }
    &__content {
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 78px;
      margin-top: 60px;
      &__title {
        font-weight: bold;
        font-size: 8px;
        line-height: 18px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
      }
      &__text {
        font-weight: bold;
        font-size: 15px;
        line-height: 50px;
        text-transform: uppercase;
        color: #ffffff;
        display: flex;
      }
      &__colomnContainer {
        display: flex;
        margin-top: 0px;
        img {
          width: 30px;
          padding-top: 0px;
          margin: 30px 0px 0px 0px;
        }
      }
      &__colomnOne {
        display: flex;
        flex-direction: column;
        width: 200px;
      }
      &__colomnTwo {
        display: flex;
        flex-direction: column;
        padding-left: 15px;
        width: 200px;
      }
      &__block-title {
        font-weight: bold;
        font-size: 10px;
        line-height: 23px;
        letter-spacing: 0.1em;
        color: #ffffff;
        display: flex;
        margin-bottom: 10px;
      }
      &__block-text {
        width: 180px;
        font-weight: normal;
        font-size: 10px;
        line-height: 18px;
        color: #ffffff;
        p {
          margin-top: -10px;
        }
      }
    }
  }
}
@media (max-width: 450px) {
  .section-about-speaker {
    background-color: #4069a7;
    height: 1400px;
    display: flex;
    position: relative;
    flex-direction: column;
    padding-bottom: 951px;
    &__button {
      display: flex;
      position: absolute;
      z-index: 6;
      margin: 400px 0px 0px 0px;
    }
    &__Rectangle100 {
      display: flex;
      background-image: url("../assets/image/1_main/360x640/ramki/ramka_speaker_back_mob.svg");
      position: absolute;
      z-index: 3;
      width: 312px;
      height: 362px;
      margin: 55px 0px 0px 20px;
    }
    &__man {
      display: flex;
      background-image: url("../assets/image/1_main/360x640/man_mob.png");
      position: absolute;
      z-index: 3;
      width: 320px;
      height: 418px;
      margin: 33px 0px 0px 20px;
    }
  }
  .section-about-speakerCard {
    background-color: #1d2b46;
    width: 100%;
    height: 950px;
    display: flex;
    position: relative;
    z-index: 2;
    margin: 450px 0px 0px -270px;

    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg");
      position: relative;
      z-index: 5;
      width: 960px;
      height: 950px;
      display: none;
    }
    &__content {
      display: flex;
      flex-direction: column;
      margin: 0px 0px 0px -30px;
      &__title {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        margin: 0px 0px 0px 0px;
      }
      &__text {
        font-weight: bold;
        font-size: 35px;
        line-height: 50px;
        text-transform: uppercase;
        color: #ffffff;
        display: flex;
      }
      &__colomnContainer {
        margin: 0px 0px 0px 0px;
        display: flex;
        flex-direction: column;
        justify-content: center;

        img {
          margin: 30px 0px 0px 0px;
        }
      }
      &__colomnOne {
        display: flex;
        flex-direction: column;
        margin: 0px 0px 0px 0px;
        width: 300px;
      }
      &__colomnTwo {
        display: flex;
        flex-direction: column;
        padding: 0px 0px 0px 0px;
        width: 300px;
      }
      &__block-title {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        letter-spacing: 0.1em;
        color: #ffffff;
        display: flex;
        padding: 5px 0px 0px 18px;
      }
      &__block-text {
        width: 250px;
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 15px;
        color: #ffffff;
        padding-left: 18px;
        p {
          margin-top: 0px;
        }
      }
    }
  }
}
</style>
