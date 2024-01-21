<script>
export default {
  name: 'App',
  data(){
    return {
      message: 'Ciao, benvenuto in questo nuovo esercizio!',
      image: 'https://picsum.photos/200/300'
    }
  }
}
</script>

<template>
  <header>
    <h1>{{ message }}</h1>
  </header>
  
  <main>
    <div>
      <img v-bind:src="image" alt="lorem picsum">
    </div>
  </main>

  <footer>

  </footer>
</template>

<style>
</style>
