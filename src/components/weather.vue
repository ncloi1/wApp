<template>
    <body>
        <div class="backgroungImg">
            <img src="../assets/background.jpg" alt="фон">
        </div>
        <p class="textCity">Москва</p>
        <div class="startImgText">
            <img class="startImg" src="../assets/weather1.png" alt="ясно"><p class="gradus">5°</p>
        </div>
        <p class="text-weather0">Солнечно</p>
<p class="days">По дням</p><br>
    <div class="container_0">
        <div class="block1" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Сегодня <br>
            <img class="weather1" src="../assets/weather1.png" alt="ясно"><br>
            <p>5° <font class="nightGradus">3°</font></p>
        </div>
        <div class="block2" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Завтра<br>
            <img class="weather2" src="../assets/weather2.png" alt="облачно"><br>
            <p>4° <font class="nightGradus">1°</font></p>
        </div>
        <div class="block3" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Ср 9<br>
            <img class="weather3" src="../assets/weather3.png" alt="дождь"><br>
            <p>2° <font class="nightGradus">-1°</font></p>
        </div>
        <div class="block4" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Чт 10<br>
            <img class="weather4" src="../assets/weather3.png" alt="дождь"><br>
            <p>4° <font class="nightGradus">2°</font></p>
         </div>
        <div class="block5" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Пт 11<br>
            <img class="weather5" src="../assets/weather1.png" alt="ясно"><br>
            <p>7° <font class="nightGradus">4°</font></p>
        </div>
        <div class="block6" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Сб 12<br>
            <img class="weather6" src="../assets/weather1.png" alt="ясно"><br>
            <p>10°  <font class="nightGradus">8°</font></p>
        </div>
        <div class="block7" onmouseover="this.style.background='rgba(255,255,255,0.300)';" onmouseout="this.style.background='transparent';">
            Вс 13<br>
            <img class="weather7" src="../assets/weather5.png" alt="гроза"><br>
            <p>8°  <font class="nightGradus">5°</font></p>
        </div>
    </div>
        <div>
          <p class="textDetails">Подробности</p>
       
        </div>
<br>       
<hr class="hr_1"><hr class="hr_2">
<br>
        <div class="container_1">
          <div class="item_a item_1">По ощущениям
            <br>
          2°</div>
          <div class="item_a item_2">Влажность
            <br>
          73°</div>
          <div class="item_a item_3">Видимость
            <br>
          10 км</div>
          <div class="item_a item_4">Восход
            <br>
            <img class="sunrise" url="sunrise.png" alt="Закат">
          </div>
        </div>
        <br>
        <div class="container_2">
          <div class="item_b item_5">Давление
            <br>
          750.00 мм
        </div>
          <div class="item_b item_6">Ветер
            <br>
          4 м/с
        </div>
          <div class="item_b item_7">
            <br>
          </div>
          <div class="item_b item_8">Закат<br>
            <img class="sunrise" src="sunset.png" alt="Закат">
          </div>
        </div>
    </body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
* {
  margin: 0;
  padding: 0;
  outline: 0;
  box-sizing: border-box;
}
.backgroungImg {
    width: 100%;
    height: 100%;
}
#app {
    width: 100%;
    height: 100%;
    background-repeat: no-repeat;
}
body {
 background: 0;
 color: 0;
 -webkit-font-smoothing: antialiased;
}

body, input, button {
 font-size: 0;
 font-family: 0;
}

button {
 cursor: pointer;
}
/*сверху css reset*/

body {
    background-size: 100%;
    background-repeat: no-repeat;
   }
.textCity {
    text-align: center;
    color: rgb(255, 255, 255);
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;
    color: white;
        margin-right: 0px;
        margin-left: 0px;
        margin-top: -12px;
        margin-bottom: 0px;

}
.startImg {
    height: 80px;
    width: 80px;
    position: absolute;
    top: 30px;
    bottom: 0px;
    left: 45%;
    right: 0px; 
}
.startImgText {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 100px;
}
.gradus {
    text-align: center;
    font-size: 90px;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    position: absolute;
    top: 20px;
    bottom: 0px;
    left: 100px;
    right: 0px; 
}
.days {
    color: white;
    padding-left: 30px;
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
    position: absolute;
    top: 350px;
    bottom: 0px;
    left: 0px;
    right: 0px; 
}

.container_0 {
    display: flex;
    padding-left: 30px;
    padding-right: 30px;
    justify-content: space-between;
    justify-items: flex-start;
    position: absolute;
    top: 400px;
    bottom: 100px;
    left: 0px;
    right: 0px; 
}

.block1 {

    background: rgba(200, 200, 200, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather1 {
    height: 50px;
    width: 50px;
}
.block2 {

    background: rgba(255, 0, 0, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather2 {
    height: 50px;
    width: 50px;
}
.block3 {

    background: rgba(255, 0, 0, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather3 {
    height: 50px;
    width: 50px;
}
.block4 {

    background: rgba(255, 0, 0, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather4 {
    height: 50px;
    width: 50px;
}
.block5 {

    background: rgba(255, 0, 0, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather5 {
    height: 50px;
    width: 50px;
}
.block6 {

    background: rgba(255, 0, 0, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather6 {
    height: 50px;
    width: 50px;
}
.block7 {

    background: rgba(255, 0, 0, 0);
    font-family: Arial, Helvetica, sans-serif;
    border-radius: 5px;
    color: white;
    height: 100px;
    width: 100px;
}
.weather7 {
    height: 50px;
    width: 50px;
}
.textDetails {
    position: absolute;
    top: 600px;
    bottom: 100px;
    left: 0px;
    right: 0px; 
    color: white;
    padding-left: 30px;
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
}
.hr_1 {
    position: absolute;
    top: 650px;
    bottom: 90px;
    left: 0px;
    right: 0px; 
    padding-left: 5px;
    width: 40%;
    height: 0px;
    margin-right: 5px;
    margin-left: 30px;
    margin-top: 0px;
    margin-bottom: 1px;
}
.hr_2 {
    position: absolute;
    top: 650px;
    bottom: 100px;
    left: 0px;
    right: 0px; 
    padding-left: 5px;
    width: 100px;
    height: 0px;
    margin-right: 5px;
    margin-left: 630px;
    margin-top: -2px;
    margin-bottom: 1px;
}
.nightGradus {
    size: 0.5px;
    color: rgb(150, 150, 150);
}
.sunrise {
    width: 10px;
    height: 10px;
}
.sunset {
    width: 20px;
    height: 20px;
}
.container_1 {
    display: flex;
    color: white;
    position: absolute;
    top: 650px;
    bottom: 100px;
    left: 0px;
    right: 0px; 
}
.item_a {
    padding-left: 30px;
    font-size: 10px;
    border: 1px solid rgba(192, 192, 192, 0);
    flex-basis: 200px;
    font-family: Arial, Helvetica, sans-serif;
}
.item_1 {

}
.item_2 {

}
.item_3 {

}
.item_4 {

}
.container_2 {
    display: flex;
    color: white;
    position: absolute;
    top: 700px;
    bottom: 100px;
    left: 0px;
    right: 0px; 
    padding-bottom: 20px;
}
.item_b {
    padding-left: 30px;
    font-size: 10px;
    border: 1px solid rgba(192, 192, 192, 0);
    flex-basis: 200px;
    font-family: Arial, Helvetica, sans-serif;
}
.item_5 {

}
.item_6 {

}
.item_7 {

}
.item_8 {

}

</style>
