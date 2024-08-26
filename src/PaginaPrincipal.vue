<template>
    <Cabecalho>
        <template v-slot:subtitulo>
            <h2>Subtítulo aqui</h2>
        </template>

        <template v-slot:extra>
            <h3>Texto Extra </h3>
        </template>

    </Cabecalho>

    <ListaDeCidades/>

</template>

<script>

import './assets/estilo.css'
import Cabecalho from './components/Cabecalho.vue';
import ListaDeCidades from './components/ListaDeCidades.vue';


export default {
    components: { Cabecalho, ListaDeCidades },
    
}
</script>

<style scoped>

</style>