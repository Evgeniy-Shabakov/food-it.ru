<script setup>
defineProps({
    qtyItemsInList: {
        type: Number,
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

            <ul class="list-disc text-gray-600">
                <li v-if="1 <= qtyItemsInList">
                    <slot name="li_1"></slot>
                </li>
                <li v-if="2 <= qtyItemsInList">
                    <slot name="li_2"></slot>
                </li>
                <li v-if="3 <= qtyItemsInList">
                    <slot name="li_3"></slot>
                </li>
                <li v-if="4 <= qtyItemsInList">
                    <slot name="li_4"></slot>
                </li>
                <li v-if="5 <= qtyItemsInList">
                    <slot name="li_5"></slot>
                </li>
                <li v-if="6 <= qtyItemsInList">
                    <slot name="li_6"></slot>
                </li>
                <li v-if="7 <= qtyItemsInList">
                    <slot name="li_7"></slot>
                </li>
                <li v-if="8 <= qtyItemsInList">
                    <slot name="li_8"></slot>
                </li>
                <li v-if="9 <= qtyItemsInList">
                    <slot name="li_9"></slot>
                </li>
            </ul>

        </div>

    </div>
</template>