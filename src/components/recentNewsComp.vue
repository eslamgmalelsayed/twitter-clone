<template>
    <div class="news row my-2">
        <div class="col-3">
            <img width="55" class="img-fluid" src="https://sportfive.com/static/media/runner.2fa8a5bf.png" alt="news">
        </div>
        <div class="col">
            <p>some title <span class="text-muted"> 2 hours ago</span></p>
            <h6>some news lorem ipsum and so on</h6>
        </div>
    </div>
</template>

<script>
export default {
    name: 'recentNewsComp'
}
</script>
<style lang="scss" scoped>
   h6,p,img,.col,.col-3{
        background: #16181C;
    }
</style>