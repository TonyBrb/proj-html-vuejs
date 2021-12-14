<template>
  <section>
    <div class="container">
      <div class="intro">
        <h2>Specialty Services</h2>
        <div class="trattino"></div> 
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi illo reiciendis quaerat! Nemo, fugit? Ex, pariatur qui illum aliquam quisquam eaque quis blanditiis. Cum odit totam deleniti nesciunt ad est.
      </div>
      <div class="plans">
        <div class="learn-more">
          <h1><i class="fas fa-globe"></i></h1>
          <h3>Small Business Loans</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, officiis tempora iste labore laboriosam sit unde saepe, veritatis quam repudiandae.</p> 
          <div class="btn">Learn More</div>
        </div>
        <div class="learn-more">
          <h1><i class="far fa-gem"></i></h1>
          <h3>Credit Rating Advice</h3>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, officiis tempora iste labore laboriosam sit unde saepe, veritatis quam repudiandae.
          <div class="btn">Learn More</div>
        </div>
        <div class="learn-more">
          <h1><i class="fas fa-chart-line"></i></h1>
          <h3>Fast Crowd Founding</h3>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, officiis tempora iste labore laboriosam sit unde saepe, veritatis quam repudiandae.
          <div class="btn">Learn More</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionSpeciality'
}
</script>

<style lang="scss" scoped>
  section{
    background-color: #f6f7f7;
    text-align: center;
    .container{
    width: 60%;
    margin: 0 auto;
    }

    .intro{
      padding: 50px;
      .trattino{
        border: 1px solid black;
        width: 60px;
        margin-left: calc(50% - 30px);
        margin-bottom: 25px;
      }
    }
    
    .plans{
      display: flex;
      padding-bottom: 80px;
      .learn-more{
        width: 30%;
        background-color: #fff;
        h1{
          font-size: 50px;
          margin-bottom: 0;
        }

        .btn{
          width: 100%;
          background-color: #5cdbcc;
          color: white;
          text-align: center;
          padding-top: 5px;
          padding-bottom: 5px;
          margin-top: 30px;
          cursor: pointer;
        }
      }

      .learn-more:first-child{
        margin-left: 4%;
      }

      .learn-more:nth-child(2){
        margin-left: 2%;
        margin-right: 2%;
      }
    }
  }

</style>