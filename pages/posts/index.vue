<template>
    <head>
        <Title>Posts</Title>
    </head>
    <h2>Post list</h2>

    <div>
        <ul>
            <li><NuxtLink to="/posts/1">Primer post</NuxtLink></li>
            <li><NuxtLink to="/posts/2">Segundo post</NuxtLink></li>
            <li><NuxtLink to="/posts/3">Tercer post</NuxtLink></li>
        </ul>
    </div>
</template>

<style scoped>
ul{
    list-style: none;
}
</style>
