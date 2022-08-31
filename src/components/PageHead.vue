<template>
  <div class="container">
    <div class="hello">Hello</div>
    <div class="name">I'M<br>
    RUSSEL MANITO</div>
    <div class="desc"> I've been doing Back-end Development, Front-end Development, and simple Programs for more than a year. </div>
    <br><br>
    <a href="https://github.com/rmanitoxv"><img src="../assets/gh-logo.png"></a> 
    <a href="https://www.linkedin.com/in/rrmanitoxv/"><img src="../assets/li-logo.png"></a>
  </div>
</template>

<script>

export default {
  name: 'PageHead',
  props: {
    msg: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap');
  .container{
    padding: 10rem;
    color: #E4E4E4;
    font: 'next art';
  }
  .hello{
    font-size: 3rem;
    font-family: 'Alumni Sans Pinstripe', sans-serif;
  }
  .name{
    font-size: 4.5rem;
    font-family: 'Roboto Condensed', sans-serif;
  }
  .desc{
      font-size: 1.125rem;
  }
  img{
    height: 2rem;
    margin: 1rem;
  }
</style>
