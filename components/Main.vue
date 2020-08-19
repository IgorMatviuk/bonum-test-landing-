<template>
  <div class="section-main">
    <div class="section-main__wrapper">
      <div class="section-main__Rectangle100"></div>
      <div class="section-main__"></div>
      <div class="section-main__man"></div>
      <div class="section-main__man__header"></div>
      <div class="section-main__centerBlock">
        <div><hr /></div>
        <div class="section-main__centerBlock__smallText">
          <p>УЧАВСТВУЙТЕ В ВЕБИНАРЕ</p>
        </div>
        <div class="section-main__centerBlock__TitleText">
          <div><p>КАК СОЗДАТЬ</p></div>
          <div class="section-main__centerBlock__TitleText__margin">
            <strong><p>ПАССИВНЫЙ ДОХОД</p></strong>
          </div>
        </div>
        <div><hr /></div>
        <div class="section-main__centerBlock__button__margin">
          <div>
            <button class="btn buttonOrange">Узнать больше</button>
          </div>
          <div>
            <button class="btn buttonBlue">Смотреть видео</button>
          </div>
        </div>
      </div>
      <div class="section-main__leftBlock">
        <div class="section-main__leftBlock__TitleText"><p>СПИКЕР</p></div>
        <div class="section-main__leftBlock__Name"><p>Максим Орышак</p></div>
        <div><hr /></div>
        <div class="section-main__leftBlock__text">
          <p>управляющий дистанционного офиса</p>
          <p>компании “Центр биржевых технологий”</p>
        </div>
        <div><hr /></div>
      </div>
    </div>
    <div class="section-main__left"></div>
    <div class="section-main__right"></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section-main {
  display: flex;
  height: 910px;
  position: relative;
  &__wrapper {
    background: url("../assets/image/bg/Blueprint.svg");
    position: absolute;
    z-index: 2;
    width: 100%;
    height: 910px;
  }
  &__Rectangle100 {
    background-image: url("../assets/image/1_main/1080x1920/Rectangle 150.svg");
    position: absolute;
    z-index: 4;
    width: 589px;
    height: 673px;
    margin: 100px 100px 100px 250px;
  }
  &__man {
    background: url("../assets/image/1_main/1080x1920/man_header.png") no-repeat;
    position: absolute;
    z-index: 3;
    width: 600px;
    height: 1200px;
    margin: 27px 0px 0px 265px;
  }
  &__man__header {
    background-image: url("../assets/image/1_main/1080x1920/man_header_part.png");
    position: absolute;
    z-index: 5;
    width: 195px;
    height: 30px;
    margin: 76px 0px 0px 498px;
  }
  &__centerBlock {
    align-items: center;
    display: flex;
    flex-direction: column;
    position: absolute;
    z-index: 4;
    margin: 273px 0px 0px 730px;
    hr {
      border: none;
      background-color: #75acff;
      height: 2px;
      width: 880px;
    }
    &__smallText {
      color: #75acff;
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      margin: 38px 0px -30px -550px;
      font-family: CeraPro-Light;
    }
    &__TitleText {
      color: #ffffff;
      font-weight: normal;
      font-size: 75px;
      line-height: 85px;
      margin: 48px 0px 30px -130px;
      padding-bottom: 7px;
      font-family: CeraPro-Light;
    }
    &__TitleText__margin {
      margin-top: 0px;
    }
    &__button__margin {
      margin-top: 30px;
      display: flex;
      button {
        margin-left: 30px;
      }
    }
  }
  &__leftBlock {
    align-items: center;
    display: flex;
    flex-direction: column;
    position: absolute;
    z-index: 4;
    margin: 150px 0px 0px 250px;
    hr {
      border: none;
      background-color: #75acff;
      height: 2px;
      width: 275px;
      margin: 10px 0px 10px 0px;
    }
    &__TitleText {
      color: #ffffff;
      font-weight: 300;
      font-size: 20px;
      line-height: 25px;
      letter-spacing: 0.2em;
      padding: 25px 105px 0px 10px;
      font-family: CeraPro-Light;
    }
    &__Name {
      color: #f5841f;
      font-weight: 500;
      font-size: 26px;
      line-height: 33px;
    }
    &__text {
      font-weight: normal;
      font-size: 11px;
      line-height: 14px;
      letter-spacing: 0.04em;
      color: #b1bfe0;
      padding-left: 40px;
    }
  }
  &__left {
    width: 38%;
    background-color: #4069a7;
  }
  &__right {
    width: 62%;
    background-color: #031530;
  }
}
@media (max-width: 1650px) {
  .section-main {
    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg");
      position: absolute;
      z-index: 2;
      width: 100%;
      height: 910px;
    }
    &__Rectangle100 {
      width: 588px;
      height: 672px;
      margin: 100px 100px 100px 140px;
      background-repeat: no-repeat;
    }
    &__man {
      margin: 27px 0px 0px 210px;
    }
    &__man__header {
      margin: 77px 0px 0px 445px;
    }
    &__centerBlock {
      margin: 274px 0px 0px 630px;
      &__button__margin {
        margin: 50px 0px 0px 60px;
        padding-top: 50px;
        display: flex;
      }
    }
    &__leftBlock {
      margin: 84px 0px 0px 140px;
    }
  }
}
@media (max-width: 1450px) {
  .section-main {
    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg");
      position: absolute;
      z-index: 2;
      width: 100%;
      height: 910px;
    }
    &__Rectangle100 {
      width: 588px;
      height: 672px;
      margin: 100px 100px 100px 40px;
      background-repeat: no-repeat;
    }
    &__man {
      margin: 27px 0px 0px 65px;
    }
    &__man__header {
      margin: 77px 0px 0px 300px;
    }
    &__centerBlock {
      margin: 274px 0px 0px 485px;
      &__button__margin {
        margin: 50px 0px 0px 0px;
        padding-top: 50px;
        display: flex;
      }
    }
    &__leftBlock {
      margin: 90px 0px 0px 40px;
    }
  }
}
@media (max-width: 768px) {
  .section-main {
    display: flex;
    height: 680px;
    position: relative;
    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg");
      position: absolute;
      z-index: 2;
      width: 100%;
      height: 532px;
    }
    &__Rectangle100 {
      background-image: url("../assets/image/1_main/768x960 gorizont/Rectangle 100.svg");
      position: absolute;
      z-index: 4;
      width: 602px;
      height: 632px;
      margin: 100px 100px 100px 8px;
    }
    &__man {
      background: url("../assets/image/1_main/768x960 gorizont/man_header.png")
        no-repeat;
      position: absolute;
      z-index: 3;
      width: 600px;
      height: 645px;
      margin: 35px 0px 0px 0px;
      padding: 0px 0px 0px 0px;
    }
    &__man__header {
      background-image: url("../assets/image/1_main/768x960 gorizont/man_header_part.png");
      position: absolute;
      z-index: 4;
      width: 195px;
      height: 30px;
      margin: 73px 0px 0px 175px;
    }
    &__centerBlock {
      align-items: center;
      display: flex;
      flex-direction: column;
      position: absolute;
      z-index: 4;
      margin: 245px 0px 0px 250px;
      hr {
        border: none;
        background-color: #75acff;
        height: 2px;
        width: 400px;
      }
      &__smallText {
        color: #75acff;
        font-weight: bold;
        font-size: 16px;
        line-height: 18px;
        letter-spacing: 0.4em;
        margin: 40px 0px -5px -25px;
      }
      &__TitleText {
        color: #ffffff;
        font-weight: normal;
        font-size: 40px;
        line-height: 85px;
        margin: 18px 0px -25px 0px;
        padding-bottom: 40px;
      }
      &__TitleText__margin {
        margin-top: -25px;
      }
      &__button__margin {
        margin: 0px 0px 0px 130px;
        flex-direction: column;
        display: flex;
        button {
          margin-top: 10px;
        }
      }
    }
    &__leftBlock {
      align-items: center;
      display: flex;
      flex-direction: column;
      position: absolute;
      z-index: 4;
      margin: 84px 0px 0px -25px;
      display: none;
      hr {
        border: none;
        background-color: #75acff;
        height: 2px;
        width: 150px;
      }
      &__TitleText {
        color: #ffffff;
        font-weight: 300;
        font-size: 15px;
        line-height: 25px;
        letter-spacing: 0.2em;
        padding: 25px 105px 0px 40px;
      }
      &__Name {
        color: #f5841f;
        font-weight: 500;
        font-size: 20px;
        line-height: 33px;
        margin: -40px 0px -30px 20px;
      }
      &__text {
        font-weight: normal;
        font-size: 8px;
        line-height: 14px;
        letter-spacing: 0.04em;
        color: #b1bfe0;
        padding-left: 30px;
      }
    }
    &__left {
      width: 38%;
      background-color: #4069a7;
    }
    &__right {
      width: 62%;
      background-color: #031530;
    }
  }
}
@media (max-width: 450px) {
  .section-main {
    display: flex;
    height: 555px;
    width: 100%;
    position: relative;
    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg");
      position: absolute;
      z-index: 8;
      width: 100%;
      height: 532px;
    }
    &__Rectangle100 {
      background-image: url("../assets/image/1_main/360x640/ramki/ramka_header.svg");
      position: absolute;
      z-index: 4;
      width: 612px;
      height: 762px;
      margin: 55px 0px 0px -10px;
    }
    &__man {
      background: url("../assets/image/1_main/360x640/photo_header.png")
        no-repeat;
      position: absolute;
      z-index: 3;
      width: 600px;
      height: 645px;
      margin: 40px 0px 0px -25px;
    }
    &__man__header {
      background-image: url("../assets/image/1_main/360x640/photo_header_part.png");
      position: absolute;
      z-index: 4;
      width: 130px;
      height: 30px;
      margin: 43px 0px 0px 100px;
    }
    &__centerBlock {
      align-items: center;
      display: flex;
      flex-direction: column;
      position: absolute;
      z-index: 4;
      margin: 258px 0px 0px -20px;
      hr {
        border: none;
        background-color: #75acff;
        height: 2px;
        width: 380px;
        margin: 0px 0px 0px 0px;
      }
      &__smallText {
        color: #75acff;
        font-weight: bold;
        font-size: 10px;
        line-height: 18px;
        letter-spacing: 0.4em;
        margin: 17px 0px 5px -130px;
      }
      &__TitleText {
        color: #ffffff;
        font-weight: normal;
        font-size: 22px;
        line-height: 85px;
        margin: -30px 40px 0px -90px;
        padding-bottom: 0px;
        letter-spacing: 0em;
      }
      &__TitleText__margin {
        margin-top: -50px;
      }
      &__button__margin {
        margin: -30px 320px 0px 100px;
        flex-direction: column;
        display: flex;
        button {
          margin: 0px 0px 15px 0px;
        }
      }
    }
    &__leftBlock {
      align-items: center;
      display: none;
      flex-direction: column;
      position: absolute;
      z-index: 4;
      margin: 84px 0px 0px -25px;
      hr {
        border: none;
        background-color: #75acff;
        height: 2px;
        width: 150px;
      }
      &__TitleText {
        color: #ffffff;
        font-weight: 300;
        font-size: 15px;
        line-height: 25px;
        letter-spacing: 0.2em;
        padding: 25px 105px 0px 40px;
      }
      &__Name {
        color: #f5841f;
        font-weight: 500;
        font-size: 20px;
        line-height: 33px;
        margin: -40px 0px -30px 20px;
      }
      &__text {
        font-weight: normal;
        font-size: 8px;
        line-height: 14px;
        letter-spacing: 0.04em;
        color: #b1bfe0;
        padding-left: 30px;
      }
    }
    &__left {
      width: 38%;
      background-color: #4069a7;
    }
    &__right {
      width: 62%;
      background-color: #031530;
    }
  }
}
</style>
