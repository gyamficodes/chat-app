<template>
    <div class="wrapper">
     <div class="md-app">
        <div class="navbar">
            <span style="color: #fff;">my title</span>
        </div>
        <div class="chat-area">
            <MessagePage/>
        </div>
        <div class="footer"></div>
     </div>
    </div>
   
</template>

<script>
import MessagePage from '@/components/MessagePage.vue';


    export default {
        name:'ChatsPage',
        components:{
            MessagePage,
        },
        props:[],
        data(){
            return{}
        },
        computed:{},
        mounted(){},
        watch:{}
    }
</script>

<style lang="scss">
@import'../assets/CSS/ChatArea';
</style>