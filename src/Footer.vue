<template>
<footer>
  <div class="contant">
    <div class="bottomBar">
      <h4>Адрес:</h4>
      <a href="#">г.Сочи, ул, Навагинская, д.14</a>
      <h4>Телефон:</h4>
      <a href="#">+7(862)264-45-55</a><br>
      <a href="#">+7(800)100-57-58</a>
      <h4>E-mail:</h4>
      <a href="#">info@aviatourne.ru</a>
    </div>
    <div class="bottomBar">
      <h4>Партнеры:</h4>
      <img src="./assets/-e-iata@3x.png" class="main">
      <img src="./assets/-e-tkp@3x.png" class="main">
      <img src="./assets/-e-ural@3x.png" class="main">
    </div>
    <div class="bottomBar">
      <h4>Полезные ссылки</h4>
      <a href="#">Авиабилеты</a><br>
      <a href="#">Ж/Д билеты</a><br>
      <a href="#">Гостиницы</a><br>
      <a href="#">Трансфер</a><br>
      <a href="#">Партнерам</a><br>
    </div>
    <div class="bottomBar">
      <img src="./assets/-e-uni_logo@3x.png" class="uni">
      <div class="items">
      <img src="./assets/google-play@3x.png" class="connect">
      <img src="./assets/app-store@3x.png" class="connect">
      <img src="./assets/external-link@3x.png" class="connect">
      </div>
      <p>Uniticket.aero – это продажа<br>
      билетов любых перевозчиков<br>
      сразу на все направления<br>
      в одном интерфейсе.</p>
    </div>
    <div class="bottomBar">
      <img src="./assets/-e-Aviatourne_logo@3x.png" class="logo">
      <div class="items">
      <img src="./assets/black-back-closed-envelope-shape@3x.png" class="connect">
      <img src="./assets/telephone-handle-silhouette@3x.png" class="connect">
      <img src="./assets/maps-and-flags@3x.png" class="connect">
      </div>
      <p>&copy; АвиаТурне 2009 — 2019</p><br>
      <br>
      <p> Мы не штампуем - мы создаем<br> IT's WEB</p>
    </div>
 </div>
</footer>
</template>

<script>
export default {
}
</script>

<style lang="sass?indentedSyntax=true">
footer
    background-image: url(./assets/3.png)
    background-size: cover
    padding:
      top: 68px
      bottom: 92px
.contant
  position: relative
  left: 13%
  display: flex
  font-family: SegoeUI
  justify-content: space-between
  max-width: 1055px
@media screen and (max-width: 1280px)
  .contant
    left: 130px
    max-width: 988px
.bottomBar
  display: flex
  flex-direction: column
  max-width: 196px
.bottomBar h4
  color: white
  font-size: 14px
  font-weight: 600
  margin-bottom: 3%
.bottomBar a
  font-size: 11px
  line-height: 1.94
  color: #c5c5c5
.bottomBar:nth-child(3) a
  padding:
    top: 13px
.bottomBar p
  font-size: 11px
  color: #c5c5c5
  line-height: 1.94
.bottomBar img
  position: relative
  top: 10px
  left: 0px
  padding:
    top: 7%
    bottom: 7%
.bottomBar .main
  display: flex
  max-width: 53px
.uni
  margin-top: 0%
  max-width: 27px
.items
  display: flex
  flex-direction: row
  justify-content: space-between
  max-width: 110px
.connect
  margin:
      top: 9%
      bottom: 9%
  max-width: 17px
  max-height: 17px
.logo
  margin-top: 0%
  max-width: 41px
</style>
