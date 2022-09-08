<template>
    <div class="links">
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-twitter"></i></a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-house"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">home</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-hash"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">explore</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-alarm"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">notifications</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-envelope"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">messages</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-bookmark"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">bookmarks</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-card-list"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">lists</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-person"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">person</a>
        </div>
        <div class="single-link">
            <a href="#"><i class="fs-3 pe-3 bi bi-three-dots"></i></a>
            <a class="fs-5 d-xl-inline d-none" href="#">more</a>
        </div>
        <!-- button -->
        <button class="rounded-5 py-2 mb-3 fw-bold w-75 d-xl-inline d-none">Tweet</button>
        <!-- card -->
        <div class="card border-0 mt-2">
        <div class="row g-0 px-xl-3">
            <div class="col-xl-2 col-12 text-xl-end">
                <a href="#"><img src="../assets/images/logo.png" class="img-fluid" alt="logo"></a>   
            </div>
            <div class="col-xl d-xl-inline d-none">
            <div class="card-body">
                <h5 class="card-title">Esi <br><span class="text-muted fs-6">@esi944</span></h5>
            </div>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'sideComp'
}
</script>

<style lang="scss" scoped>
.links{
    .single-link{
        height: fit-content;
        margin-bottom: 1.4rem;
        a{     
            text-decoration: none;
            color: #fff;
        }
    }
    button{
        height: fit-content;
        background: #1A8CD8;
        // border-radius: 50%;
    }
    img{
        @media(max-width:1200px){
            width: 40px;
            height: 30px;
        }
    }
}
</style>