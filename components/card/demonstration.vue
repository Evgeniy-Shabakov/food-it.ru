<script setup>
defineProps({
    link: {
        type: String,
        required: true
    }
})
</script>

<template>
    <div class="flex">

        <div class="mr-4 h-8 w-8 flex-shrink-0">
            <slot name="icon"></slot>
        </div>

        <div>
            <h3 class="text-xl font-semibold mb-2">
                <slot name="h3"></slot>
            </h3>
            <p class="text-gray-600">
                <slot name="p"></slot>
            </p>
            <a :href="link" class="block py-2 underline hover:text-yellow-800 active:text-yellow-500" target="_blank">
                {{ link }}
            </a>
        </div>

    </div>
</template>