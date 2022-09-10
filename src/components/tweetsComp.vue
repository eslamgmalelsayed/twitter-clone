<template>
    <div class="home ps-2">
        <h4>home</h4>
        <!-- add tweet -->
        <addTweet />
        <!-- tweet -->
        <tweetComp />
        <tweetComp />
        <tweetComp />
    </div>
</template>

<script>
// imports
import addTweet from './addTweet.vue'
import tweetComp from './tweetComp.vue'
export default {

    name:'tweetsComp',
    components:{
        addTweet,
        tweetComp
    }
}
</script>

<style lang="scss" scoped>

</style>