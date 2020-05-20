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
            to="Historie"
            target="_blank"
            class="button1"
          >
            Historie unseres Restaurants
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
        <h1>Gästebuch</h1>
        <br>        
        <p>Hallo liebe Gäste,</p>
        <p>hier können Sie uns einen netten Kommentar dalassen. Ganz gleich, ob Lob oder Kritik, wir lesen uns alles durch.</p>
      </div>
     <!-- <div id="Komfeld">
        <p>Kommentar von:</p>
        {{vorname, email, Kommentar}}
        
         Name: {{vorname}} <br>
         E-Mail: {{email}} <br>
         Kommentar: {{Kommentar}}
        <p v-for="vorname in kommentare"></p>
        <p v-for="email in kommentare"></p>
        <p v-for="Kommentar in kommentare"></p>
        
              <br>
        <input v-model="vorname" placeholder="Name">
        <br>
        <input v-model="email" placeholder="E-Mail">
        <br>        
        <input v-model="Kommentar" placeholder="Schreibe einen Kommentar">
        <button @click="senden">Senden</button>
      </div>-->
    </div>
</template>

<script>
    export default {
      name: "Gaestebuch",
        data(){
          
          /*
        },
        methods:({
          addText: function(){
            this.kommentare.push{
              vorname:"",
              email:"",
              Kommentar:""
            });
            */
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
  height: 500px;

  top: 250px;
  position: absolute;

  color: white;
  padding: 30px;
}

#Komfeld{
  background.color: #5F6A6A;
  border-style: groove;
  width: 800px;
  height: 300px;

  left: 30px;
  top: 400px;
  position: absolute;
  color: white;
  text-align: left;
  padding: 10px;
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

p{
  text-align: left;
}

</style>
