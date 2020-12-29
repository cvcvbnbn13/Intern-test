<template>
  <section id="headerPage">
    <div id="backImg">
      <img src="@/assets/banner.png" alt="">
    </div>
    <div class="banner">
      <div class="logo">LOGO</div>
      <div class="menber">
        <a href="javascript:;">加入會員</a>
        <a href="javascript:;">會員登入</a>
      </div>
    </div>
    <div class="title">
      <h1>你也熱愛騎單車 ?</h1>
      <h2>-鐵馬族的專屬保險-</h2>
      <h3>自行車責任 | 失竊車損 | 意外身故失能</h3>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
  body,html{
    width: 100%;
  }
  #headerPage{
    width: 100%;
    height: 100vh;
    background: #3da1a6;
    position: relative;
  }
  #backImg img{
    height: 100vh;
    position: absolute;
    left: 0;
    width: 100%;
  }
  .banner{
    width: 90%;
    margin: auto;
    padding-top: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: #fff;
    position: relative;
    z-index: 1;
  }
  .banner .logo{
    font-size: 2rem;
    font-weight: bold;
  }
  .banner a{
    text-decoration: none;
    color: #fff;
    font-size: 1.5rem;
    font-weight: normal;
  }
  .banner a:nth-child(2){
    margin-left: 1.5rem;
  }
  .title{
    width: 100%;
    position: absolute;
    z-index: 1;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%) rotate(-3deg);
    color: #fff;
    font-size: 2rem;
  }
  .title h1{
    font-size: 8rem;
    text-shadow: 5px 10px rgba(0, 0, 0,.5);
  }
  .title h2{
    font-size: 5rem;
    text-shadow: 3px 7px rgba(0, 0, 0,.5);
  }
  .title h3{
    text-shadow: 1px 5px rgba(0, 0, 0,.5);
    padding-top: 1rem;
  }
  @media only screen and (max-width: 1023px){
    .title h1{
      font-size: 6rem;
      text-shadow: 2px 5px rgba(0, 0, 0,.5);
    }
    .title h2{
      font-size: 4rem;
      text-shadow: 1px 3px rgba(0, 0, 0,.5);
    }
    .title h3{
      text-shadow: 1px 2px rgba(0, 0, 0,.5);
      padding-top: 1rem;
    }
  }
  @media only screen and (max-width: 767px){
    #headerPage{
      height: 80vh;
    }
    #backImg img{
      height: 80vh;
      position: absolute;
      left: 0;
    }
    .banner .logo{
      font-size: 1.5rem;
    }
    .banner a{
      font-size: 1rem;
    }
    .banner a:nth-child(2){
      margin-left: 1.5rem;
    }
    .title{
      font-size: 1.5rem;
    }
    .title h1{
      font-size: 5rem;
      text-shadow: 2px 5px rgba(0, 0, 0,.5);
    }
    .title h2{
      font-size: 3rem;
      text-shadow: 1px 3px rgba(0, 0, 0,.5);
    }
    .title h3{
      text-shadow: 1px 2px rgba(0, 0, 0,.5);
      padding-top: 1rem;
    }
  }
  @media only screen and (max-width: 480px){
    #headerPage{
      height: 40vh;
    }
    #backImg img{
      height: 36vh;
      position: absolute;
      left: 0;
    }
    .banner .logo{
      font-size: 0.5rem;
    }
    .banner a{
      font-size: 0.5rem;
    }
    .banner a:nth-child(2){
      margin-left: 1rem;
    }
    .title{
      font-size: .5rem;
    }
    .title h1{
      font-size: 2rem;
      text-shadow: .5px 2px rgba(0, 0, 0,.5);
    }
    .title h2{
      font-size: 1rem;
      text-shadow: .5px 2px rgba(0, 0, 0,.5);
      padding-top: 0.5rem;
    }
    .title h3{
      text-shadow: .5px 2px rgba(0, 0, 0,.5);
      padding-top: 0.5rem;
    }
  }
</style>