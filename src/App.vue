<script>
//1)importazione
import AppHeader from './components/AppHeader.vue';
export default {
    data() {
        return { count: 0 };
    },
    //2)dichiarazione componenti
    components: {
        AppHeader
    }
};
</script>

<template>
    <div>
        <!--3)dichiarazione componenti--> 
        <AppHeader/>
    </div>
</template>

<style scoped>
    /* */
</style>
