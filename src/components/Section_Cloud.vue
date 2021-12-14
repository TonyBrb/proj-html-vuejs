<template>
  <section>
    <div class="cloud">
      <h2>Cloud Based Finance</h2>
      <div class="trattino"></div>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Asperiores quis quos distinctio, illum eaque soluta aperiam. <br> <br> dolorum odio est molestiae, totam unde voluptas animi accusamus sit repellat amet minus corporis.
      </p>
      <button class="btn">LEARN MORE</button>
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
      .trattino{
        width: 60px;
        border: 1px solid black;
      }
      .btn{
        background-color: #5cdbcc;
        padding: 10px 20px 10px 20px;
        border: none;
        border-radius: 20px;
        color: white;
        font-size: 12px;
        cursor: pointer;
      }
    }
    .stats{
      width: 50%;
      img{
        width: 100%;
      }
    }
  }
</style>