<template>
  <div>
    <h2>档案</h2>
    <h2>name: {{name}}</h2>
    <h2>age: {{age}}</h2>
  </div>
</template>

<script>
  export default {
    name: "Profile",
    computed: {
      name() {
        return this.$route.query.name
      },
      age() {
        return this.$route.query.age
      }
    }
  }
</script>

<style scoped>

</style>