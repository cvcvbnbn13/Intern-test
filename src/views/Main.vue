<template>
  <div id="mainPage">
    <div class="news">
      <div class="txt">
        <h6>2019/08/08</h6>
        <h1>騎腳踏車違規 害重機騎士身亡 判賠130萬</h1>
        <p>高雄市李姓婦人騎腳踏車未依規定行駛，遭何姓機車騎士從後方追撞<br>
，騎士當場死亡。橋頭地院依過失致死罪，判處徒刑七月，後來以130<br>
萬元達成和解。</p>
      </div>
      <div class="image">
        <img src="@/assets/news.png" alt="新聞圖" class="newsImg">
        <span>(示意圖取自網路)</span>
      </div>
    </div>
    <div class="info">
      <div class="container">
        <div class="title">
          <h1>不只是意外險，還是<span>單車險</span></h1>
          <h2>開車有汽車保險，騎單車也該有單車保險</h2>
        </div>
        <div class="bikeIns">
          <div class="item item1">
            <img src="@/assets/icon_bike.png" alt="">
            <div class="txt">
              <div class="polygon">
                <h3>自行車責任</h3>
              </div>
              <p>如汽機車強制險般，理賠事故造成對方的損失</p>
            </div>
          </div>
          <div class="item item2">
            <img src="@/assets/icon_theft.png" alt="">
            <div class="txt">
              <div class="polygon">
                <h3>失竊車損</h3>
              </div>
              <p>理賠因竊盜、搶奪、強盜、碰撞造成的運動器材損失</p>
            </div>
          </div>
          <div class="item item3">
            <img src="@/assets/icon_disable.png" alt="">
            <div class="txt">
              <div class="polygon">
                <h3>意外身故失能</h3>
              </div>
              <p>理賠被保險人意外身故或失能</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped> 
 #mainPage {
   width: 100%;
   text-align: left;
   box-sizing: border-box;
 }
 .news{
   display: flex;
   width: 100%;
   padding: 0 0.5rem;
   height: 40vh;
   justify-content: center;
   align-items: center;
   position: relative;
 }
 .news .image{
   position: relative;
 }
 .news .txt{
   font-weight: bold;
   padding-right: 5%;
 }

 .news .txt h1{
   font-size: 3rem;
   text-align: center;
   padding-bottom: 2%;
 }
 .news .txt p{
   font-size: 1.8rem;
   font-weight: normal;
   padding-top: 2%;
 }

.news .image .newsImg{
  width: 300px;
  height: 300px;
  position: relative;
}
.news .image span{
  position: absolute;
  width: 100%;
  bottom: -10%;
  left: 0%;
  text-align: right;
  font-size: 1.5rem;
  font-weight: bold;
}

.info{
  background-color:#4b4b55;
  height: 70vh;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.info .title h1{
  font-size: 3.5rem;
  color: #fff;
  font-weight: bold;
}
.info .title h2{
  color: #fbdc4c;
  font-size: 2rem;
}
.bikeIns{
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  margin: auto;
  font-weight: bold;
}
.bikeIns .item{
  padding-top: 8%;
  width: 15%;
  text-align: left;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.bikeIns .item .polygon{
  text-align: center;
  color: #000;
  background-color: #fff;
  clip-path: polygon(0 11%, 100% 3%, 100% 88%, 0 77%);
  height: 45px;
  line-height: 45px;
  font-weight: bold;
}
.bikeIns .item .polygon h3{
  font-size: 1.3rem;
}
.bikeIns .item p{
  padding-top: 10%;
  color: #fff;
}
@media only screen and (max-width: 1023px){
  #mainPage{
    background-color:#4b4b55;
    padding-top: 1rem;
  }
  .news{
    width: 90%;
    margin: 1% auto;
    height: 35vh;
    background-color: #fff;
  }
  .news .txt{
    width: 65%;
  }

  .news .txt h1{
    font-size: 2.5rem;
    text-align: left;
  }
  .news .txt p{
    font-size: 1.3rem;
    text-align: justify;
  }
  .news .txt p br{
    display: none;
  }

  .news .image .newsImg{
    width: 250px;
    height: 250px;
  }
  .news .image span{
    font-size: 1.5rem;
  }

  .info{
    height: 110vh;
  }
  .info .title h1{
    font-size: 4rem;
  }
  .info .title h2{
    color: #fbdc4c;
    font-size: 2.5rem;
  }
  .bikeIns{
    flex-direction: column;
  }
  .bikeIns .item{
    padding-top: 2%;
    width: 100%;
    flex-direction: row;
    align-items: center;
  }
  .bikeIns .item2{
    flex-direction: row-reverse;
  }
  .bikeIns .item2 img{
    padding-right: 0;
    padding-left: 5%;
  }
  .bikeIns .item img{
    width: 250px;
    height: 250px;
    padding-right: 5%;
  }
  .bikeIns .item .txt{
    width: 40%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .bikeIns .item .polygon{
    text-align: center;
    color: #000;
    background-color: #fff;
    clip-path: polygon(0 11%, 100% 3%, 100% 88%, 0 77%);
    display: flex;
    justify-content: center;
    width: 50%;
  }
  .bikeIns .item .polygon h3{
    font-size: 1.1rem;
  }
}
@media only screen and (max-width: 767px){
  #mainPage{
    background-color:#4b4b55;
    padding-top: 1rem;
  }
  .news{
    width: 90%;
    margin: 1% auto;
    height: 30vh;
    background-color: #fff;
  }
  .news .txt{
    width: 65%;
  }

  .news .txt h1{
    font-size: 2rem;
    text-align: left;
  }
  .news .txt p{
    font-size: 1rem;
    text-align: justify;
  }
  .news .txt p br{
    display: none;
  }

  .news .image .newsImg{
    width: 200px;
    height: 200px;
  }
  .news .image span{
    font-size: 1rem;
  }

  .info{
    height: 110vh;
  }
  .info .title h1{
    font-size: 3rem;
  }
  .info .title h2{
    color: #fbdc4c;
    font-size: 1.8rem;
  }
  .bikeIns{
    flex-direction: column;
  }
  .bikeIns .item{
    padding-top: 2%;
    width: 100%;
    flex-direction: row;
    align-items: center;
  }
  .bikeIns .item2{
    flex-direction: row-reverse;
  }
  .bikeIns .item2 img{
    padding-right: 0;
    padding-left: 5%;
  }
  .bikeIns .item img{
    width: 250px;
    height: 250px;
    padding-right: 5%;
  }
  .bikeIns .item .txt{
    width: 40%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .bikeIns .item .polygon{
    text-align: center;
    color: #000;
    background-color: #fff;
    clip-path: polygon(0 11%, 100% 3%, 100% 88%, 0 77%);
    display: flex;
    justify-content: center;
    width: 50%;
  }
  .bikeIns .item .polygon h3{
    font-size: 1.1rem;
  }
}
@media only screen and (max-width: 480px){
  #mainPage{
    background-color:#4b4b55;
    padding-top: 1rem;
  }
  .news{
    width: 90%;
    margin: 1% auto;
    height: 25vh;
    background-color: #fff;
  }
  .news .txt{
    width: 55%;
  }

  .news .txt h1{
    font-size: .8rem;
    text-align: left;
  }
  .news .txt p{
    font-size: .3rem;
    text-align: justify;
  }

  .news .image .newsImg{
    width: 150px;
    height: 150px;
  }
  .news .image span{
    font-size: .5rem;
  }

  .info{
    height: 75vh;
  }
  .info .container{
    padding-top: 0;
  }
  .info .title h1{
    font-size: 1.8rem;
  }
  .info .title h2{
    color: #fbdc4c;
    font-size: 1.2rem;
  }
  .bikeIns{
    flex-direction: column;
  }
  .bikeIns .item{
    width: 80%;
    flex-direction: row;
    align-items: center;
  }
  .bikeIns .item2{
    flex-direction: row-reverse;
  }
  .bikeIns .item2 img{
    padding-right: 0;
    padding-left: 5%;
  }
  .bikeIns .item img{
    width: 150px;
    height: 150px;
    padding-right: 5%;
  }
  .bikeIns .item .txt{
    width: 50%;
  }
  .bikeIns .item .polygon{
    text-align: center;
    color: #000;
    background-color: #fff;
    clip-path: polygon(0 11%, 100% 3%, 100% 88%, 0 77%);
    display: flex;
    justify-content: center;
  }
  .bikeIns .item .polygon h3{
    font-size: 1.1rem;
  }
}
</style>