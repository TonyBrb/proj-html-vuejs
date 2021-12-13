<template>
  <section>
    <div class="left">
      <img src="../assets/img/counters-bg-image.jpg" alt="">
    </div>
    <div class="right">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Minus quos, autem repellat distinctio accusantium aut minima cumque deleniti doloremque impedit expedita vitae sit ex enim consectetur molestiae, in itaque voluptatum?
    </div>
  </section>
</template>

<script>
export default {
  name:'SectionStats'
}
</script>

<style lang="scss" scoped>
  section{
    display: flex;
    .left{
      width: 30%;
      img{
        width: 100%;
      }
    }
    .right{
      width: 70%;
    }
  }
</style>