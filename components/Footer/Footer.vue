<template>

        <footer class="mt-5 bg-dark text-white p-3">
            &copy; Daniel Restrepo - {{ currentYear }}
        </footer>

</template>

<script  setup>
    const currentYear = new Date().getUTCFullYear()
</script>

<style scoped>
    footer{
        position: absolute;
        bottom: 0;
        width: 100%;
    }
</style>
