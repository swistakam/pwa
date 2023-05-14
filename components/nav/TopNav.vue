<template>
    <div class="nav">

        <div class="left-nav">
            <span>
                <NuxtLink class="text" to="/">Home nuxt</NuxtLink>
                <NuxtLink class="text" to="/onas">About nuxt</NuxtLink>
            </span>
        </div>
    </div>

</template>

<script>

</script>
<style scoped>
.nav{
    display: flex;
    /* flex-direction: column; */
    background-color: rgb(19, 188, 244);
    border-bottom: 5px solid green;
    height: 100%;
    width: 100%;
    max-height: 50px;
    min-height: 50px;
    max-width: 100vw;
    min-width: 200px;
}
.left-nav{
    padding-top: 8px;
    font-weight: bolder;
    font-size: 30px;
    display: flex;
    flex-direction: row;
}
.text{
    color: whitesmoke;
    text-decoration: none;
    padding: 10px;
    
}

.item{
    border: 3px solid blue;
    max-height: 100px;
    min-height: 100px;
    max-width: 100px;
    min-width: 100px;

}

.item2{
    display: flex;
    flex-direction: column;
}

</style>