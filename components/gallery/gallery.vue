<template>
    <div class="gallery">
      <div v-for="image in images" :key="image.id" class="image-container">
        <img :src="image.url" alt="Image" @click="openImage(image)">
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        images: [
          { id: 1, url: 'https://fotoforma.pl/environment/cache/images/500_500_productGfx_21838/Aparat-cyfrowy-Sony-A6600---obiektyw-18-135mm-czarny-ILCE6600MB-SEL18135.jpg' },
          { id: 2, url: 'https://www.mediaexpert.pl/media/cache/resolve/gallery/images/18/1826207/Aparat-SONY-A6400-Czarny-Obiektyw-16-50mm-skos.jpg' },
          { id: 3, url: 'https://image.ceneostatic.pl/data/products/75126786/38ee0ef1-7b72-4c89-afe1-a9ce63b39906_i-sony-a6400-czarny-body.jpg' },
       
        ]
      };
    },
    methods: {
      openImage(image) {
      
      }
    }
  };
  </script>
  
  <style>
  .gallery {
    display: flex;
    flex-wrap: wrap;
  }
  
  .image-container {
    margin: 10px;
    cursor: pointer;
  }
  
  img {
    width: 200px;
    height: auto;
  }
  </style>
  