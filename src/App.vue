<script>
  export default {
  data() {
    return {
      name: ''
    }
  },
  methods:{
    setName(){
      this.name = 'johnjohn'
    }  
  }
}
</script>

<template>
  <div>
    <button :type="button" @click="setName">{{name.length? name : 'no name'}}</button>
  </div>
</template>

