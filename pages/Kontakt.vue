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
            to="Speisekarte"
            target="_blank"
            class="button1"
          >
            Speisekarte
          </nuxt-link>
          <nuxt-link 
            to="Historie"
            target="_blank"
            class="button1"
          >
            Historie unseres Restaurants
          </nuxt-link>
          <nuxt-link 
            to="Gästebuch"
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
        <div class="Daten">
          <h1>Kontakt</h1>
          <p>Da Vinci Restaurant</p>
          <p>Leonardo Da Vinci</p>
          <p>Kanalstraße 345</p>
          <p>56394 Universalstadt</p>
          <p>Tel.: 016263965281</p>
          <p>E-Mail: da.vinci@gmx.de</p>
        </div>
        <div class="Bild">
          <img src="Leonardo.jpg">
          <p>Geschäftsführer: Leonardo Da Vinci</p>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
      name: "Kontakt"
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

.Daten{
  border: solid #5DADE2;
  height: 270px;
  width: 280px;

  background-color: #5F6A6A;
  padding: 50px;
  color: white;
}

.Bild{
  background-color: #5F6A6A;
  border: solid #5DADE2;
  height: 400px;
  width: 400px;

  top: 300px;
  right: 50px;
  float: right;

  padding: 50px;
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
