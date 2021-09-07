<template>
  <div >
    <h1 v-show="isShow">Đây Là Menu</h1>
    <button @click="isShow =! isShow">An/Hien</button>
  </div>

</template>

<script>
export default {
    data(){
        return{
            isShow:true
        };
    }
}
</script>

<style scoped>
</style>