<template>
    <div class="search">
        <div class="input-group mb-3">
            <i class="bi bi-search"></i>
            <input type="text" class="form-control rounded-5 ms-1 py-2" placeholder="search twitter" aria-label="Username" aria-describedby="basic-addon1">
        </div>
    </div>
</template>
<script>
export default {
    name:'searchComp'
}
</script>

<style lang="scss" scoped>

    .search{
        .bi-search{
            position: absolute;
            top: 0;
            left: 6px;
            width: fit-content;
            height: fit-content;
            padding: .4rem;
            z-index: 999;
            background: transparent;
            color: rgb(144, 136, 136);
        }
        input::placeholder{
            color: rgb(144, 136, 136);
            padding-left: 1.3rem;
        }
        input{
            position: relative;
            background: #202327;
            border: none;
            &:focus{
                border: 1px solid #1A8CD8;
            }
        }
    }
</style>