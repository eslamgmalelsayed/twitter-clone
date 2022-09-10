<template>
    <div>
        <!-- search comp -->
        <searchComp />
        <!-- recent comp -->
        <div class="recent my-3 p-3 ms-2 rounded">
            <h5>what's happening</h5>
            <p class="text-muted">sports - yesterday</p>
            <!--recent news comp -->
           <recentNewsComp/>
            <recentNewsComp/>
            <recentNewsComp/>
        </div>
        <div>
        </div>
    </div>
</template>

<script>
// imports
import searchComp from './searchComp.vue'
import recentNewsComp from './recentNewsComp.vue'
export default {
    name:'sideComp',
    components:{
        searchComp,
        recentNewsComp
    },
}
</script>

<style lang="scss" scoped>
.recent, h5,p{
    background: #16181C;
}
</style>