<template>
    <div class="mt-2 col-sm-6 col-lg-4" :class="{ 'mt-sm-0': index < 2, 'mt-lg-0': index === 2 }">
        <div class="card">
            <img class="card-img-top" :src="require(`~/assets/img/${item.src}.png`)" alt="Card image cap">
            <div class="card-body rounded-top">
                <h5 class="card-title text-baloo font-weight-bolder">{{ item.title }}</h5>
                <p class="card-text text-nunito">{{ item.description }}</p>
                <a href="#" class="text-danger text-nunito font-weight-bolder text-decoration-none">Lebih Lanjut</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: [ 'item', 'index' ]
}
</script>