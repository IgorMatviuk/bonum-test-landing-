<template>
  <div class="section-webinarInfo">
    <div class="section-webinarInfo__left">
      <div class="section-webinarInfo__left__column0ne">
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/1.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>Как получать</strong> информацию быстрее и как это
              использовать
            </p>
          </div>
        </div>
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/2.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>Как максимально</strong> быстро освоить профессию будущего
              и стать одним из лидеров рынка
            </p>
          </div>
        </div>
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/3.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>С чего начать</strong> обучение, где черпать знания и как
              правильно их структурировать
            </p>
          </div>
        </div>
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/4.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>Как развиваться</strong>, повышать свою прибыль на рынке
            </p>
          </div>
        </div>
      </div>
      <div class="section-webinarInfo__left__columnTwo">
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/5.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>Как вы сможете</strong> выйти на зарплату от $1000 уделяя
              этому несколько часов в день
            </p>
          </div>
        </div>
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/6.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>Если у вас уже</strong> есть бизнес, вы узнаете как
              диверсифицировать его и выйти на совершенно новый уровень
            </p>
          </div>
        </div>
        <div class="section-webinarInfo__left__block">
          <div>
            <img src="../assets/image/icons common/icons_chto/7.svg" />
          </div>
          <div class="section-webinarInfo__left__block__text">
            <p>
              <strong>Как вы можете</strong> стать высокооплачиваемым и
              востребованным специалистом среди компаний со всего мира
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="section-webinarInfo__right">
      <div>
        <div class="section-webinarInfo__right__title">
          <p>ПОЛЕЗНАЯ ИНФОРМАЦИЯ</p>
        </div>
        <div class="section-webinarInfo__right__text">
          <p>ЧТО ВЫ УЗНАЕТЕ</p>
          <p>НА ВЕБИНАРЕ</p>
        </div>
        <div class="section-webinarInfo__right__button">
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
.section-webinarInfo {
  font-family: CeraPro-Light;
  height: 630px;
  display: flex;
  &__left {
    background-color: #ffffff;
    width: 60%;
    display: flex;
    justify-content: center;
    &__column0ne {
      display: flex;
      flex-direction: column;
      margin-top: 40px;
      margin-left: 120px;
    }
    &__columnTwo {
      display: flex;
      flex-direction: column;
      margin-top: 40px;
      margin-left: 40px;
    }
    &__block {
      display: flex;
      flex-flow: row nowrap;
      font-size: 16px;
      line-height: 20px;
      color: #000000;
      img {
        padding: 0px 10px 100px 0px;
      }
      &__text {
        margin-top: 20px;
      }
    }
  }
  &__right {
    background-color: #f2f4f9;
    width: 40%;
    display: flex;
    justify-content: center;
    &__title {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: #75acff;
      margin-top: 150px;
    }
    &__text {
      font-weight: bold;
      font-size: 35px;
      line-height: 50px;
      text-transform: uppercase;
      color: #000000;
    }
    &__button {
      display: flex;
    }
  }
}
@media (max-width: 768px) {
  .section-webinarInfo {
    height: 520px;
    display: flex;
    &__left {
      background-color: #ffffff;
      width: 60%;
      display: flex;
      justify-content: center;
      &__column0ne {
        margin: 25px 0px 0px 50px;
        p {
          margin: 0px 0px 2px 10px;
          font-size: 12px;
        }
        img {
          margin-top: -10px;
        }
      }
      &__columnTwo {
        margin: 25px 0px 0px 30px;
        p {
          margin: 0px 0px 2px 10px;
          font-size: 12px;
        }
      }
      &__block {
        display: flex;
        flex-flow: row nowrap;
        font-size: 16px;
        line-height: 20px;
        color: #000000;
      }
    }
    &__right {
      background-color: #f2f4f9;
      width: 40%;
      display: flex;
      justify-content: center;
      align-items: center;
      &__title {
        font-size: 12px;
        text-transform: uppercase;
        color: #75acff;
        margin: 0px 0px 0px 0px;
      }
      &__text {
        font-size: 30px;
        margin: 10px 0px 0px 0px;
        p {
          margin-top: 0px;
        }
      }
      &__button {
        display: flex;
        padding-top: 20px;
      }
    }
  }
}
@media (max-width: 450px) {
  .section-webinarInfo {
    height: 915px;
    padding-top: 250px;
    display: flex;
    //flex-direction: column;
    flex-direction: column-reverse;
    &__left {
      width: 100%;
      background-color: #ffffff;
      height: 750px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      &__column0ne {
        display: flex;
        flex-direction: column;
        margin: 30px 0px 0px 20px;
      }
      &__columnTwo {
        margin: 0px 0px 30px 20px;
        display: flex;
        flex-direction: column;
      }
      &__block {
        display: flex;
        flex-flow: row nowrap;
        font-size: 16px;
        line-height: 20px;
        color: #000000;
        padding-top: 20px;
      }
    }
    &__right {
      width: 100%;
      //margin-bottom: 0px;
      background-color: #f2f4f9;
      height: 220px;
      display: flex;
      justify-content: center;
      &__title {
        font-weight: bold;
        font-size: 10px;
        line-height: 13px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        margin: 30px 100px 5px 0px;
      }
      &__text {
        font-weight: bold;
        font-size: 20px;
        line-height: 27px;
        text-transform: uppercase;
        color: #000000;
        margin: 10px 0px 18px 0px;
        p {
          margin-top: 0px;
        }
      }
      &__button {
        display: flex;
        margin: 0px 0px 20px 0px;
      }
    }
  }
}
</style>
