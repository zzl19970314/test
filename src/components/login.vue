<template>
<div class="box">
    <div class="top">登录</div>
    <router-link to='/index'>首页</router-link>
</div>
</template>
<script>
export default {
components:{
 },
data () {
 return {
 }
},
methods:{
},
mounted(){
}
}
</script>
<style scoped lang='stylus'>
@import '../stylus/index.styl'
.box
    width 100vw
    height 400px
    background $bgColor
    color $color
    .top
        width 100px
        height 100px
        background $color


</style>