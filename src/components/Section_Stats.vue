// Creo il componente suddiviso in 2 div, left e right.
<template>
  <section>
    <div class="left">
      <div class="left-write">
        <h5>Investment Numbers</h5>
        <h2>Making An Impact In Our Communities</h2>
        <button class="btn">LEARN MORE</button>
      </div>
    </div>
    <div class="right">
      <div class="right-cube">
        <h1>86%</h1>
        <p>Succesfull Applications</p>
      </div>
      <div class="right-cube">
        <h1>94%</h1>
        <p>Return On Investment</p>
      </div>
      <div class="right-cube">
        <h1>92%</h1>
        <p>Applied Solutions</p>
      </div>
      <div class="right-cube">
        <h1>100%</h1>
        <p>Completely Secure</p>
      </div>
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
    height: 500px;
    .left{
      width: 30%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background-image: url('../assets/img/counters-bg-image.jpg');
      .left-write{
        padding-left: 50px;
        color: white;
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
    }
    .right{
      width: 70%;
      height: 100%;
      display: flex;
      flex-wrap: wrap;
      .right-cube{
        width: 50%;
        height: 50%;
        text-align: center;
        h1{
          color: #426ead;
          font-size: 50px;
          margin-bottom: 0;
        }
        p{
          color: #949494;
          margin: 0;
        }
      }
      .right-cube:first-child{
        h1{
          padding-top: 100px;
          padding-left: 150px;
        }
        p{
          padding-left: 150px;
        }
      }
      .right-cube:nth-child(2){
        h1{
          padding-top: 100px;
        }
      }
      .right-cube:nth-child(3){
        h1{
          padding-left: 150px;
        }
        p{
          padding-left: 150px;
        }
      }
    }
  }
</style>