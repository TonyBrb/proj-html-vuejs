<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/finance_logo_1x.png" alt="">
      </div>
      <div class="menu">
        <ul>
          <a href="#"><li>HOME</li></a> 
          <a href="#"><li>ABOUT</li></a> 
          <a href="#"><li>SERVICES</li></a> 
          <a href="#"><li>PACKAGES</li></a> 
          <a href="#"><li>INSIGHT</li></a> 
          <a href="#"><li class="active">CONTACT</li></a> 
          <a href="#"><li>+</li></a> 
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss" scoped>
  header{
    height: 50px;
    display: flex;
    align-items: center;
    .container{
      width: 95%;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
   
    .logo{
      width: 180px;
      img{
        width: 100%;
      }
    }
    .menu{
      height: 100%;
      a{
        text-decoration: none;
        color: #949494;
        margin-right: 20px;
      }
    }
  }

  ul{
    list-style: none;
    display: flex;
    margin: 0;
    line-height: 50px;
    align-items: center;

    li:hover{
      background-color: #f6f7f7;
      color: #1b304b;
    }

    .active{
      background-color: #5ddecc;
      color: white;
      border-radius: 25px;
      padding-left: 20px;
      padding-right: 20px;
      height: 30px;
      line-height: 30px;
    }
  }

</style>