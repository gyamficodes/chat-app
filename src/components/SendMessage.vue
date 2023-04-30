<template>
      
    <div class="textA" style="display: flex; align-items: center; justify-content: center;height: 100%;">
        <md-field>
      <label>Autogrow</label>
      <md-textarea v-model="autogrow" md-autogrow md-counter="200"></md-textarea>
    </md-field>
    </div>
</template>

<script>

    export default {
        name:'SendMessage',
        components:{},
        props:[],
        data(){
            return{}
        },
        computed:{},
        mounted(){},
        watch:{}
    }
</script>

<style lang="sass" scoped>

</style>