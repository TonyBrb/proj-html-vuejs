<template>
  <section>
    <div class="container">
      <div class="intro">
        <h2>Specialty Services</h2> 
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi illo reiciendis quaerat! Nemo, fugit? Ex, pariatur qui illum aliquam quisquam eaque quis blanditiis. Cum odit totam deleniti nesciunt ad est.
      </div>
      <div class="plans">
        <div class="learn-more">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, officiis tempora iste labore laboriosam sit unde saepe, veritatis quam repudiandae eaque nisi cumque est nam. Nostrum exercitationem ipsum adipisci cupiditate?
        </div>
        <div class="learn-more">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, officiis tempora iste labore laboriosam sit unde saepe, veritatis quam repudiandae eaque nisi cumque est nam. Nostrum exercitationem ipsum adipisci cupiditate?
        </div>
        <div class="learn-more">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo, officiis tempora iste labore laboriosam sit unde saepe, veritatis quam repudiandae eaque nisi cumque est nam. Nostrum exercitationem ipsum adipisci cupiditate?
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
    
    .plans{
      display: flex;
      .learn-more{
        width: 33%;
      }
    }
  }

</style>