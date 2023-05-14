<template>
    <div>
        <TopNav />
        <h1> O nas</h1>
        <h2> strona </h2>
        <button @click="showInfo">Kliknij mnie</button>
        <div>
 
        </div>
    </div>

</template>
<script>
import TopNav from '../components/nav/TopNav.vue'
import Gallery from '../components/gallery/gallery.vue'
export default {
  name: 'onas',
  components: {TopNav, Gallery},

  methods:{
    showInfo: ()=>{
        console.log('Witaj w konsoli')
        alert('Witaj')
    }
  }
}

</script>
<style scoped>


</style>