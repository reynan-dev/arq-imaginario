<template>
    <div class="grid-content">
        <div class="high">
            <PrimaryPost></PrimaryPost>
        </div>

        <div class="split">
            <SecundaryPost></SecundaryPost>
            <SecundaryPost></SecundaryPost>
        </div>
        <h2>Esses são nossos xodós</h2>
        <div class="three">
            <TerciaryPost></TerciaryPost>
            <TerciaryPost></TerciaryPost>
            <TerciaryPost></TerciaryPost>
        </div>
        <h2>Você também vai gostar desses</h2>
        <div class="galery">
            <GaleryPost></GaleryPost>
            <GaleryPost></GaleryPost>
            <GaleryPost></GaleryPost>
            <GaleryPost></GaleryPost>
            <GaleryPost></GaleryPost>
            <GaleryPost></GaleryPost>
        </div>
    </div>
</template>

<script lang="ts">
import Vue from "vue";
import PrimaryPost from "./primary-post.vue";
import SecundaryPost from "./secundary-post.vue";
import TerciaryPost from "./terciary-post.vue";
import GaleryPost from "../galery/galery-post.vue";
export default Vue.extend({
    name: "feed",
    components: { PrimaryPost, SecundaryPost, TerciaryPost, GaleryPost }
})</script>