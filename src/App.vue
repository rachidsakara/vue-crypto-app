<template>
  
  <div class="container" id="app">
    <section class="section">

      <nav class="level">
        <div class="level-left">
          <router-link to="/" class="level-item button is-black is-outlined is-large">Home</router-link>
          <router-link to="/news" class="level-item button is-black is-outlined is-large">News</router-link>
        </div>
      </nav>
    </section>

    <!--Rendering the componenets will be here-->
    <router-view/>

  </div>

  

</template>

<script>
export default {
  name: 'App'
}
</script>


<style >

section.section{
  width: 70%;
}

section.section{
   margin: auto; 
}

</style>
