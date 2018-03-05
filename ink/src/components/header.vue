<template>
    <div class="head">
        <div class="container">
            <div class="logo">MarryBlog...</div>
            <nav>
                <ul>
                  <li><a href="">Home</a></li>
                  <li><a href="">GitHub</a></li>
                  <li><a href="">works</a></li>
                  <li><a href="">About</a></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
  import  '../assets/css/base.css';
  export default {
    data () {
      return {
        msg: 'Welcome to Your Vue.js App',
      }
    }
  }
</script>
<style>
  .head{background-color: #24292e;height: 60px;}
  .container{width: 1200px;margin: 0 auto;}
  .logo{float: left;font-size: 26px;color:#fff;line-height:60px;}
  .head nav{float: right;}
  .head nav li{display: block;font-size: 14px;color: #fff;padding: 0 28px ;line-height: 60px;float:left;cursor: pointer;}
  .head nav li a{color: #fff;}
</style>
