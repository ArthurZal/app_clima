<template>
    <Cabecalho />
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