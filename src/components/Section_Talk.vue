<template>
  <section>
    <div class="container">
      <h1>Ready to talk?</h1>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus, beatae? Exercitationem magni repellendus itaque</p>
      <button class="btn">LET'S TALK</button>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionTalk'
}
</script>

<style lang="scss" scoped>
  section{
    min-height: 300px;
    padding-bottom: 50px;
    background-image: url('../assets/img/ready_to_talk_cta_bg.jpg');
    object-fit: contain;
    text-align: center;
    color: white;
    .container{
      width: 30%;
      margin: 0 auto;
    }

    h1{
      margin: 0;
      font-size: 50px;
      padding-top: 80px;
      padding-bottom: 20px;
    }

    p{
      color: #949494;
    }
    
    .btn{
      margin-top: 20px;
      background-color: #5cdbcc;
      padding: 10px 20px 10px 20px;
      border: none;
      border-radius: 20px;
      color: white;
      font-size: 12px;
      cursor: pointer;
      
    }

  }
</style>