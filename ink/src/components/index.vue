<template>
  <div>
    <new-header></new-header>
    <h1>测试主页</h1>
    <span></span>
  </div>
</template>

<script>

  import  NewHeader from  '@/components/header';
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
    }
  },
  components:{
    NewHeader,
  }
}
</script>

