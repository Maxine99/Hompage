<template>      
    <div class="container">
      <div class="head">
        <h1 class="title">
          Da Vinci Restaurant
        </h1>
        <h2>
          Italienische Speisen von Pasta bis Pizza!
        </h2>
        <div class="links">
          <nuxt-link
            to="/"
            target="_blank"
            class="button1"
          >
            Startseite
          </nuxt-link>
          <nuxt-link 
            to="Historie"
            target="_blank"
            class="button1"
          >
            Historie unseres Restaurants
          </nuxt-link>
          <nuxt-link 
            to="Gaestebuch"
            target="_blank"
            class="button1"
          >
            Gästebuch
          </nuxt-link>
          <nuxt-link 
            to="Kontakt"
            target="_blank"
            class="button1"
          >
            Kontakt
          </nuxt-link>
        </div>
      </div>
      <div class="inhalt">
        <h1>Speisekarte</h1>
        <br>
        <input type="checkbox" id="pizza" value="Pizza" v-model="dishes">
        <label for="pizza">Pizza</label>
        <input type="checkbox" id="lasagne" value="Lasagne" v-model="dishes">
        <label for="lasagne">Lasagne</label>
        <input type="checkbox" id="spaggetthi" value="SPaggetthi" v-model="dishes">
        <label for="spaggetthi">Spaggetthi</label>
        <input type="checkbox" id="tiramisu" value="Tiramisu" v-model="dishes">
        <label for="tiramisu">Tiramisu</label>
        <br>
        <span>ausgewählte Speisen: {{dishes}}</span>
        
      </div>
    </div>
</template>

<script>
    export default {
      name: "Speisekarte",
      data: {
        dishes: []
      }
    }
</script>

<style>
.container {
  background-color: #5F6A6A;
  margin: 0 auto;
  min-height: 100vh;
  width: 100%;
  position: absolute;
  align-items: center;
  text-align: center;
}

.head {
  background-color: #424949;
  height: 250px;
  width: 100%;
  position: absolute;
  align-items: center;
  text-align: center;
}

.inhalt{
  background.color: #5F6A6A;
  width: 100%;
  height: 850px;

  top: 250px;
  position: absolute;

  color: white;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #5DADE2;
  letter-spacing: 1px;
}

img{
  align: center;
  width: 100%;
  height: 100%;
}

h2
{
  color: white;
}

.links {
  padding-top: 15px;
}

</style>
