<template>
  <div>
    <h2>user page</h2>
    <h2>{{userId}}</h2>
  </div>
</template>

<script>
  export default {
    name: "User",
    computed:{
      userId(){
        return this.$route.params.userId
      }
    }
  }
</script>

<style scoped>

</style>