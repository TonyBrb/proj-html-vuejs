<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/finance_logo_1x.png" alt="">
      </div>
      <div class="menu">
        <ul>
          <li>prova</li>
          <li>prova</li>
          <li>prova</li>
          <li>prova</li>
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
    .container{
      width: 95%;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    
    height: 50px;
    border-bottom: 1px solid #000;
    .logo{
      width: 180px;
      img{
        width: 100%;
      }
    }
    .menu{
      align-items: center;
    }
  }

  ul{
    list-style: none;
    display: flex;
  }

</style>