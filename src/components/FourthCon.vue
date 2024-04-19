<template>
  <div class="con flex flex-col items-center py-28 space-y-14">
    <div
      class="flex flex-col space-y-8 lg:space-y-0 lg:flex-row items-end max-w-md lg:max-w-6xl space-x-8"
    >
      <div class="card flex flex-col items-center space-y-4 p-5 justify-center">
        <span class="mainText"> Pro </span>
        <span class="priceText">30$</span>
        <span class="descriptionText"
          >Простое и основное приглашение, которое содержит минимальную
          информацию о дате, времени и месте</span
        >
      </div>

      <div class="card flex flex-col items-center space-y-4 p-5 justify-center">
        <span class="mainText"> Basic </span>
        <span class="priceText">10$</span>
        <span class="descriptionText"
          >Простое и основное приглашение, которое содержит минимальную
          информацию о дате, времени и месте</span
        >
      </div>

      <div class="card flex flex-col items-center space-y-4 p-5 justify-center">
        <span class="mainText"> Electronic </span>
        <span class="priceText">20$</span>
        <span class="descriptionText"
          >Простое и основное приглашение, которое содержит минимальную
          информацию о дате, времени и месте</span
        >
      </div>
    </div>
    <a
      href="https://docs.google.com/forms/d/e/1FAIpQLSfVKIV2GiiJfubXACl8BTjLdpeCYo1FeQ3dDowLPQKMwtxjjQ/viewform"
    >
      <button class="greenButton">ЗАКАЗАТЬ</button></a
    >
  </div>
</template>

<style scoped>
.con {
  background: url("../assets/fourthConImg.svg");
}
.card {
  width: 397px;
  height: 349px;
  border-radius: 15px;
  text-align: center;
  background: #edecec;
}

.mainText {
  font-family: Inter;
  font-size: 45px;
  font-style: italic;
  font-weight: 400;
  line-height: 54.46px;
}

.priceText {
  font-family: Inter;
  font-size: 60px;
  font-weight: 300;
  line-height: 72.61px;
  text-align: left;
  color: #facd59;
}
.descriptionText {
  font-family: Inter;
  font-size: 20px;
  font-style: italic;
  font-weight: 400;
  line-height: 24.2px;
  text-align: center;
}
</style>
