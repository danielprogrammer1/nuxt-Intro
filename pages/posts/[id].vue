<template>
    <head>
        <Title>Post {{ id }}</Title>
    </head>
    <h2>Bienvenido al post # {{ id }}</h2>
</template>

<script setup>
    const { id } = useRoute().params

    

    definePageMeta({
        validate: async (route) => {
            const nuxtApp = useNuxtApp();

            if (!/^[0-9]+$/.test(route.params.id)){
                throw createError
                ({
                    statusCode:"500",
                    statusMessage:"Param type is invalid"
                });
            }
            return true;
        }
    })
</script>
