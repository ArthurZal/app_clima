<template>
    <div class="card">
        <div class="card-img"></div>
        <h3>{{ cidade.name }}</h3>
        <h4>{{ cidade.description }}</h4>
        <div class="temperatura">{{ cidade.temp }}º</div>
    </div>
</template>

<script>
export default {
    props: {
        cidade: Object
    },
};
</script>

<style>

</style>