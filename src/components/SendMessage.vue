<template>
      
    <div class="textA" >
     <div class="text">
        <md-field>
      <label>Say hi...</label>
      <md-textarea   v-model="message"   md-counter="200" ></md-textarea>
    </md-field>
     </div>
    
    <div class="btn">
    <span  class=" material-icons" style="margin-top: 30px; cursor:pointer; color:blue;">send</span>
    </div>

    </div>
</template>

<script>

    export default {
        name:'SendMessage',
        components:{},
        props:[],
        data(){
            return{
                message: '',
            }
        },
        computed:{},
        mounted(){},
        watch:{}
    }
</script>

<style lang="scss">
@import'../assets/CSS/SendMessage';
</style>