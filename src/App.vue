<template>
  <div id="app">
    <!-- <nav> -->
      <!-- <router-link to="/"></router-link> 
      <router-link to="/about"></router-link>
    </nav>
    <router-view/>
   -->
   <!-- <LogIn/> -->
<ChatsPage/>
    </div>
</template>

<script>
import ChatsPage from '@/components/ChatsPage.vue';

 export default {
         name: 'App',
         props:{},
         components:{
          ChatsPage
         },
        data(){
            return{
            
             }
        },
        methods:{
        
        },
        computed:{},
        watch:{},
        mounted(){
          
        }
    }
</script>

 <style lang="scss">
@import'./assets/CSS/LogInPage';
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}



nav {
  // padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
