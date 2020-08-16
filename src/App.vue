<template>
<div>
    <h1>{{ title }}</h1>
    <p>{{greeting()}}</p>
</div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      title: 'Hello',
    }
  },
  methods:{
    greeting: function(){
        return  'World'

    }
  }
}
</script>

<style>
</style>
