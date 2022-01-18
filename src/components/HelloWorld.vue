<!--------------> 
<!-- TEMPLATE -->
<!--------------> 
<template>
    <main>
        <div class="login-container d-flex">
            <img class="logo" src="../assets/img/pokedex-red.png">
            <button class="btn pokedex-button">Enter</button>
        </div>
    </main>
</template>



<!---------------->  
<!-- JavaScript -->
<!----------------> 
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>



<!---------> 
<!-- CSS -->
<!---------> 
<style scoped>
main{
    background: #fff url('~@/assets/img/dream-back.png') no-repeat center center / cover;
    position: relative;
    height: 100vh;
}

.logo {
    max-width: 10em;
}

.login-container{
    width: 30em;
    height: 100vh;
    background-color: darkgray;
    right: 0;
    position: absolute;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.pokedex-button{
    margin-top: 1em;
    max-width: 10em;
}
</style>
