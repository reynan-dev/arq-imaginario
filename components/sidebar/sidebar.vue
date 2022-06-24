<template>

    <div class="grid-sidebar">
        <div class="identify">
            <img src="" alt="">
            <h1>Arquitura do Imáginario</h1>
        </div>
        <nav>
            <ul>
                <li>
                    <div class="icon"></div>
                    <div class="text"><a href="/projetos">Projetos</a></div>
                </li>
                <li>
                    <div class="icon"></div>
                    <div class="text"><a href="/ruido-coletivo">Ruido Coletivo</a></div>
                </li>
                <li>
                    <div class="icon"></div>
                    <div class="text"><a href="/modulares">Modulares</a></div>
                </li>
                <li>
                    <div class="icon"></div>
                    <div class="text"><a href="/project">Project</a></div>
                </li>
            </ul>
        </nav>
        <footer>
            <p>&copy; 2022. Todos os direitos reservados</p>
            <p>Projeto feito por <a href="https://reynan.dev">reynan.dev</a></p>
        </footer>
    </div>

</template>

<script lang="ts">

import Vue from "vue";
export default Vue.extend({
    name: "Sidebar",
})

</script>