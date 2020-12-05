<template>
  <div id="app">
    <div class="container">
        <EadLogin />
    </div>
  </div>
</template>
<script>


  import EadLogin from './components/pages/EadLogin';
  
  export default {
    name: 'app',
    components: {
      EadLogin
    }
  }
</script>
<style>

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Montserrat;
  }
  body{
    background-color:#121214;
  }
  .container{
      max-width: 1440px;
  }
</style>
