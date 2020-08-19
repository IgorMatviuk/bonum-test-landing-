<template>
  <div class="section-whom">
    <div class="section-whom__left"></div>
    <div class="section-whom__right">
      <div class="section-whom__right__title">
        <p>МОЖЕТЕ НЕ ПРИХОДИТЬ!</p>
      </div>
      <div class="section-whom__right__text">
        <p>КОМУ КАТЕГОРИЧЕСКИ</p>
        <p>ЗАПРЕЩЕНО ПОСЕЩЕНИЕ</p>
        <p>ВЕБИНАРА?</p>
      </div>
    </div>
    <div class="section-whom__container">
      <div class="section-whom__container__block">
        <div class="section-whom__container__block__image">
          <img
            src="../assets/image/icons common/icons_zapresheno/iskatel.svg"
          />
        </div>
        <div class="section-whom__container__block__title">
          <p>Скептикам</p>
        </div>
        <div class="section-whom__container__block__text">
          <p>Это люди, которые всегда все знают лучше других.</p>
          <p>Они приходят на бесплатные мероприятия, чтобы</p>
          <p>покритиковать звук или цвет рубашки ведущего, но</p>
          <p>никак не за знаниями.</p>
        </div>
      </div>
      <div class="section-whom__container__block">
        <div class="section-whom__container__block__image">
          <img src="../assets/image/icons common/icons_zapresheno/nitik.svg" />
        </div>
        <div class="section-whom__container__block__title"><p>Нытикам</p></div>
        <div class="section-whom__container__block__text">
          <p>Вебинар абсолютно бесполезный для людей,</p>
          <p>постоянно ищущих оправдания. Вам не нравится</p>
          <p>ваша жизнь? Вините в этом всех, кроме себя?</p>
          <p>Извините, но нам не по пути.</p>
        </div>
      </div>
      <div class="section-whom__container__block">
        <div class="section-whom__container__block__image">
          <img
            src="../assets/image/icons common/icons_zapresheno/skeptik.svg"
          />
        </div>
        <div class="section-whom__container__block__title">
          <p>Искателям мгновенного обогащения</p>
        </div>
        <div class="section-whom__container__block__text">
          <p>Вы НЕ получите красную кнопку “Бабло”. Чтобы</p>
          <p>достичь хороших результатов, нужно работать.</p>
          <p>Много работать. Задайте себе вопрос: Готовы ли</p>
          <p>вы сейчас потрудиться, чтобы потом достойно</p>
          <p>зарабатывать? Если вы не готовы вкладывать силы</p>
          <p>в собственное развитие, мы не можем вам помочь.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section-whom {
  font-family: CeraPro-Light;
  display: flex;
  height: 731px;
  position: relative;
  &__left {
    width: 50%;
    background-image: url("../assets/image/1_main/1080x1920/zapresheno_photo 1.jpg");
    display: flex;
  }
  &__right {
    width: 50%;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    &__title {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: #75acff;
      margin: 70px 0px 0px 100px;
      padding-bottom: 15px;
    }
    &__text {
      font-weight: bold;
      font-size: 35px;
      line-height: 50px;
      text-transform: uppercase;
      color: #000000;
      margin: 0px 0px 0px 100px;
      p {
        margin: 0px 0px 0px 0px;
      }
    }
  }
  &__container {
    display: flex;
    background-color: #ffffff;
    width: 1300px;
    height: 390px;
    z-index: 3;
    position: absolute;
    margin: 340px 0px 0px 350px;
    justify-content: space-evenly;
    &__block {
      display: flex;
      flex-direction: column;
      padding-top: 100px;
      &__image {
        padding-right: 50px;
        padding-bottom: 10px;
      }
      &__title {
        font-weight: bold;
        font-size: 18px;
        line-height: 23px;
        letter-spacing: 0.1em;
        color: #000000;
      }
      &__text {
        font-weight: normal;
        font-size: 14px;
        line-height: 18px;
        color: #585858;
        p {
          margin-top: 0px;
        }
      }
    }
  }
}
@media (max-width: 1650px) {
  .section-main {
    &__Rectangle100 {
      width: 687px;
      height: 753px;
      margin: 100px 100px 100px 140px;
    }
    &__man {
      margin: 27px 0px 0px 210px;
    }
    &__man__header {
      margin: 77px 0px 0px 445px;
    }
    &__centerBlock {
      margin: 284px 0px 0px 630px;
      &__button__margin {
        margin: 0px 0px 0px 60px;
        display: flex;
      }
    }
    &__leftBlock {
      margin: 84px 0px 0px 140px;
    }
  }
}
@media (max-width: 768px) {
  .section-whom {
    display: flex;
    height: 530px;
    position: relative;
    &__left {
      width: 50%;
      background-image: url("../assets/image/1_main/768x960 vertical/zapresheno_photo 1.jpg");
      display: flex;
    }
    &__right {
      width: 50%;
      background-color: #ffffff;
      display: flex;
      flex-direction: column;
      &__title {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        margin: 60px 0px 0px 50px;
      }
      &__text {
        font-weight: bold;
        font-size: 21px;
        line-height: 50px;
        text-transform: uppercase;
        color: #000000;
        margin: 0px 0px 0px 50px;
        p {
          margin: -20px 0px 0px 0px;
        }
      }
    }
    &__container {
      display: flex;
      background-color: #ffffff;
      width: 977px;
      height: 300px;
      z-index: 3;
      position: absolute;
      margin: 230px 0px 0px 50px;
      justify-content: space-evenly;
      &__block {
        padding-right: 20px;
        display: flex;
        flex-direction: column;
        margin: 5px 0px 0px -110px;
        &__image {
          display: flex;
          margin: 0px 0px 0px -140px;
        }
        &__title {
          font-weight: bold;
          font-size: 12px;
          line-height: 23px;
          letter-spacing: 0px;
          color: #000000;
          margin-left: -135px;
        }
        &__text {
          font-weight: normal;
          font-size: 8px;
          line-height: 14px;
          color: #585858;
          margin-left: -135px;
          p {
            margin-top: -5px;
          }
        }
      }
    }
  }
}
@media (max-width: 450px) {
  .section-whom {
    display: flex;
    position: relative;
    flex-direction: column-reverse;
    &__left {
      height: 327px;
      width: 100%;
      background-image: url("../assets/image/1_main/360x640/zapresheno_photo_mob.jpg");
      background-repeat: no-repeat;
      display: flex;
      padding-bottom: 870px;
    }
    &__right {
      height: 360px;
      width: 100%;
      background-color: #ffffff;
      display: flex;
      flex-direction: column;
      padding-bottom: 40px;
      &__title {
        font-weight: bold;
        font-size: 10px;
        line-height: 13px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        margin: 0px 0px 0px 20px;
      }
      &__text {
        font-weight: bold;
        font-size: 20px;
        line-height: 27px;
        text-transform: uppercase;
        margin: 0px 0px 0px 20px;
        p {
          margin: 0px 0px 0px 0px;
        }
      }
    }
    &__container {
      display: flex;
      background-color: #ffffff;
      width: 100%;
      height: 630px;
      z-index: 6;
      position: absolute;
      margin: 0px 0px 10px 0px;
      flex-direction: column;
      &__block {
        display: flex;
        flex-direction: column;
        margin: 0px 0px 30px 20px;
        padding: 0px 0px 0px 0px;
        &__image {
          margin: 0px 0px 10px 0px;
        }
        &__title {
          font-weight: bold;
          font-size: 14px;
          line-height: 18px;
          letter-spacing: 0.1em;
          color: #000000;
          margin: 0px 0px 0px 10px;
        }
        &__text {
          font-style: normal;
          font-weight: normal;
          font-size: 12px;
          line-height: 15px;
          color: #585858;
          margin: 0px 0px 0px 10px;
          p {
            margin-top: 0px;
          }
        }
      }
    }
  }
}
</style>
