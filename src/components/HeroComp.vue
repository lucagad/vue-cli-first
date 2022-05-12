<template>
  <div>
    <div class="jumbotron">
      <div class="jumbotron-content-box">
          <h2>Il mio primo Jumbotron con Vue Cli</h2>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HeroComp'
  }
</script>

<style scoped>

.jumbotron{
  width: 100%;
  height: 700px;
  background-image: url("../assets/jumbo.png");
  background-position: center;
  background-size: cover;
}

.jumbotron-content-box{
  width: 100%;
  height:auto;
  margin:0 auto;
  text-align: center;
  color: white;
  padding-top: 10%;
}

.jumbotron-content-box h2{
  font-size: 35px;
}

.jumbotron-content-box p{
  padding: 4% 25%;
  font-size: 25px;
  text-align: center;
}

</style>