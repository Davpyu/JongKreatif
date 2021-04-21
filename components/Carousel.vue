<template>
    <div>
        <b-carousel
            id="carousel-1"
            v-model="slide"
            :interval="4000"
            controls
            indicators
            img-width="1024"
            img-height="480"
            style="text-shadow: 1px 1px 2px #333;"
            @sliding-start="onSlideStart"
            @sliding-end="onSlideEnd"
        >
            <b-carousel-slide img-blank img-blank-color="red">
                <h1 class="text-white">Build Your Experience</h1>
                <p class="text-white">Build better customer relationships easily messaging that provides a more personal experience for you and your customers.</p>
                <button type="button" class="rounded text-danger btn btn-light">Get to Know</button>
            </b-carousel-slide>

            <b-carousel-slide img-blank img-blank-color="red">
                <h1 class="text-white">Build Your Experience</h1>
                <p class="text-white">Build better customer relationships easily messaging that provides a more personal experience for you and your customers.</p>
                <button type="button" class="rounded text-danger btn btn-light">Get to Know</button>
            </b-carousel-slide>

            <b-carousel-slide img-blank img-blank-color="red">
                <h1 class="text-white">Build Your Experience</h1>
                <p class="text-white">Build better customer relationships easily messaging that provides a more personal experience for you and your customers.</p>
                <button type="button" class="rounded text-danger btn btn-light">Get to Know</button>
            </b-carousel-slide>
        </b-carousel>
    </div>
</template>