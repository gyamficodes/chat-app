<template>
 
    
     
    <md-card  class=""  md-with-hover>
      <md-ripple>
        <md-card-header>
          <div class="md-title">Authenticstion</div>
          <div class="md-subhead">Please register to login first</div>
        </md-card-header>

        <md-card-content>
          <md-field>
      <label>Password toggle</label>
      <md-input v-model="password" type="password"></md-input>
    </md-field>
        </md-card-content>

        <md-card-actions>
          <md-button>LOGIN</md-button>
          <md-button>SIGNUP</md-button>
        </md-card-actions>
      </md-ripple>
    </md-card>


</template>

<script>

    export default {
         name: 'LogIn',
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
@import'../assets/CSS/LogInPage';
</style>