<template>
 
    <div class="wrapper">
      <md-card  class="" >
      
      <md-card-header>
        <div class="md-title">Authenticstion</div>
        <div class="md-subhead">Please register to login first</div>
      </md-card-header>

      <md-card-content>
        <md-field class="ip">
    <label>Username</label>
    <md-input v-model="Username" type="text"></md-input>
  </md-field>
  <md-field class="ip">
    <label>Password</label>
    <md-input v-model="password" type="password"></md-input>
  </md-field>
      </md-card-content>

      <md-card-actions>
        <md-button>LOGIN</md-button>
        <md-button>SIGNUP</md-button>
      </md-card-actions>
  
  </md-card>

    </div>
     
   

</template>

<script>

    export default {
         name: 'LogIn',
        data(){
            return{
            Username:'',
            password:'',
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
@import'../assets/CSS/LogInPage';
</style>