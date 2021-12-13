<template>
  <div class="jumbotron">
    <img src="../assets/img/home_finance_slider_bg.jpg" alt="">
    <div class="jumbo-down">
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
      </div>
      <div class="client-logo">
        <img src="../assets/img/client-logo-7-200x87.png" alt="">
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
    img{
      width: 100%;
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