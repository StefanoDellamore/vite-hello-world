<script>
// my-component.js
export default {
    data() {
        return { title: 'La mia prima app con Vite!' };
    },
};
</script>

<template>
    <div>
        <h1>
            {{ title }}
        </h1>
    </div>
</template>

<style scoped>
    h1{
        color: red;
        text-align: center;
    }
</style>
