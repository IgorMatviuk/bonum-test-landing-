<template>
  <div class="section-source">
    <div class="Rectangle204"></div>
    <div class="section-source__left">
      <div>
        <div class="section-source__left__title">ИСТОЧНИКИ</div>
        <div class="section-source__left__text">
          <div><p>О НАС ПИШУТ САМЫЕ</p></div>
          <div><p>СЕРЬЕЗНЫЕ НОВОСТНЫЕ</p></div>
          <div><p>КАНАЛЫ</p></div>
        </div>
      </div>
    </div>
    <div class="section-source__right">
      <div class="section-source__right__cards">
        <div class="section-source__right__card">
          <img src="../assets/image/istochniki/vesti.png" />
        </div>
        <div class="section-source__right__card">
          <img src="../assets/image/istochniki/rbk.png" />
        </div>
        <div class="section-source__right__card">
          <img src="../assets/image/istochniki/kpua.png" />
        </div>
        <div class="section-source__right__card">
          <img src="../assets/image/istochniki/delo.png" />
        </div>
        <div class="section-source__right__card">
          <img src="../assets/image/istochniki/minfin.png" />
        </div>
        <div class="section-source__right__card">
          <img src="../assets/image/istochniki/ukraine24.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.Rectangle204 {
  background-image: url("../assets/image/1_main/1080x1920/Rectangle 138.svg");
  position: absolute;
  z-index: 3;
  width: 643px;
  height: 383px;
  left: 940px;
  top: 1000px;
}
.section-source {
  display: flex;
  height: 530px;
  &__left {
    width: 50%;
    background: #f2f4f9;
    display: flex;
    justify-content: center;
    align-items: center;
    &__title {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: #75acff;
      font-family: CeraPro-Light;
    }
    &__text {
      font-weight: bold;
      font-size: 35px;
      line-height: 50px;
      text-transform: uppercase;
      color: #000000;
      font-family: CeraPro-Medium;
    }
  }
  &__right {
    width: 50%;
    background: #ffffff;
    position: relative;
    &__cards {
      display: flex;
      flex-flow: column wrap;
      height: 100%;
      align-items: center;
      padding-top: 50px;
      padding-left: 10px;
      position: absolute;
      z-index: 4;
    }
    &__card {
      width: 180px;
      height: 180px;
      background: #f2f4f9;
      margin: 10px 10px 10px 10px;
      display: flex;
      align-items: center;
      img {
        padding-left: 30px;
      }
    }
  }
}
@media (max-width: 768px) {
  .Rectangle204 {
    display: none;
    background-image: url("../assets/image/1_main/1080x1920/Rectangle 138.svg");
    transform: rotate(90deg);
    position: absolute;
    z-index: 3;
    width: 643px;
    height: 383px;
    left: 240px;
    top: 850px;
  }
  .section-source {
    display: flex;
    height: 730px;
    &__left {
      width: 40%;
      display: flex;
      justify-content: center;
      align-items: center;
      &__title {
        font-size: 14px;
      }
      &__text {
        font-size: 20px;
      }
    }
    &__right {
      width: 60%;
      background: #ffffff;
      &__cards {
        display: flex;
        flex-flow: column wrap;
        flex-direction: column;
        height: 100%;
      }
    }
  }
}
@media (max-width: 450px) {
  .Rectangle204 {
    display: none;
    background-image: url("../assets/image/1_main/360x640/ramki/ramka_istochniki.svg")
      no-repeat;
    transform: rotate(90deg);
    position: absolute;
    z-index: 3;
    width: 643px;
    height: 383px;
    left: -110px;
    top: 800px;
  }
  .section-source {
    display: flex;
    flex-direction: column;
    &__left {
      width: 100%;
      height: 220px;
      display: flex;
      justify-content: center;
      align-items: center;
      &__title {
        font-size: 10px;
        margin-left: -40px;
      }
      &__text {
        margin-top: 10px;
        font-size: 20px;
        margin-left: -40px;
        p {
          margin-top: -15px;
        }
      }
    }
    &__right {
      display: flex;
      align-items: center;
      position: relative;
      height: 550px;
      width: 100%;
      background: #ffffff;
      margin-left: 25px;
      &__cards {
        display: flex;
        align-items: center;
        flex-wrap: wrap;
        position: absolute;
        z-index: 4;
      }
      &__card {
        width: 130px;
        height: 130px;
        background: #f2f4f9;
        display: flex;
        align-items: center;
        img {
          padding-left: 10px;
          display: flex;
        }
      }
    }
  }
}
</style>
