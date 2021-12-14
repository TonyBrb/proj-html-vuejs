<template>
  <div class="jumbotron">
    <img src="../assets/img/home_finance_slider_bg.jpg" alt="">
    <span>Right People. Right Investments.</span>
    <div class="jumbo-down">
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-8-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-9-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-5-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-6-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Jumbotron'
}

</script>

<style lang="scss" scoped>
  .jumbotron{
    width: 100%;
    background-color: #f6f7f7;
    position: relative;
    img{
      width: 100%;
    }

    span{
      margin: 0;
      position: absolute;
      top: 46%;
      left:50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 50px;
    }
    .jumbo-down{
      display: flex;
      
      width: 95%;
      margin: 0 auto;
      .client-logo{
        width: 16.6%;
        img{
          width: 100%;
        }
      }
    }
  }

</style>