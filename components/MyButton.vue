<template>
  <div>
<h2>我爱中国</h2>
<button @click="count++">爱了{{count}}</button>
 </div>
</template>

<script>
export default {
  name: '',
  data() { 
    return {
        count:0
    }
  },
  components:{
  },
  mounted() {

  },
  methods:{

  },
 }
</script>

<style scoped>
</style>