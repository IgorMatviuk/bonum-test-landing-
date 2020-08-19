<template>
  <div class="section-mail">
    <div class="wrapper"></div>
    <div class="section-mail__left">
      <div>
        <p class="section-mail__left__text1">запишитесь сейчас !</p>
        <p class="section-mail__left__text2">ХОЧУ УЧАСТВОВАТЬ</p>
        <p class="section-mail__left__text2 section-mail__left__text2__margin">
          В ВЕБИНАРЕ
        </p>
      </div>
    </div>
    <div class="section-mail__right">
      <div>
        <div>
          <div class="section-mail__right__input__name">
            <p><a>*</a>Ваше имя</p>
          </div>
          <div>
            <input class="inputWhite" value="Александр" />
          </div>
        </div>
        <div>
          <div class="section-mail__right__input__name">
            <p><a>*</a>Ваш телефон</p>
          </div>
          <div>
            <input class="inputWhite" value="+38 (050) 123-45-67" />
          </div>
        </div>
      </div>
      <div>
        <div class="paddingLeft50px">
          <div class="section-mail__right__input__name">
            <p><a>*</a>Ваш e-mail</p>
          </div>
          <div>
            <input class="inputWhite" value="email@gmail.com" />
          </div>
        </div>
        <div class="paddingLeft50px section-mail__right__button">
          <button class="btn buttonOrange">Принять участие</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.wrapper {
  background-image: url("../assets/image/bg/map_laptop.svg");
  position: absolute;
  z-index: 6;
  left: 250px;
  width: 1300px;
  height: 400px;
}
.section-mail {
  font-family: CeraPro-Light;
  display: flex;
  height: 400px;
  &__left {
    display: flex;
    justify-content: center;
    padding-top: 110px;
    padding-left: 50px;
    background-color: #f2f4f9;
    width: 38%;
    &__text1 {
      font-size: 20px;
      color: #4c8beb;
    }
    &__text2 {
      font-size: 35px;
      font-weight: 800;
    }
    &__text2__margin {
      margin-top: 0px;
    }
  }
  &__right {
    background-color: #4069a7;
    width: 62%;
    display: flex;
    justify-content: center;
    align-items: center;
    &__button {
      margin-top: 50px;
    }
    &__input__name {
      color: #ccc;
      margin-top: 30px;
      a {
        color: #f5841f;
      }
    }
  }
}
@media (max-width: 768px) {
  .wrapper {
    background-image: url("../assets/image/bg/map_laptop.svg");
    position: absolute;
    z-index: 1;
    left: 10px;
    width: 750px;
    height: 400px;
  }
  .section-mail {
    display: flex;
    height: 400px;
    &__left {
      display: flex;
      justify-content: center;
      padding-top: 110px;
      padding-left: 50px;
      background-color: #f2f4f9;
      width: 40%;
      &__text1 {
        font-size: 20px;
        color: #4c8beb;
      }
      &__text2 {
        font-size: 30px;
        font-weight: 800;
      }
      &__text2__margin {
        margin-top: 0px;
      }
    }
    &__right {
      background-color: #4069a7;
      width: 60%;
      display: flex;
      justify-content: center;
      align-items: center;
      &__button {
        margin-top: 50px;
      }
      &__input__name {
        color: #ccc;
        a {
          color: #f5841f;
        }
      }
    }
  }
}
@media (max-width: 450px) {
  .wrapper {
    background-image: url("../assets/image/bg/map_laptop.svg");
    position: absolute;
    z-index: 6;
    left: 0px;
    margin-top: 250px;
    width: 360px;
    height: 400px;
  }
  .paddingLeft50px {
    padding-left: 0px;
  }
  .section-mail {
    display: flex;
    flex-direction: column;
    height: 100%;
    &__left {
      display: flex;
      background-color: #f2f4f9;
      height: 170px;
      width: 100%;
      padding: 50px 110px 0px 0px;
      &__text1 {
        font-size: 20px;
        color: #4c8beb;
        margin: 0px 0px 10px 0px;
      }
      &__text2 {
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 27px;
        margin: 0px 0px 0px 0px;
        text-transform: uppercase;
      }
      &__text2__margin {
        margin-top: 0px;
      }
    }
    &__right {
      background-color: #4069a7;
      height: 570px;
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 100%;
      padding-right: 20px;
      &__button {
        margin-top: 50px;
      }
      &__input__name {
        color: #ccc;
        a {
          color: #f5841f;
        }
      }
    }
  }
}
</style>
