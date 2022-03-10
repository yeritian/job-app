<template>
<div class="box">
    <TitleCom>
        <div class="btn">招聘广场</div>
    </TitleCom>
    <div class="select-box">
        <div class="search-box">
            <input type="text" placeholder="招聘">
            <img src="../assets/search.png" alt="">

        </div>
    </div>
</div>
</template>
<script>
import TitleCom from '@/components/TitleCom.vue'
import {defineComponent } from 'vue'
export default defineComponent ({
setup(){
 return{}
},
components:{
    TitleCom
}
})
</script>
<style lang="scss" scoped>
.btn{
    font-size: 20px;
    font-weight: 600;
    color:cadetblue;
    border:1px solid cadetblue;
    cursor: pointer;
    padding: 10px 5px;
    border-radius: 5px;
}
.box{
    width: 1000px;
    margin: 0 auto;
    box-shadow: 0 6px 18px #999;
}
</style>