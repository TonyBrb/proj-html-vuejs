<template>
  <footer>
    <div class="up">
      <div class="container">
        <div class="box">
          <img src="../assets/img/finance_logo_footer.png" alt="">
        </div>
        <div class="box">
          <h5>RECENT POSTS</h5>
          <p>> When is it the right time to sell your company?</p>
          <p>> Personal debt or company debt we explore your options</p>
          <p>> An interview with a so-called business angel</p>
        </div>
        <div class="box">
          <h5>SERVICES</h5>
          <p>> SMALL BUSINESS LOAN SERVICES</p>
          <p>> CREDIT RATING ADVICE SERVICES</p>
          <p>> CROWD FOUNDING SERVICES</p>
        </div>
        <div class="box">
          <h5>LATEST</h5>
          <p><i class="fab fa-twitter"></i></p>
        </div>
      </div>
    </div>

    <div class="down">
      <div class="container">
        <div class="copyright">
          <i class="far fa-copyright"></i> Copyright 2012 - 2020  |  Avada Theme by Theme Fusion  |  All Rights Reserved  |  Powered by WordPress
        </div>
        <div class="social">
          <div class="circle"><i class="fab fa-facebook-f"></i></div>
          <div class="circle"><i class="fab fa-twitter"></i></div>
          <div class="circle"><i class="fab fa-youtube"></i></div>
          <div class="circle"><i class="fab fa-instagram"></i></div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
  footer{
    .up{
      background-color: #1c1b21;
    }
    .container{
      width: 95%;
      margin: 0 auto;
      display: flex;
      padding-top: 40px;

      .box:last-child{
        p{
          color: #4876b5;
        }
      }

      .box{
        width: 25%;
        margin-right: 2%;
        color: grey;

        h5{
          color: white;
          margin-top: 0;;
        }
        img{
          width: 50%;
          margin-left: 15px;
        }
      }
    }

    .down{
      height: 80px;
      background-color: #19191f;
      color: grey;
      display: flex;
      align-items: center;
      .container{
        padding-top: 0;
        justify-content: space-between;
        align-content: initial;
      }

      .copyright{
        font-size: 10px;
        line-height: 32px;
      }
      

      .social{
        display: flex;
      }
      .circle{
        background-color: #5cdbcc;
        color: white;
        border-radius: 50%;
        padding-top: 7px;
        padding-bottom: 7px;
        padding-left: 10px;
        padding-right: 10px;
        margin-right: 10px;
        cursor: pointer;
      }
    }
  }

</style>