<template>
  <section>
    <div class="up">
      <h1>Client Feedback</h1>
    </div>
    <div class="down">
      <div class="feedback">
        <img src="../assets/img/client-logo-4.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
      </div>
      <div class="feedback">
        <img src="../assets/img/client-logo-4.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
      </div>
      <div class="feedback">
        <img src="../assets/img/client-logo-4.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
      </div>
      <div class="feedback">
        <img src="../assets/img/client-logo-4.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionClient'
}
</script>

<style lang="scss" scoped>
  section{
    .up{
      background-color: #f6f7f7;
      text-align: center;
      height: 100px;
    }
    
    .down{
      display: flex;
      .feedback{
        width: 25%;
        border-right: 1px solid grey;
        img{
          width: 100%;
        }
      }
    }
  }

</style>