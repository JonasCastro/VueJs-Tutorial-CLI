<template>
  <div>
    <h1>List of ninjas</h1>
    <ul>
        <li v-for="ninja in ninjas" v-bind:key='ninja'>{{ ninja }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      ninjas:['Yoshi','Mario', 'Ryu'],
    }
  }
}
</script>

<style scoped>

  h1{
    color: blue;
  }
</style>
