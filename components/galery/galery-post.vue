<template>
    <div class="posts"> </div>
</template>

<script lang="ts">
import Vue from 'vue';
export default Vue.extend({
    name: "GaleryPost",
    props: {
        title: "" as string,
        descriptions: "" as string,
    }
})
</script>