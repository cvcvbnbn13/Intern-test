<template>
  <div id="subscrPage">
    <div class="title">
      <h1>選擇你的保險方案</h1>
      <h3>立即保障你的鐵馬旅行 !</h3>
    </div>
    <div class="subscrPlan">
      <div class="plan plan1">
        <div class="planTitle">
          <h3>基礎方案</h3>
          <h5>約NT$810/年</h5>
        </div>
        <div class="planContent">
          <div class="item">
            <p>意外身故失能
            </p>
            <span>100萬</span>
          </div>
          <div class="item">
            <p>燒燙傷皮膚移植
            </p>
            <span>50萬</span>
          </div>
          <div class="item">
            <p>意外重大失能增額
            </p>
            <span>50萬</span>
          </div>
          <div class="item">
            <p>個人責任
            </p>
            <span>10萬</span>
          </div>
          <div class="item">
            <p>自行車責任
            </p>
            <span>20萬</span>
          </div>
          <div class="item">
            <p>運動休閒器材損失
            </p>
            <span>3000元</span>
          </div>
        </div>
        <a href="javascript:;">選擇此方案</a>
      </div>
      <div class="plan plan2">
        <div class="planTitle">
          <h3>推薦方案</h3>
          <h5>約NT$1410/年</h5>
        </div>
        <div class="planContent">
          <div class="item">
            <p>意外身故失能
            </p>
            <span>200萬</span>
          </div>
          <div class="item">
            <p>燒燙傷皮膚移植
            </p>
            <span>100萬</span>
          </div>
          <div class="item">
            <p>意外重大失能增額
            </p>
            <span>50萬</span>
          </div>
          <div class="item">
            <p>個人責任
            </p>
            <span>10萬</span>
          </div>
          <div class="item">
            <p>自行車責任
            </p>
            <span>20萬</span>
          </div>
          <div class="item">
            <p>運動休閒器材損失
            </p>
            <span>3000元</span>
          </div>
        </div>
        <a href="javascript:;">選擇此方案</a>
      </div>
      <div class="plan plan3">
        <div class="planTitle">
          <h3>進階方案</h3>
          <h5>約NT$2010/年</h5>
        </div>
        <div class="planContent">
          <div class="item">
            <p>意外身故失能
            </p>
            <span>300萬</span>
          </div>
          <div class="item">
            <p>燒燙傷皮膚移植
            </p>
            <span>150萬</span>
          </div>
          <div class="item">
            <p>意外重大失能增額
            </p>
            <span>50萬</span>
          </div>
          <div class="item">
            <p>個人責任
            </p>
            <span>10萬</span>
          </div>
          <div class="item">
            <p>自行車責任
            </p>
            <span>20萬</span>
          </div>
          <div class="item">
            <p>運動休閒器材損失
            </p>
            <span>3000元</span>
          </div>
        </div>
        <a href="javascript:;">選擇此方案</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  #subscrPage{
    width: 100%;
    height: 100%;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  span{
    color: #3da1a6;
  }
  .title{
    width: 100%;
    font-weight: bold;
    padding-top: 5%;
  }
  .title h1{
    color: #3da1a6;
    font-size: 3rem;
  }
  .title h3{
    font-size: 2rem;
    padding-top: 1%;
  }
  .subscrPlan{
    width: 90%;
    margin: 5% auto;
    display: flex;
    justify-content: center;
  }
  .plan{
    height: 55vh;
    width: 33%;
    border: 1px solid #000;
    border-radius: 10px;
    margin: 1.5%;
    font-weight: bold;
    padding: 3% 2% 0;
    box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
  }
  .plan .planTitle{
    padding: 5% 0;
  }
  .plan .planTitle h3{
    font-size: 2rem;
    padding: 5px 0;
  }
  .plan .planTitle h5{
    font-size: 1rem;
  }
  .plan .planContent{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  .plan2{
    position: relative;
    overflow: hidden;
  }
  .plan2::before{
    content:'';
    background: #3da1a6;
    width: 20px;
    height: 80px;
    transform: rotate(45deg);
    position: absolute;
    left: 1%;
    top: -5%;
  }
  .plan .planContent .item{
    width: 50%;
    display: flex;
    font-size: 1.2rem;
    flex-direction: column;
    font-weight: bold;
    padding: 5% 0;
  }
  .plan .planContent .item:nth-child(5),
  .plan .planContent .item:nth-child(6){
    padding: 0;
    margin-bottom: 20%;
  }
  .plan a{
    text-decoration: none;
    color: #fff;
    background-color: #3da1a6;
    font-size: 1.8rem;
    padding: 0.5rem 3rem;
    border-radius: 5px;
    box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
    cursor: pointer;
  }
  @media only screen and (max-width: 1023px){
    .title{
      padding-top: 5%;
    }
    .title h1{
      font-size: 2.6rem;
    }
    .title h3{
      font-size: 1.5rem;
    }
    .subscrPlan{
      width: 100%;
      margin: 3% auto;
      display: flex;
      justify-content: center;
    }
    .plan{
      height: 40vh;
      padding: 3% 3%;
      box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
    }
    .plan .planTitle{
      padding: 3% 0 4%;
    }
    .plan .planTitle h3{
      font-size: 1.5rem;
      padding: 5px 0;
    }
    .plan .planTitle h5{
      font-size: .8rem;
    }
    .plan .planContent .item{
      width: 50%;
      display: flex;
      font-size: 1rem;
      flex-direction: column;
      font-weight: bold;
      padding: 5% 0;
    }
    .plan .planContent .item:nth-child(5),
    .plan .planContent .item:nth-child(6){
      padding: 0;
      margin-bottom: 15%;
    }
    .plan a{
      text-decoration: none;
      color: #fff;
      background-color: #3da1a6;
      font-size: 1rem;
      padding: 0.4rem 2rem;
      border-radius: 5px;
      box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
      cursor: pointer;
    }
  }
  @media only screen and (max-width: 767px){
    .title{
      padding-top: 5%;
    }
    .title h1{
      font-size: 3rem;
    }
    .title h3{
      font-size: 1.8rem;
    }
    .subscrPlan{
      width: 100%;
      margin: 5% auto;
      display: flex;
      justify-content: center;
    }
    .plan{
      width: 60%;
      padding: 2% 4%;
      box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
    }
    .plan1,.plan3{
      display: none;
    }
    .plan .planTitle{
      padding: 3% 0;
    }
    .plan .planTitle h3{
      font-size: 2rem;
      padding: 5px 0;
    }
    .plan .planTitle h5{
      font-size: 1rem;
    }
    .plan .planContent .item{
      width: 50%;
      display: flex;
      font-size: 1rem;
      flex-direction: column;
      font-weight: bold;
      padding: 5% 0;
    }
    .plan .planContent .item:nth-child(5),
    .plan .planContent .item:nth-child(6){
      padding: 0;
      margin-bottom: 10%;
    }
    .plan a{
      text-decoration: none;
      color: #fff;
      background-color: #3da1a6;
      font-size: 1.5rem;
      padding: 0.4rem 2.5rem;
      border-radius: 5px;
      box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
      cursor: pointer;
    }
  }
  @media only screen and (max-width: 480px){
    .title{
      padding-top: 5%;
    }
    .title h1{
      font-size: 2rem;
    }
    .title h3{
      font-size: 1.2rem;
    }
    .subscrPlan{
      width: 100%;
      margin: 5% auto;
      display: flex;
      justify-content: center;
    }
    .plan{
      width: 80%;
      padding: 0 4%;
      box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
    }
    .plan1,.plan3{
      display: none;
    }
    .plan .planTitle{
      padding: 5% 0 3%;
    }
    .plan .planTitle h3{
      font-size: 1.5rem;
      padding: 5px 0;
    }
    .plan .planTitle h5{
      font-size: .8rem;
    }
    .plan2::before{
      content:'';
      background: #3da1a6;
      width: 20px;
      height: 80px;
      transform: rotate(45deg);
      position: absolute;
      left: 1%;
      top: -5%;
    }
    .plan .planContent .item{
      width: 50%;
      display: flex;
      font-size: 1rem;
      flex-direction: column;
      font-weight: bold;
      padding: 7.5% 0;
    }
    .plan .planContent .item:nth-child(5),
    .plan .planContent .item:nth-child(6){
      padding: 0;
      margin-bottom: 10%;
    }
    .plan a{
      text-decoration: none;
      color: #fff;
      background-color: #3da1a6;
      font-size: 1.3rem;
      padding: 0.2rem 1.8rem;
      border-radius: 5px;
      box-shadow: 0 0 3px 1px rgba(0,0,0,0.3);
      cursor: pointer;
    }
  }
</style>