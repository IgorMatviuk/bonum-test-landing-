<template>
  <div class="section-discover">
    <div class="section-discover__left">
      <div class="section-discover__left__blocks">
        <div class="section-discover__left__wrapper"></div>
        <div>
          <div class="section-discover__left__block">
            <div>
              <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
            </div>
            <div class="section-discover__left__block__title">
              <p>Мы всегда в тренде:</p>
            </div>
            <div class="section-discover__left__block__text">
              <p>Наши курсы постоянно подпитываются и</p>
              <p>обновляются инсайдерской информацией от</p>
              <p>наших западных партнеров.</p>
            </div>
          </div>
          <div class="section-discover__left__block">
            <div>
              <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
            </div>
            <div class="section-discover__left__block__title">
              <p>Только практика</p>
            </div>
            <div class="section-discover__left__block__text">
              <p>Компания ЦБТ больше 20 лет популяризирует</p>
              <p>финансовую грамотность на территории нашей</p>
              <p>страны. Мы являемся лидером по количеству</p>
              <p>клиентов, которые прошли наши курсы и</p>
              <p>увеличили свои доходы в разы</p>
            </div>
          </div>
        </div>
        <div>
          <div
            class="section-discover__left__block section-discover__left__block__blockEnd"
          >
            <div>
              <img src="../assets/image/1_main/1080x1920/kavichka_full.svg" />
            </div>
            <div class="section-discover__left__block__title">
              <p>Реальные результаты</p>
            </div>
            <div class="section-discover__left__block__text">
              <p>Благодаря слаженной работе компании</p>
              <p>только за прошлый год мы помогли</p>
              <p>заработать нашим клиентам свыше $10 000</p>
              <p></p>
              <p>000,00</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section-discover__right">
      <div>
        <div class="section-discover__right__title">
          <p>Центр Биржевых Технологий</p>
        </div>
        <div class="section-discover__right__text">
          <p>3 причины,</p>
          <p>почему Вам нужно</p>
          <p>посетить вебинар</p>
        </div>
        <div class="section-discover__right__button">
          <button class="btn buttonOrange">Что вы узнаете?</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section-discover {
  display: flex;
  height: 650px;
  font-family: CeraPro-Light;
  &__left {
    position: relative;
    display: flex;
    width: 55%;
    background: #4069a7;
    &__wrapper {
      background-image: url("../assets/image/bg/map_laptop.svg");
      bottom: 300px;
      right: 100px;
      position: absolute;
      z-index: 8;
      width: 1200px;
      height: 100%;
    }
    &__blocks {
      display: flex;
      margin: 100px 0px 0px 170px;
    }
    &__block {
      display: flex;
      flex-direction: column;
      align-items: center;
      img {
        margin-left: -170px;
        margin-top: 30px;
      }
      &__title {
        font-weight: bold;
        font-size: 18px;
        line-height: 23px;
        letter-spacing: 0.1em;
        color: #f2f4f9;
        margin-bottom: 10px;
      }
      &__text {
        font-weight: normal;
        font-size: 14px;
        line-height: 18px;
        color: #f2f4f9;
        p {
          margin-top: 0px;
        }
      }
      &__blockEnd {
        padding-left: 50px;
      }
    }
  }
  &__right {
    width: 45%;
    position: relative;
    background: #f2f4f9;
    display: flex;
    align-items: center;
    justify-content: center;
    &__title {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: #75acff;
      padding-bottom: 30px;
    }
    &__text {
      font-weight: bold;
      font-size: 35px;
      line-height: 50px;
      text-transform: uppercase;
      color: #000000;
      p {
        margin-top: -10px;
      }
    }
    &__button {
      display: flex;
    }
  }
}
@media (max-width: 768px) {
  .section-discover {
    display: flex;
    height: 650px;
    &__left {
      display: flex;
      width: 65%;
      background: #4069a7;
      &__blocks {
        display: flex;
        margin: 100px 30px 0px 30px;
      }
      &__block {
        display: flex;
        flex-direction: column;
        align-items: center;
        &__title {
          font-weight: bold;
          font-size: 16px;
          line-height: 23px;
          letter-spacing: 0.1em;
          color: #f2f4f9;
          margin-bottom: 10px;
        }
        &__text {
          font-weight: normal;
          font-size: 14px;
          line-height: 18px;
          color: #f2f4f9;
          p {
            margin-top: 0px;
          }
        }
        &__blockEnd {
          padding-left: 50px;
        }
        img {
          padding-right: 0px;
          margin: 20px 140px 0px 0px;
        }
      }
    }
    &__right {
      width: 35%;
      background: #f2f4f9;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 120px;
      &__title {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        padding-bottom: 60px;
        margin-left: 30px;
      }
      &__text {
        font-weight: bold;
        font-size: 20px;
        line-height: 50px;
        text-transform: uppercase;
        color: #000000;
        margin-left: 30px;
        p {
          margin-top: -50px;
          margin-bottom: 30px;
        }
      }
      &__button {
        display: flex;
        margin-left: 30px;
      }
    }
  }
}
@media (max-width: 450px) {
  .section-discover {
    display: flex;
    flex-direction: column-reverse;
    height: 810px;
    width: 100%;
    &__left {
      height: 550px;
      width: 100%;
      display: flex;
      background: #4069a7;
      &__wrapper {
        background-image: url("../assets/image/bg/map_laptop.svg");
        bottom: 10px;
        right: 50px;
        position: absolute;
        z-index: 8;
        width: 1200px;
        height: 100%;
      }
      &__blocks {
        display: flex;
        flex-direction: column;
        margin: 0px 0px 0px 20px;
      }
      &__block {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: -100px 0px 0px 0px;
        img {
          padding: 120px 130px 0px 0px;
        }
        &__title {
          font-weight: bold;
          font-size: 14px;
          line-height: 18px;
          letter-spacing: 0.1em;
          color: #f2f4f9;
          margin-bottom: 10px;
        }
        &__text {
          font-style: normal;
          font-weight: normal;
          font-size: 12px;
          line-height: 15px;
          color: #f2f4f9;
          p {
            margin-top: 0px;
          }
        }
        &__blockEnd {
          padding-left: 0px;
        }
      }
    }
    &__right {
      position: relative;
      top: 120px;
      height: 260px;
      width: 100%;
      background: #f2f4f9;
      display: flex;
      justify-content: center;
      &__title {
        font-weight: bold;
        font-size: 10px;
        line-height: 13px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        padding: 30px 0px 30px 0px;
        margin-right: 50px;
      }
      &__text {
        font-weight: bold;
        font-size: 20px;
        line-height: 27px;
        text-transform: uppercase;
        color: #000000;
        margin: 30px 0px 0px 30px;
        p {
          margin-top: -28px;
        }
      }
      &__button {
        display: flex;
        margin: 0px 0px 40px 30px;
      }
    }
  }
}
</style>
