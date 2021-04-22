<template>
    <div class="p-2 d-flex">
        <div
            class="flex-shrink-0 w-1 mr-4" 
            v-if="item.position === 'left'"
            :class="{ 'bg-danger': item.active === true, 'bg-dark opacity-10': item.active === false }"
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
            class="flex-shrink-0 w-1 ml-4" 
            v-if="item.position === 'right'"
            :class="{ 'bg-danger': item.active === true, 'bg-dark opacity-10': item.active === false }"
        ></div>
    </div>
</template>

<script>
export default {
    props: ['item']
}
</script>

<style scoped>
    .w-1 {
        width: 0.25rem;
    }

    .flex-shrink-0 {
        flex-shrink: 0;
    }
</style>