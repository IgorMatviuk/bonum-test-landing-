<template>
  <div class="section-expectation">
    <div class="section-expectation__left">
      <div class="section-expectation__left__title">
        <p>ЭТО ИМЕННО ВЫ !</p>
      </div>
      <div class="section-expectation__left__text">
        <p>КОГО МЫ ЖДЕМ НА ВЕБИНАРЕ?</p>
      </div>
      <div class="section-expectation__left__button">
        <button class="btn buttonOrange">Принять участие</button>
      </div>
    </div>
    <div class="section-expectation__right">
      <div class="section-expectation__right__cards">
        <div class="section-expectation__right__ectangle204"></div>
        <div class="section-expectation__right__card">
          <div class="section-expectation__right__card__number">01</div>
          <div class="section-expectation__right__card__hr"></div>
          <div class="section-expectation__right__card__text">
            <p>Амбициозных людей,</p>
            <p>которые хотят сменить вид</p>
            <p>деятельности и освоить</p>
            <p>новую профессию с полной</p>
            <p>свободой действий и</p>
            <p>ежемесячным доходом</p>
            <p>гораздо выше среднего</p>
          </div>
          <div class="section-expectation__right__card__plus">+</div>
        </div>
        <div class="section-expectation__right__card">
          <div class="section-expectation__right__card__number">02</div>
          <div class="section-expectation__right__card__hr"></div>
          <div class="section-expectation__right__card__text">
            <p>Людей, которые ищут</p>
            <p>варианты дополнительного</p>
            <p>источника заработка</p>
          </div>
          <div class="section-expectation__right__card__plus">+</div>
        </div>
        <div class="section-expectation__right__card">
          <div class="section-expectation__right__card__number">03</div>
          <div class="section-expectation__right__card__hr"></div>
          <div class="section-expectation__right__card__text">
            <p>Предпринимателей, которые</p>
            <p>имеют опыт ведения бизнеса</p>
            <p>и которые ищут варианты</p>
            <p>получения пассивного</p>
            <p>дохода</p>
          </div>
          <div class="section-expectation__right__card__plus">+</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.section-expectation {
  display: flex;
  height: 550px;
  font-family: CeraPro-Light;
  &__left {
    background-color: #ffffff;
    width: 40%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 400px;
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
      color: #000000;
    }
    &__button {
      display: flex;
    }
  }
  &__right {
    background-color: #f2f4f9;
    width: 60%;
    display: flex;
    &__cards {
      display: flex;
      justify-content: space-evenly;
      align-items: center;
      position: relative;
      padding-left: 50px;
    }
    &__card {
      display: flex;
      align-items: center;
      flex-direction: column;
      width: 280px;
      height: 330px;
      background: #4069a7;
      margin: 0px 10px 0px 10px;
      &__number {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        text-align: right;
        letter-spacing: 0.1em;
        color: #f5841f;
        padding-left: 175px;
        margin: 20px 0px 30px 0px;
      }
      &__hr {
        display: flex;
        border: none;
        background-color: #75acff;
        width: 200px;
        height: 3px;
      }
      &__text {
        font-weight: normal;
        font-size: 14px;
        line-height: 18px;
        color: #fafbfd;
        margin: 20px 0px 30px 0px;
        p {
          margin-bottom: 0px;
        }
      }
      &__plus {
        font-weight: 500;
        font-size: 24px;
        line-height: 30px;
        color: #75acff;
        display: flex;
        margin-right: 170px;
      }
    }
  }
}
@media (max-width: 1650px) {
  .section-expectation {
    &__left {
      padding-left: 100px;
    }
    &__right {
      &__cards {
        padding-left: 10px;
      }
    }
  }
}
@media (max-width: 768px) {
  .section-expectation {
    display: flex;
    flex-direction: column;
    &__left {
      background-color: #ffffff;
      height: 340px;
      width: 100%;
      display: flex;
      margin: 0px 0px 0px 50px;
      &__title {
        font-weight: bold;
        font-size: 12px;
        line-height: 18px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
      }
      &__text {
        font-weight: bold;
        font-size: 30px;
        line-height: 50px;
        text-transform: uppercase;
        color: #000000;
        p {
          margin: 0px 0px 0px 5px;
        }
      }
      &__button {
        display: flex;
      }
    }
    &__right {
      padding-left: 150px;
      background-color: #f2f4f9;
      height: 340px;
      display: flex;
      justify-content: center;
      &__cards {
        display: flex;
        justify-content: space-evenly;
        margin: 0px 0px 0px 150px;
      }
      &__card {
        display: flex;
        align-items: center;
        flex-direction: column;
        width: 200px;
        height: 270px;
        background: #4069a7;
        margin: 0px 10px 0px 5px;
        &__number {
          font-weight: bold;
          font-size: 14px;
          line-height: 18px;
          text-align: right;
          letter-spacing: 0.1em;
          color: #f5841f;
          padding-left: 175px;
          margin: 20px 0px 20px 0px;
        }
        &__hr {
          display: flex;
          border: none;
          background-color: #75acff;
          width: 200px;
          height: 3px;
        }
        &__text {
          font-weight: normal;
          font-size: 14px;
          line-height: 18px;
          color: #fafbfd;
          margin: 5px 10px 10px 10px;
          p {
            margin-bottom: 0px;
          }
        }
        &__plus {
          font-weight: 500;
          font-size: 24px;
          line-height: 30px;
          color: #75acff;
          display: flex;
          margin-right: 170px;
        }
      }
    }
  }
}
@media (max-width: 450px) {
  .section-expectation {
    display: flex;
    height: 1750px;
    width: 100%;
    margin-bottom: 150px;
    &__left {
      margin-left: -80px;
      background-color: #ffffff;
      height: 250px;
      width: 100%;
      display: flex;
      flex-direction: column;

      &__title {
        font-weight: bold;
        font-size: 10px;
        line-height: 13px;
        letter-spacing: 0.4em;
        text-transform: uppercase;
        color: #75acff;
        margin-left: 10px;
      }
      &__text {
        font-weight: bold;
        font-size: 20px;
        line-height: 27px;
        text-transform: uppercase;
        color: #000000;
        margin-top: 15px;
      }
      &__button {
        display: flex;
        margin-top: 30px;
      }
    }
    &__right {
      background-color: #f2f4f9;
      height: 1150px;
      width: 100%;
      display: flex;
      &__cards {
        display: flex;
        position: relative;
        flex-direction: column;
        margin: 0px 190px 0px 0px;
      }
      &__card {
        display: flex;
        align-items: center;
        flex-direction: column;
        width: 280px;
        height: 330px;
        background: #4069a7;
        margin: 0px 0px 35px 10px;
        &__number {
          font-weight: bold;
          font-size: 14px;
          line-height: 18px;
          text-align: right;
          letter-spacing: 0.1em;
          color: #f5841f;
          padding-left: 175px;
          margin: 20px 0px 30px 0px;
        }
        &__hr {
          display: flex;
          border: none;
          background-color: #75acff;
          width: 200px;
          height: 3px;
        }
        &__text {
          font-weight: normal;
          font-size: 14px;
          line-height: 18px;
          color: #fafbfd;
          margin: 20px 0px 30px 0px;
          p {
            margin-bottom: 0px;
          }
        }
        &__plus {
          font-weight: 500;
          font-size: 24px;
          line-height: 30px;
          color: #75acff;
          display: flex;
          margin-right: 170px;
        }
      }
    }
  }
}
</style>
