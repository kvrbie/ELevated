<script setup lang="ts"></script>

<template>
    <div>
        <h1 class="text-5xl">This page's slug is:</h1>
        <p class="text-2xl text-gray-600">
            {{ $route.params.slug }}
        </p>
    </div>
</template>
