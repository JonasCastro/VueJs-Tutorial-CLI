<template>
<ul>
    <li v-for="ninja in ninjas" v-bind:key='ninja'>{{ ninja }}</li>
</ul>
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

<style>
</style>
