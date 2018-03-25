<template>
  <div >
    <h1>{{ msg }} - {{$route.params.username}}</h1>
  </div>
</template>

<script>
export default {
  name: 'Hi1',
  data () {
    return {
      msg: 'Hi, No1!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
