<script setup>
defineProps({
    h3Visible: {
        type: Boolean,
    }
})
</script>

<template>

    <article class="bg-white p-6 rounded-lg shadow-md">

        <h3 v-if="h3Visible" class="text-xl font-semibold mb-4">
            <slot name="h3"></slot>
        </h3>
        <div class="text-gray-600">
            <slot name="div"></slot>
        </div>

    </article>

</template>
