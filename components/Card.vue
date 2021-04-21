<template>
    <div class="card">
        <img class="card-img-top" :src="require(`~/assets/img/${item.src}.png`)" alt="Card image cap">
        <div class="card-body rounded-top">
            <h5 class="card-title text-baloo font-weight-bolder">{{ item.title }}</h5>
            <p class="card-text text-nunito">{{ item.description }}</p>
            <a href="#" class="text-danger text-nunito font-weight-bolder">Lebih Lanjut</a>
        </div>
    </div>
</template>

<script>
export default {
    props: [ 'item' ]
}
</script>