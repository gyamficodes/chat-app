<template>
  <div id="app">
    <!-- <nav> -->
      <!-- <router-link to="/"></router-link> 
      <router-link to="/about"></router-link>
    </nav>
    <router-view/>
   -->
   <LogIn>
    <md-card  class="md-accent"  md-with-hover>
      <md-ripple>
        <md-card-header>
          <div class="md-title">Authenticstion</div>
          <div class="md-subhead">Please register to login first</div>
        </md-card-header>

        <md-card-content>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio itaque ea, nostrum odio. Dolores, sed accusantium quasi non.
        </md-card-content>

        <md-card-actions>
          <md-button>LOGIN</md-button>
          <md-button>SIGNUP</md-button>
        </md-card-actions>
      </md-ripple>
    </md-card>
   </LogIn>
  </div>
</template>

<script>
import LogIn from './components/LogIn.vue';

 export default {
         name: 'App',
         props:{},
         components:{
          LogIn
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
