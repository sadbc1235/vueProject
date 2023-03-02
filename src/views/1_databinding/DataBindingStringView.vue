<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userName: 'John Doe',
      msg: 'Welcome KES'
    }
  }
}
</script>

<style scoped>
.text-red {
  color: red;
}
</style>
