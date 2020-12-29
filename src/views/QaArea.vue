<template>
  <div id="qaPage">
    <div class="container">
      <div class="title">
        <h1>常見問題</h1>
      </div>
      <div class="qa qa1">
        <div class="question">
          <h2>Q : 如何申請理賠?</h2>
        </div>
        <div class="answer">
          <h2>A : <span>來電客服通知我們，並填寫理賠申請書並備妥相關文件，e-mail或郵寄至易安網保經客服中心。</span></h2>
        </div>
      </div>
      <div class="qa qa2">
        <div class="question">
          <h2>Q : 有保障自行車競賽、馬拉松嗎?</h2>
        </div>
        <div class="answer">
          <h2>A : <span>若主辦單位將活動列為競賽，僅保障責任險及運動器材損失，不保障意外身故及失能。</span></h2>
        </div>
      </div>
      <div class="qa qa3">
        <div class="question">
          <h2>Q : 自行車車損的定義是什麼?</h2>
        </div>
        <div class="answer">
          <h2>A : <span>凡是發生竊盜、搶奪、強盜、碰撞造成的自行車損壞或滅失，即可申請理賠。</span></h2>
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
  #qaPage{
    width: 100%;
    height: 80vh;
    background-color: #efefef;
    text-align: center;
    padding: 5% 5%;
  }
  .container{
    margin : 0 auto;
  }
  .title{
    width: 100%;
    margin: 0 auto;
    background-color: #3da1a6;
    padding: 1%;
  }
  .title h1{
    color: #fff;
  }

  .qa{
    width: 90%;
    margin: 5% 0 auto 8%;
    text-align: left;
  }
  .qa .question{
    color: #3da1a6 ;
    margin-bottom: 1rem;
    vertical-align: middle;
  }
  .qa .question,.answer{
    font-size: 1.5rem;
  }

  .qa .answer span{
    font-size: 1.5rem;
    vertical-align: middle;
  }
  .qa2{
    position: relative;
  }
  .qa2::before{
    content: "";
    background: #ccc;
    width: 65%;
    height: 2px;
    position: absolute;
    top: -20%;
    left: 2%;
  }
  .qa2::after{
    content: "";
    background: #ccc;
    width: 65%;
    height: 2px;
    position: absolute;
    bottom: -20%;
    left: 2%;
  }
  @media only screen and (max-width: 1023px){
    #qaPage{
      display: flex;
      align-items: center;
    }
    .qa{
      width: 90%;
      margin: 5% 0 0 8%;
      text-align: left;
    }
    .qa .question{
      color: #3da1a6 ;
      margin-bottom: 1rem;
      vertical-align: middle;
    }
    .qa .question,.answer{
      font-size: 1rem;
    }

    .qa .answer span{
      font-size: 1.2rem;
      vertical-align: middle;
    }
    .qa2{
      position: relative;
    }
    .qa2::before{
      content: "";
      background: #ccc;
      width: 65%;
      height: 2px;
      position: absolute;
      top: -20%;
      left: 2%;
    }
    .qa2::after{
      content: "";
      background: #ccc;
      width: 65%;
      height: 2px;
      position: absolute;
      bottom: -20%;
      left: 2%;
  }
  }
  @media only screen and (max-width: 767px){
    #qaPage{
      height: 60vh;
      display: flex;
      align-items: center;
    }
    .title{
      width: 90%;
      padding: 1%;
    }
    .title h1{
      color: #fff;
    }

    .qa{
      width: 90%;
      margin: 5% auto;
      text-align: left;
    }
    .qa .question{
      color: #3da1a6 ;
      margin-bottom: 1rem;
      vertical-align: middle;
    }
    .qa .question,.answer{
      font-size: 1rem;
    }

    .qa .answer span{
      font-size: 1rem;
    }
    .qa2{
      position: relative;
    }
    .qa2::before{
      content: "";
      background: #ccc;
      width: 90%;
      height: 2px;
      position: absolute;
      top: -10%;
      left: 2%;
    }
    .qa2::after{
      content: "";
      background: #ccc;
      width: 90%;
      height: 2px;
      position: absolute;
      bottom: -10%;
      left: 2%;
    }
  }
</style>