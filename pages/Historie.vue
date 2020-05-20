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
            to="Speisekarte"
            target="_blank"
            class="button1"
          >
           Speisekarte
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
        <h2>Historie unseres Restaurants</h2>
        <br>
        <p>Im Jahre 1926 eröffnete unser erstes Lokal. Bereits in den ersten Wochen lief das Restaurant gut. Doch wegen der Weltwirtschaftskrise mussten wir das Restaurant in den 30ern schließen. In den 60ern hatten wir wieder die nötigen Mittel um das Restaurant neu zu eröffnen.</p>
        <p>Von da an, waren wir bekannt für unsere hauseigenen Kreationen. Der Laden wurde immer beliebter und ist mittlerweile zu einer touristenaktion geworden.</p>
        <p>Seit neuestem haben wir auch einen eigenen Lieferservice.</p>
      </div>
    </div>
</template>

<script>
    export default {
      name: "Historie"
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
