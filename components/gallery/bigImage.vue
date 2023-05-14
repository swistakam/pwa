<template>
    <div>
        <img :src="image" class="img" />
    </div>
</template>

<script>
export default {
  name: 'BigImage',
  props:{
    image:{
        type: String,
        default: () => 'Pusty string'
    }
  }

}
</script>
<style scoped>
.img{
    min-width: 300px;
    max-width: 500px;
    margin: 2px;
}
</style>