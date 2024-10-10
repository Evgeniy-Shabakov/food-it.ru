<template>

    <div class="bg-white p-6 rounded-lg shadow-md text-center">
        <div
            class="w-12 h-12 bg-blue-500 text-white rounded-full flex items-center justify-center mx-auto mb-4 text-xl font-bold">
            <slot name="number"></slot>
        </div>
        <h3 class="text-xl font-semibold mb-2">
            <slot name="h3"></slot>
        </h3>
        <p class="text-gray-600">
            <slot name="p"></slot>
        </p>
    </div>

</template>
