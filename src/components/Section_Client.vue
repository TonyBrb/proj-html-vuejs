// Creo il componente suddiviso in 2 div, up e down, in up metto il titolo, in down i feedback con logo
// feedback e creatore del feedback
<template>
  <section>
    <div class="up">
      <h1>Client Feedback</h1>
      <div class="trattino"></div>
    </div>
    <div class="down">
      <div class="feedback">
        <div class="container">
        <img src="../assets/img/client-logo-4-200x87.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
        </div>
        <div class="feedback-down">
          <h5>ANDRE MENDOZA</h5>
          <h6>CREATIVE MARKET</h6>
        </div>
      </div>
      <div class="feedback">
        <div class="container">
        <img src="../assets/img/client-logo-1-1-200x87.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
        </div>
        <div class="feedback-down">
          <h5>ANDRE MENDOZA</h5>
          <h6>CREATIVE MARKET</h6>
        </div>
      </div>
      <div class="feedback">
        <div class="container">
        <img src="../assets/img/client-logo-2-200x87.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
        </div>
        <div class="feedback-down">
          <h5>ANDRE MENDOZA</h5>
          <h6>CREATIVE MARKET</h6>
        </div>
      </div>
      <div class="feedback">
        <div class="container">
        <img src="../assets/img/client-logo-3-200x87.png" alt="">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque voluptatibus laudantium officiis cum reiciendis harum fugit iusto id fugiat, odit quas suscipit odio quasi
        </div>
        <div class="feedback-down">
          <h5>ANDRE MENDOZA</h5>
          <h6>CREATIVE MARKET</h6>
        </div>
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
      height: 250px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      h1{
        margin: 0;
      }
      .trattino{
        width: 50px;
        border: 1px solid #426ead;
        margin-top: 20px;
      }
    }
    
    .down{
      display: flex;
      .feedback{
        width: 25%;
        border-right: 1px solid #f6f7f7;
        .container{
          width: 80%;
          margin: 0 auto;
          color: #949494;
        }
        img{
          width: 70%;
          display: block;
          margin-left: 40px;
        }

        .feedback-down{
          width: 100%;
          text-align: center;
          border: 2px solid #f6f7f7;
          border-left: none;
          border-right: none;
          margin-top: 60px;
          h5,h6{
            margin: 10px;
          }
          h6{
            color: #949494;
          }
        }
      }
    }
  }

</style>