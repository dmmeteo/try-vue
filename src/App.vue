<template>
  <div>
    <h1>{{title}}</h1>
    <ninjas />
  </div>
</template>

<script>
import Ninjas from './components/Ninjas.vue';

export default {
  data(){
    return {
      title: 'Ninja app'
    }
  },
  components: {
    'ninjas': Ninjas
  }
}
</script>

<style>

</style>
