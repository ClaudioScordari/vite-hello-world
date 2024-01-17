<script>
// Importazione file 
import AppTitle from './components/AppTitle.vue';

    export default {
        data() {
            return { 
                count: 0 
            }
        },
        // Dichiarazione dei componenti
        components: {
            AppTitle
        }
    }
</script>

<template>
    <div>
        <!-- Utilizzo del componente -->
        <div>
            <h1>
                <AppTitle/>
            </h1>
        </div>
    </div>
</template>

<style scoped>

</style>
