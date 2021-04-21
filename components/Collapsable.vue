<template>
    <div class="p-2 d-flex justify-content-center">
        <div
            class="mr-4" 
            v-if="item.position === 'left'"
            :class="{ 'bg-danger w-4': item.active === true, 'bg-dark text-opacity-10 w-px': item.active === false }"
        ></div>
        <div>
            <h5 class="text-left font-weight-bold text-nunito">
                {{item.question}}
            </h5>
            <p v-if="item.active === true" class="mt-1 text-left text-nunito">
                {{item.answer}}
            </p>
        </div>
        <div
            class="ml-4" 
            v-if="item.position === 'right'"
            :class="{ 'bg-danger w-4': item.active === true, 'bg-dark text-opacity-10 w-px': item.active === false }"
        ></div>
    </div>
</template>

<script>
export default {
    props: ['item']
}
</script>

<style scoped>
    .w-4 {
        width: 1rem;
    }

    .w-px {
        width: 5.58px;
    }
</style>