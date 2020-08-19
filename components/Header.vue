<template>
  <div class="header">
    <!--mob-menu-->
    <div class="hamburger-menu">
      <input id="menu__toggle" type="checkbox" />
      <label class="menu__btn" for="menu__toggle">
        <span></span>
      </label>
      <ul class="menu__box">
        <li><a class="menu__item" href="#">О вебинаре</a></li>
        <li><a class="menu__item" href="#">Про спикера</a></li>
        <li><a class="menu__item" href="#">Узнать больше</a></li>
      </ul>
    </div>
    <!--/-->

    <div class="header__logo">
      <img :src="require(`~/assets/image/logo.svg`)" alt="logo" />
    </div>
    <div class="header__menu-center">
      <div class="header__menu-center__date">
        <p>20.05.2020</p>
      </div>
      <div class="header__menu-center__text-1">
        <p>вебинар</p>
      </div>
      <div class="header__menu-center__text-2">
        <p>"КАК СОЗДАВАТЬ ПАССИВНЫЙ ДОХОД?"</p>
      </div>
    </div>
    <div class="header__menu-right">
      <div class="header__menu-right__number">
        <img :src="require(`~/assets/image/icons common/call.svg`)" />
        <p>0 800 <strong>500 222</strong></p>
      </div>
      <div class="header__menu-right__button">
        <button class="btn buttonBlue">УЧАСТВОВАТЬ</button>
      </div>
    </div>
    <div class="call">
      <div>
        <img :src="require(`~/assets/image/icons common/call.svg`)" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.call {
  display: none;
}
.hamburger-menu {
  display: none;
}
.header {
  font-family: CeraPro-Light;
  display: flex;
  height: 45px;
  width: 100%;
  background-color: transparent;
  position: fixed;
  justify-content: space-evenly;
  z-index: 9;
  margin-top: 25px;
  &__logo {
    display: flex;
  }
  &__menu-center {
    display: flex;
    flex-direction: row;
    p {
      margin: 10px 50px 0px -40px;
    }
    &__date {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      display: flex;
      color: #f5841f;
    }
    &__text-1 {
      display: flex;
      color: #ffffff;
      font-size: 14px;
      font-weight: bold;
      padding-right: 10px;
    }
    &__text-2 {
      display: flex;
      color: #75acff;
      font-weight: bold;
      padding-right: 10px;
    }
  }
  &__menu-right {
    display: flex;
    flex-direction: row;
    &__number {
      display: flex;
      flex-direction: row;
      color: #ffffff;
      font-weight: normal;
      font-size: 16px;
      line-height: 20px;
      align-items: center;
      padding-right: 20px;
      img {
        padding-right: 10px;
      }
    }
    &__button {
      display: flex;
      align-items: center;
    }
  }
}
@media (max-width: 768px) {
  .call {
    display: none;
  }
  .hamburger-menu {
    display: none;
  }
  .header {
    display: flex;
    height: 45px;
    width: 100%;
    background-color: transparent;
    position: fixed;
    justify-content: space-around;
    z-index: 9;
    margin-top: 25px;
    &__logo {
      display: flex;
    }
    &__menu-center {
      display: none;
      flex-direction: row;
      p {
        margin: 10px 50px 0px -40px;
      }
      &__date {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        display: flex;
        color: #f5841f;
      }
      &__text-1 {
        display: flex;
        color: #ffffff;
        font-size: 14px;
        font-weight: bold;
        padding-right: 10px;
      }
      &__text-2 {
        display: flex;
        color: #75acff;
        font-weight: bold;
        padding-right: 10px;
      }
    }
    &__menu-right {
      display: flex;
      flex-direction: row;
      &__number {
        display: flex;
        flex-direction: row;
        color: #ffffff;
        font-weight: normal;
        font-size: 16px;
        line-height: 20px;
        align-items: center;
        padding-right: 20px;
        img {
          padding-right: 10px;
        }
      }
      &__button {
        display: flex;
        align-items: center;
      }
    }
  }
}
@media (max-width: 450px) {
  .call {
    display: flex;
    margin: -5px 0px 0px 5px;
    width: 28px;
    height: 28px;
    background: #75acff;
    justify-content: center;
    border-radius: 50%;
    img {
      margin-top: 10px;
    }
  }
  .hamburger-menu {
    display: flex;
    position: relative;
  }
  /* скрываем чекбокс */
  #menu__toggle {
    opacity: 0;
  }
  /* стилизуем кнопку */
  .menu__btn {
    display: flex; /* используем flex для центрирования содержимого */
    align-items: center; /* центрируем содержимое кнопки */
    position: fixed;
    top: 24px;
    left: 20px;
    width: 26px;
    height: 26px;
    cursor: pointer;
    z-index: 1;
  }
  /* добавляем "гамбургер" */
  .menu__btn > span,
  .menu__btn > span::before,
  .menu__btn > span::after {
    display: block;
    position: absolute;
    width: 100%;
    height: 2px;
    background-color: #ffffff;
  }
  .menu__btn > span::before {
    content: "";
    top: -8px;
  }
  .menu__btn > span::after {
    content: "";
    top: 8px;
  }
  /* контейнер меню */
  .menu__box {
    display: block;
    position: fixed;
    visibility: hidden;
    top: 0;
    left: -100%;
    width: 300px;
    height: 100%;
    margin: 0;
    padding: 80px 0;
    list-style: none;
    text-align: center;
    background-color: #eceff1;
    box-shadow: 1px 0px 6px rgba(0, 0, 0, 0.2);
  }
  /* элементы меню */
  .menu__item {
    display: block;
    padding: 12px 24px;
    color: #333;
    font-family: "Roboto", sans-serif;
    font-size: 20px;
    font-weight: 600;
    text-decoration: none;
  }
  .menu__item:hover {
    background-color: #cfd8dc;
  }
  #menu__toggle:checked ~ .menu__btn > span {
    transform: rotate(45deg);
  }
  #menu__toggle:checked ~ .menu__btn > span::before {
    top: 0;
    transform: rotate(0);
  }
  #menu__toggle:checked ~ .menu__btn > span::after {
    top: 0;
    transform: rotate(90deg);
  }
  #menu__toggle:checked ~ .menu__box {
    visibility: visible;
    left: 0;
  }
  .header {
    display: flex;
    height: 45px;
    width: 100%;
    background-color: transparent;
    position: fixed;
    justify-content: space-evenly;
    z-index: 9;
    margin-top: 25px;
    &__logo {
      display: flex;
      margin: 0px 0px 22px 0px;
    }
    &__menu-center {
      display: none;
      flex-direction: row;
      p {
        margin: 10px 50px 0px -40px;
      }
      &__date {
        font-weight: bold;
        font-size: 14px;
        line-height: 18px;
        display: flex;
        color: #f5841f;
      }
      &__text-1 {
        display: flex;
        color: #ffffff;
        font-size: 14px;
        font-weight: bold;
        padding-right: 10px;
      }
      &__text-2 {
        display: flex;
        color: #75acff;
        font-weight: bold;
        padding-right: 10px;
      }
    }
    &__menu-right {
      display: none;
      flex-direction: row;
      &__number {
        display: flex;
        flex-direction: row;
        color: #ffffff;
        font-weight: normal;
        font-size: 16px;
        line-height: 20px;
        align-items: center;
        padding-right: 20px;
        img {
          padding-right: 10px;
        }
      }
      &__button {
        display: none;
        align-items: center;
      }
    }
  }
}
</style>
