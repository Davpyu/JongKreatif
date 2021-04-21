<template>
    <div>
        <b-carousel
            id="carousel-1"
            v-model="slide"
            :interval="4000"
            controls
            indicators
            @sliding-start="onSlideStart"
            @sliding-end="onSlideEnd"
        >
            <div class="p-5 text-center carousel-item bg-danger text-light">
                <div class="p-5 d-flex flex-column align-items-center justify-content-center" style="height: 480px">
                    <h1 class="text-baloo font-weight-bolder display-4">Build Your Experience</h1>
                    <div class="w-75">
                        <p class="text-nunito">Build better customer relationships easily messaging that provides a more personal experience for you and your customers.</p>
                    </div>
                    <b-button variant="light" class="rounded-full text-danger text-baloo font-weight-bolder">Get to Know</b-button>
                </div>
            </div>

            <div class="p-5 text-center carousel-item bg-danger text-light">
                <div class="p-5 d-flex flex-column align-items-center justify-content-center" style="height: 480px">
                    <h1 class="text-baloo font-weight-bolder display-4">Build Your Experience</h1>
                    <div class="w-75">
                        <p class="text-nunito">Build better customer relationships easily messaging that provides a more personal experience for you and your customers.</p>
                    </div>
                    <b-button variant="light" class="rounded-full text-danger text-baloo font-weight-bolder">Get to Know</b-button>
                </div>
            </div>

            <div class="p-5 text-center carousel-item bg-danger text-light">
                <div class="p-5 d-flex flex-column align-items-center justify-content-center" style="height: 480px">
                    <h1 class="text-baloo font-weight-bolder display-4">Build Your Experience</h1>
                    <div class="w-75">
                        <p class="text-nunito">Build better customer relationships easily messaging that provides a more personal experience for you and your customers.</p>
                    </div>
                    <b-button variant="light" class="rounded-full text-danger text-baloo font-weight-bolder">Get to Know</b-button>
                </div>
            </div>
        </b-carousel>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                slide: 0,
                sliding: null
            }
        },
        methods: {
            onSlideStart(slide) {
                this.sliding = true
            },
            onSlideEnd(slide) {
                this.sliding = false
            }
        }
    }
</script>

<style scoped>
    .carousel-item.active {
        display: block;
    }
</style>