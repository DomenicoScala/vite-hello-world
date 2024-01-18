<script>
    /* 1) Importazione del componente */
    import AppTitle from './components/AppTitle.vue';
    
    export default {
        data() {
            return { count: 0 }
        },
        /* 2) Dichiarazione del Componente */
        components:{
            AppTitle
        }
    }
</script>

<template>
    <!-- 3) UTILIZZO DEL COMPONENTE -->
    <AppTitle/>
        
</template>

<style scoped>

</style>
