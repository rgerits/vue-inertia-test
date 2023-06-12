<script>
import { red import vue routerf } from "vue";

const active = ref(false);
</script>

<template>
    <router-link
        class="text-blue-500 hover:underline"
        :class="{
            'font-bold underline': active,
        }"
    >
        <slot />
    </router-link>
</template>
install vue router
