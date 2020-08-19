<template>
  <div class="section-registration">
    <div class="section-registration__left">
      <div>
        <div class="section-registration__left__wrapper"></div>
      </div>
      <div class="section-registration__left__card">
        <div class="section-registration__left__card__title">
          <p>КАК ВАМ ДЕЙСТВОВАТЬ</p>
        </div>
        <div class="section-registration__left__card__text ">
          <p>МАСТЕР-КЛАСС ПО</p>
          <p>ИНВЕСТИРОВАНИЮ</p>
        </div>
        <div>
          <p class="section-registration__left__card__input__name">
            <a>*</a>Ваше имя
          </p>
          <input class="inputWhite" value="Александр" />
        </div>
        <div class="marginTop-5">
          <p class="section-registration__left__card__input__name">
            <a>*</a>Ваш телефон
          </p>
          <input class="inputWhite" value="+38 (050) 123-45-67" />
        </div>
        <div class="marginTop-5">
          <p class="section-registration__left__card__input__name">
            <a>*</a>email@gmail.com
          </p>
          <input class="inputWhite" value="email@gmail.com" />
        </div>
        <div class="section-registration__left__card__button marginTop-5">
          <button class=" btn section-registration__left__card__button-reg">
            Зарегистрироваться
          </button>
        </div>
      </div>
    </div>
    <div class="section-registration__right"></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section-registration {
  font-family: CeraPro-Light;
  height: 650px;
  display: flex;
  position: relative;
  &__left {
    width: 60%;
    background-color: #1d2b46;
    display: flex;
    flex-direction: column;
    position: relative;
    &__wrapper {
      background-image: url("../assets/image/bg/Blueprint.svg");
      right: 300px;
      position: absolute;
      z-index: 2;
      height: 710px;
      width: 900px;
    }
    &__card {
      display: flex;
      flex-direction: column;
      padding: 50px 0px 0px 350px;
      position: absolute;
      z-index: 3;
      &__title {
        padding-top: 80px;
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
      }
      &__button {
        padding-top: 30px;
      }
      &__button-reg {
        outline: none;
        border: 0px;
        box-sizing: none;
        background-color: transparent;
        font-style: normal;
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        text-align: center;
        letter-spacing: 0.07em;
        color: #ffffff;
      }
      &__input__name {
        color: #ccc;

        padding-top: 6px;
        a {
          color: #f5841f;
        }
      }
    }
  }
  &__right {
    width: 40%;
    background-color: #4069a7;
  }
}
@media (max-width: 768px) {
  .section-registration {
    height: 650px;
    display: flex;
    position: relative;
    &__left {
      width: 80%;
      &__card {
        padding: 50px 0px 0px 80px;
      }
    }
    &__right {
      width: 20%;
    }
  }
}
@media (max-width: 500px) {
  .section-registration {
    height: 950px;
    display: flex;
    position: relative;
    &__left {
      padding-top: 230px;
      width: 100%;
      background-color: #1d2b46;
      display: flex;
      flex-direction: column;
      position: relative;
      &__wrapper {
        background-image: url("../assets/image/bg/Blueprint.svg");
        position: absolute;
        z-index: 2;
        width: 100%;
        height: 910px;
      }
      &__card {
        display: flex;
        flex-direction: column;
        padding: 200px 0px 0px 20px;
        position: absolute;
        z-index: 3;
        &__title {
          font-weight: bold;
          font-size: 10px;
          line-height: 13px;
          letter-spacing: 0.4em;
          text-transform: uppercase;
          color: #75acff;
          margin-bottom: 15px;
        }
        &__text {
          font-weight: bold;
          font-size: 20px;
          line-height: 27px;
          text-transform: uppercase;
          color: #ffffff;
          padding-bottom: 15px;
          p {
            margin-bottom: 0px;
          }
        }
        &__button {
          padding-top: 30px;
        }
        &__input__name {
          color: #ccc;
          margin-bottom: -10px;
          padding-top: 6px;
          a {
            color: #f5841f;
          }
        }
      }
    }
    &__right {
      background-color: #4069a7;
      display: none;
    }
  }
}
</style>
