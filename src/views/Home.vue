<template>
  <div class="home">
    <div class="feature-card">
      <router-link to="/movie/tt0409591">
        <img 
          src="https://a-static.mlcdn.com.br/1500x1500/livro-rick-morty-volume-1/paninibrasil/30434/ec886981348f76380682d1e45fb4dd0e.jpg" 
          alt="Rick and Morty"
          class="featured-img"
        >
        <div class="detail">
          <h3>Rick and Morty</h3>
          <p>
            Acompanhe malucas viagens no tempo-espaço e por universos paralelos com Rick, um cientista com problemas com a bebida, e 
            seu neto Morty, um adolescente não tão brilhante quanto o avô.
          </p>
        </div>
      </router-link>
    </div>
  </div>
</template>
<script>

export default {


}
</script>


<style lang="scss">
.home {
  .feature-card {
    position: relative;
    .featured-img {
      display: block;
      width: 100%;
      height: 300px;
      object-fit: cover;
      position: relative;
      z-index: 0;
    }
    .detail {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 16px;
      z-index: 1;
      h3 {
        color:#FFF;
        margin-bottom: 16px;
      }
      p {
        color: #FFF;
      }
    }
  }
}
</style>