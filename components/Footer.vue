<template>
  <footer class="footer">
    <div class="container">
      <div class="footer__block1">
        <div class="footer__block1__img">
          <img src="../assets/image/footer-logo 1.svg" />
        </div>
        <div class="footer__block1__text">
          <p>Политика конфиденциальности</p>
          <p>Важная информация</p>
        </div>
      </div>
      <div class="footer__block2">
        <div class="footer__block2__menu">
          <ul>
            <li>О компании</li>
            <li>Обучение</li>
            <li>Инвестиции</li>
            <li>Офисы</li>
          </ul>
        </div>
        <div class="footer__block2__image">
          <div class="footer__block2__image__block">
            <img src="../assets/image/icons common/icons_social/Facebook.svg" />
          </div>
          <div class="footer__block2__image__block">
            <img src="../assets/image/icons common/icons_social/telegram.svg" />
          </div>
          <div class="footer__block2__image__block">
            <img
              src="../assets/image/icons common/icons_social/Instagram.svg"
            />
          </div>
          <div class="footer__block2__image__block">
            <img src="../assets/image/icons common/icons_social/Youtube.svg" />
          </div>
        </div>
      </div>
      <div class="footer__block3">
        <div class="footer__block3__phoneNumber">
          0 800 <strong>500 222</strong>
        </div>
        <div class="footer__block3__bonum__logo">
          <div>Разработано в студии</div>
          <div>
            <img src="../assets/image/bonum.svg" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
.footer {
  background: #1d2b46;
  height: 200px;
  width: 100%;
  font-family: CeraPro-Light;
  .container {
    padding-top: 30px;
    display: flex;
    justify-content: space-evenly;
  }
  &__block1 {
    &__img {
      display: flex;
      margin: 0px 0px 0px 80px;
    }
    &__text {
      display: flex;
      font-weight: normal;
      font-size: 11px;
      line-height: 14px;
      text-decoration-line: underline;
      color: #99a2b5;
      padding-top: 50px;
    }
    &__text:hover {
      color: #f5841f;
    }
  }
  &__block2 {
    &__menu {
      color: white;
      ul {
        display: flex;
        list-style: none;
      }
      li {
        margin: 10px;
      }
      li:hover {
        color: #f5841f;
      }
    }
    &__image {
      display: flex;
      justify-content: space-evenly;
      &__block {
        margin-top: 25px;
        height: 40px;
        width: 40px;
        border-radius: 50%;
        background-color: #4069a7;
        align-items: center;
        display: flex;
        justify-content: center;
      }
      &__block:hover {
        background-color: #75acff;
      }
    }
  }
  &__block3 {
    &__phoneNumber {
      color: #ffffff;
    }
    &__bonum__logo {
      display: flex;
      padding-top: 80px;
      font-style: normal;
      font-weight: normal;
      font-size: 10px;
      line-height: 13px;
      color: #99a2b5;
      img {
        padding-left: 5px;
      }
    }
  }
}
@media (max-width: 768px) {
  .footer {
    background: #1d2b46;
    height: 140px;
    width: 100%;
    .container {
      padding-top: 10px;
      display: flex;
      justify-content: space-evenly;
    }
    &__block1 {
      p {
        padding-left: 5px;
      }
      &__img {
        display: flex;
        margin: 0px 0px 0px 60px;
      }
      &__text {
        position: absolute;
        z-index: 4;
        display: flex;
        font-weight: normal;
        font-size: 11px;
        line-height: 14px;
        text-decoration-line: underline;
        color: #99a2b5;
        padding-top: 0px;
        margin: 250px 0px 0px 30px;
        white-space: nowrap;
        position: absolute;
      }
      &__text:hover {
        color: #f5841f;
      }
    }
    &__block2 {
      &__menu {
        margin: 0px 0px 0px 40px;
        display: flex;
        color: white;
        ul {
          display: flex;
          list-style: none;
          white-space: nowrap;
        }
        li {
          margin: 10px 4px 0px 4px;
        }
        li:hover {
          color: #f5841f;
        }
      }
      &__image {
        margin-left: 50px;
        display: flex;
        justify-content: center;
        &__block {
          margin: 30px 5px 0px 5px;
          height: 40px;
          width: 40px;
          border-radius: 50%;
          background-color: #4069a7;
          align-items: center;
          display: flex;
          justify-content: center;
        }
        &__block:hover {
          background-color: #75acff;
        }
      }
    }
    &__block3 {
      &__phoneNumber {
        color: #ffffff;
        margin: 30px 0px 0px 30px;
      }
      &__bonum__logo {
        display: flex;
        margin: 10px 20px 0px 50px;
        font-style: normal;
        font-weight: normal;
        font-size: 10px;
        line-height: 13px;
        color: #99a2b5;
        white-space: nowrap;
        img {
          padding-left: 5px;
        }
      }
    }
  }
}
@media (max-width: 450px) {
  .footer {
    display: flex;
    justify-content: center;
    background: #1d2b46;
    height: 500px;
    width: 100%;
    .container {
      padding-top: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    &__block1 {
      &__img {
        margin-bottom: 30px;
        margin-right: 25px;
        display: flex;
        flex-direction: column;
      }
      &__text {
        flex-direction: column;
        align-items: center;
        display: flex;
        font-weight: normal;
        font-size: 11px;
        line-height: 14px;
        text-decoration-line: underline;
        color: #99a2b5;
        padding-top: 50px;
      }
      &__text:hover {
        color: #f5841f;
      }
    }
    &__block2 {
      &__menu {
        margin-top: 10px;
        display: flex;
        color: white;
        ul {
          display: flex;
          list-style: none;
          flex-direction: column;
          align-items: center;
          margin-left: 30px;
        }
        li {
          margin: 10px;
        }
        li:hover {
          color: #f5841f;
        }
      }
      &__image {
        display: flex;
        justify-content: space-evenly;
        margin-right: 6px;
        &__block {
          margin-top: 25px;
          height: 40px;
          width: 40px;
          border-radius: 50%;
          background-color: #4069a7;
          align-items: center;
          display: flex;
          justify-content: center;
          margin: 30px 10px 0px 10px;
        }
        &__block:hover {
          background-color: #75acff;
        }
      }
    }
    &__block3 {
      display: flex;
      flex-direction: column;
      align-items: center;
      &__phoneNumber {
        padding-top: 0px;

        display: flex;
        color: #ffffff;
        strong {
          padding-left: 5px;
        }
      }
      &__bonum__logo {
        display: flex;
        font-style: normal;
        font-weight: normal;
        font-size: 10px;
        line-height: 13px;
        color: #99a2b5;
        padding: 50px 0px 0px 0px;
        img {
          padding-left: 5px;
        }
      }
    }
  }
}
</style>
