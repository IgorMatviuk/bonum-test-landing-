<template>
  <div class="section-time">
    <div class="section-time__Rectangle138"></div>
    <div class="section-time__wrapper"></div>
    <div class="section-time__left">
      <div class="section-time__left__title">
        <p>НЕ ПРОПУСТИТЕ</p>
      </div>
      <div class="section-time__left__text">
        <p>НАШ ВЕБИНАР</p>
        <p>НАЧНЕТСЯ ЧЕРЕЗ:</p>
      </div>
    </div>
    <div class="section-time__right">
      <div class="cards">
        <div class="card">
          <div class="number"><span id="days"></span></div>
          <div class="progress-bar"></div>
          <div class="time">дней</div>
        </div>
        <div class="card">
          <div class="number"><span id="hours"></span></div>
          <div class="progress-bar"></div>
          <div class="time">часов</div>
        </div>
        <div class="card">
          <div class="number"><span id="minutes"></span></div>
          <div class="progress-bar"></div>
          <div class="time">минут</div>
        </div>
        <div class="card">
          <div class="number"><span id="seconds"></span></div>
          <div class="progress-bar"></div>
          <div class="time">секунд</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
const second = 1000,
  minute = second * 60,
  hour = minute * 60,
  day = hour * 24;

let countDown = new Date("Sep 30, 2020 00:00:00").getTime(),
  x = setInterval(function() {
    let now = new Date().getTime(),
      distance = countDown - now;

    (document.getElementById("days").innerText = Math.floor(distance / day)),
      (document.getElementById("hours").innerText = Math.floor(
        (distance % day) / hour
      )),
      (document.getElementById("minutes").innerText = Math.floor(
        (distance % hour) / minute
      )),
      (document.getElementById("seconds").innerText = Math.floor(
        (distance % minute) / second
      ));
  }, second);
export default {};
</script>
<style lang="scss">
.section-time {
  font-family: CeraPro-Light;
  display: flex;
  height: 460px;
  position: relative;
  &__Rectangle138 {
    background-image: url("../assets/image/1_main/1080x1920/Rectangle 204.svg");
    position: absolute;
    z-index: 4;
    width: 917px;
    height: 323px;
    margin: 45px 0px 0px 640px;
  }
  &__wrapper {
    background-image: url("../assets/image/bg/map_laptop.svg");
    bottom: 0px;
    right: 300px;
    position: absolute;
    z-index: 3;
    width: 1200px;
    height: 100%;
  }
  &__left {
    width: 35%;
    background: #f2f4f9;
    z-index: 2;
    display: flex;
    flex-direction: column;
    justify-content: center;
    &__title {
      font-weight: bold;
      font-size: 14px;
      line-height: 18px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: #75acff;
      padding-left: 150px;
    }
    &__text {
      font-weight: bold;
      font-size: 35px;
      line-height: 50px;
      text-transform: uppercase;
      color: #000000;
      padding-left: 150px;
    }
  }
  &__right {
    width: 65%;
    background: #4069a7;
    position: relative;
    .cards {
      display: flex;
      align-items: center;
      padding-top: 80px;
      padding: 90px 0px 0px 0px;
      z-index: 6;
      position: absolute;
    }
    .card {
      width: 190px;
      height: 240px;
      background: #ffffff;
      display: flex;
      align-items: center;
      flex-direction: column;
      margin: 0px 0px 0px 50px;
      .number {
        margin-top: 40px;
        font-style: normal;
        font-weight: 500;
        font-size: 70px;
        line-height: 88px;
        display: flex;
        align-items: center;
        text-align: center;
        color: #1d2b46;
      }
      .progress-bar {
        display: flex;
        width: 80px;
        height: 2px;
        background: #f2f4f9;
      }
      .time {
        margin-top: 30px;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 15px;
        display: flex;
        align-items: center;
        letter-spacing: 0.3em;
        color: #f5841f;
      }
    }
  }
}
@media (max-width: 768px) {
  .section-time {
    display: flex;
    height: 626px;
    position: relative;
    &__Rectangle138 {
      background-image: url("../assets/image/1_main/768x960 gorizont/Rectangle 100.svg")
        no-repeat;
      position: absolute;
      z-index: 5;
      width: 917px;
      height: 323px;
      margin: 45px 0px 0px 290px;
    }
    &__left {
      width: 40%;
      z-index: 3;
      display: flex;
      flex-direction: column;
      position: relative;
      &__title {
        font-size: 12px;
        padding: 0px 0px 0px 100px;
      }
      &__text {
        font-size: 25px;
        padding: 0px 0px 0px 100px;
        p {
          margin: 0px 0px -15px 0px;
        }
      }
    }
    &__right {
      width: 60%;
      background: #4069a7;
      z-index: 4;
      position: relative;
      .cards {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        padding-top: 0px 0px 0px 0px;
        margin: -30px 0px 0px 0px;
        flex-wrap: wrap;
        z-index: 6;
        position: absolute;
      }
      .card {
        width: 190px;
        height: 240px;
        margin: 0px 10px 10px 0px;
      }
    }
  }
}
@media (max-width: 450px) {
  .section-time {
    display: flex;
    flex-direction: column;
    height: 660px;
    position: relative;
    &__Rectangle138 {
      display: none;
      background-image: url("../assets/image/1_main/360x640/ramki/ramka_istochniki.svg")
        no-repeat;
      transform: rotate(90deg);
      position: absolute;
      z-index: 6;
      width: 918px;
      height: 323px;
      right: -280px;
    }
    &__left {
      width: 100%;
      height: 180px;
      z-index: 3;
      display: flex;
      flex-direction: column;
      &__title {
        font-size: 12px;
        padding: 0px 0px 0px 30px;
      }
      &__text {
        font-size: 25px;
        padding: 0px 0px 0px 30px;
        p {
          margin: 0px 0px -15px 0px;
        }
      }
    }
    &__right {
      display: flex;
      width: 100%;
      height: 480px;
      background: #4069a7;
      z-index: 4;
      .cards {
        display: flex;
        flex-flow: column wrap;
        flex-direction: row;
        padding-left: 25px;
        padding-top: 50px;
      }
      .card {
        display: flex;
        width: 150px;
        height: 200px;
        margin: 0px 10px 5px 0px;
      }
    }
  }
}
</style>
