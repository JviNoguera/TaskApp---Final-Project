<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="background">
    <div class="starsec"></div>
    <div class="starthird"></div>
    <div class="starfourth"></div>
    <div class="starfifth"></div>
    <section class="error">
      <div class="error__content">
        <div class="error__message message">
          <h1 class="message__title">Page Not Found</h1>
          <p class="message__text">Sorry, we couldn't find the page you were looking for.</p>
        </div>
        <div class="error__nav e-nav">
          <RouterLink to="/auth" class="e-nav__link">Go to Login</RouterLink>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  -webkit-text-size-adjust: none;
}

.background {
  height: 100vh;
  width: 100vw;
  background-color: #181828;
  overflow: hidden;
  position: relative;
}


.starsec, .starthird, .starfourth, .starfifth {
  position: absolute;
  background: transparent;
}

.starsec {
  width: 2px;
  height: 3px;
  box-shadow: 571px 173px #00BCD4, 1732px 143px #00BCD4, 1745px 454px #FF5722, 234px 784px #00BCD4, 1793px 1123px #FF9800, 1076px 504px #03A9F4, 633px 601px #FF5722, 350px 630px #FFEB3B, 1164px 782px #00BCD4, 76px 690px #3F51B5, 1825px 701px #CDDC39, 1646px 578px #FFEB3B, 544px 293px #2196F3, 445px 1061px #673AB7, 928px 47px #00BCD4, 168px 1410px #8BC34A, 777px 782px #9C27B0, 1235px 1941px #9C27B0, 104px 1690px #8BC34A, 1167px 1338px #E91E63, 345px 1652px #009688, 1682px 1196px #F44336, 1995px 494px #8BC34A, 428px 798px #FF5722, 340px 1623px #F44336, 605px 349px #9C27B0, 1339px 1344px #673AB7, 1102px 1745px #3F51B5, 1592px 1676px #2196F3, 419px 1024px #FF9800, 630px 1033px #4CAF50, 1995px 1644px #00BCD4, 1092px 712px #9C27B0, 1355px 606px #F44336, 622px 1881px #CDDC39, 1481px 621px #9E9E9E, 19px 1348px #8BC34A, 864px 1780px #E91E63, 442px 1136px #2196F3, 67px 712px #FF5722, 89px 1406px #F44336, 275px 321px #009688, 592px 630px #E91E63, 1012px 1690px #9C27B0, 1749px 23px #673AB7, 94px 1542px #FFEB3B, 1201px 1657px #3F51B5, 1505px 692px #2196F3, 1799px 601px #03A9F4, 656px 811px #00BCD4, 701px 597px #00BCD4, 1202px 46px #FF5722, 890px 569px #FF5722, 1613px 813px #2196F3, 223px 252px #FF9800, 983px 1093px #F44336, 726px 1029px #FFC107, 1764px 778px #CDDC39, 622px 1643px #F44336, 174px 1559px #673AB7, 212px 517px #00BCD4, 340px 505px #FFF, 1700px 39px #FFF, 1768px 516px #F44336, 849px 391px #FF9800, 228px 1824px #FFF, 1119px 1680px #FFC107, 812px 1480px #3F51B5, 1438px 1585px #CDDC39, 137px 1397px #FFF, 1080px 456px #673AB7, 1208px 1437px #03A9F4, 857px 281px #F44336, 1254px 1306px #CDDC39, 987px 990px #4CAF50, 1655px 911px #00BCD4, 1102px 1216px #FF5722, 1807px 1044px #FFF, 660px 435px #03A9F4, 299px 678px #4CAF50, 1193px 115px #FF9800, 918px 290px #CDDC39, 1447px 1422px #FFEB3B, 91px 1273px #9C27B0, 108px 223px #FFEB3B, 146px 754px #00BCD4, 461px 1446px #FF5722, 1004px 391px #673AB7, 1529px 516px #F44336, 1206px 845px #CDDC39, 347px 583px #009688, 1102px 1332px #F44336, 709px 1756px #00BCD4, 1972px 248px #FFF, 1669px 1344px #FF5722, 1132px 406px #F44336, 320px 1076px #CDDC39, 126px 943px #FFEB3B, 263px 604px #FF5722, 1546px 692px #F44336;
  animation: animStar 150s linear infinite;
}

.starthird {
  width: 3px;
  height: 3px;
  box-shadow: 571px 173px #00BCD4, 1732px 143px #00BCD4, 1745px 454px #FF5722, 234px 784px #00BCD4, 1793px 1123px #FF9800, 1076px 504px #03A9F4, 633px 601px #FF5722, 350px 630px #FFEB3B, 1164px 782px #00BCD4, 76px 690px #3F51B5, 1825px 701px #CDDC39, 1646px 578px #FFEB3B, 544px 293px #2196F3, 445px 1061px #673AB7, 928px 47px #00BCD4, 168px 1410px #8BC34A, 777px 782px #9C27B0, 1235px 1941px #9C27B0, 104px 1690px #8BC34A, 1167px 1338px #E91E63, 345px 1652px #009688, 1682px 1196px #F44336, 1995px 494px #8BC34A, 428px 798px #FF5722, 340px 1623px #F44336, 605px 349px #9C27B0, 1339px 1344px #673AB7, 1102px 1745px #3F51B5, 1592px 1676px #2196F3, 419px 1024px #FF9800, 630px 1033px #4CAF50, 1995px 1644px #00BCD4, 1092px 712px #9C27B0, 1355px 606px #F44336, 622px 1881px #CDDC39, 1481px 621px #9E9E9E, 19px 1348px #8BC34A, 864px 1780px #E91E63, 442px 1136px #2196F3, 67px 712px #FF5722, 89px 1406px #F44336, 275px 321px #009688, 592px 630px #E91E63, 1012px 1690px #9C27B0, 1749px 23px #673AB7, 94px 1542px #FFEB3B, 1201px 1657px #3F51B5, 1505px 692px #2196F3, 1799px 601px #03A9F4, 656px 811px #00BCD4, 701px 597px #00BCD4, 1202px 46px #FF5722, 890px 569px #FF5722, 1613px 813px #2196F3, 223px 252px #FF9800, 983px 1093px #F44336, 726px 1029px #FFC107, 1764px 778px #CDDC39, 622px 1643px #F44336, 174px 1559px #673AB7, 212px 517px #00BCD4, 340px 505px #FFF, 1700px 39px #FFF, 1768px 516px #F44336, 849px 391px #FF9800, 228px 1824px #FFF, 1119px 1680px #FFC107, 812px 1480px #3F51B5, 1438px 1585px #CDDC39, 137px 1397px #FFF, 1080px 456px #673AB7, 1208px 1437px #03A9F4, 857px 281px #F44336, 1254px 1306px #CDDC39, 987px 990px #4CAF50, 1655px 911px #00BCD4, 1102px 1216px #FF5722, 1807px 1044px #FFF, 660px 435px #03A9F4, 299px 678px #4CAF50, 1193px 115px #FF9800, 918px 290px #CDDC39, 1447px 1422px #FFEB3B, 91px 1273px #9C27B0, 108px 223px #FFEB3B, 146px 754px #00BCD4, 461px 1446px #FF5722, 1004px 391px #673AB7, 1529px 516px #F44336, 1206px 845px #CDDC39, 347px 583px #009688, 1102px 1332px #F44336, 709px 1756px #00BCD4, 1972px 248px #FFF, 1669px 1344px #FF5722, 1132px 406px #F44336, 320px 1076px #CDDC39, 126px 943px #FFEB3B, 263px 604px #FF5722, 1546px 692px #F44336;
  animation: animStar 150s linear infinite;
}

@keyframes animStar {
  from { transform: translateY(0px); }
  to { transform: translateY(-2000px); }
}

.error {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}

.error__content {
  max-width: 600px;
  margin: 0 auto;
}

.error__message {
  margin-bottom: 20px;
}

.message__title {
  font-size: 60px;
  color: var(--bg-color);
}

.message__text {
  font-size: 20px;
  color: var(--secondary-text-color);
  margin-top: 10px;
}

.error__nav{
  margin-top: 30px;
}

.e-nav__link {
  text-decoration: none;
  padding: 10px 20px;
  background: var(--btn-color);
  color: var(--btn-text-color);
  border-radius: 5px;
  margin-top: 50px;
}

.e-nav__link:hover {
  background: var(--edit-action);
}

@media (max-width: 576px) {
  .message__title {
    font-size: 40px;
  }

  .message__text {
    font-size: 16px;
  }
}
</style>
