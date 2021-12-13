<template>
  <section>
    <div class="cloud">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi, blanditiis! Aliquid excepturi nihil adipisci tempora. Atque error vel natus sed, numquam similique ut, accusamus, deserunt inventore officia earum odit cupiditate.
    </div>
    <div class="stats">
      <img src="../assets/img/graph.jpg" alt="">
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionCloud'
}
</script>

<style lang="scss" scoped>
  section{
    width: 80%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    .cloud{
      width: 50%;
    }
    .stats{
      width: 50%;
      img{
        width: 100%;
      }
    }
  }
</style>