<template>
  <div>
    <TopNav />
    <h1>Strona Domowa</h1>
    <div class="images">
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
      <bigImage image="https://www.autocentrum.pl/ac-file/article/5f48dabd7297c10c7904446b/uzywany-volkswagen-golf-iv-1997-2003-poradnik-kupujacego.jpg"/>
    </div>
  </div>
</template>

<script>
import TopNav from '../components/nav/TopNav.vue'
import bigImage from '../components/gallery/bigImage'
export default {
  name: 'IndexPage',
  components: {TopNav, bigImage}
}
</script>

<style scoped>
.images{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
</style>