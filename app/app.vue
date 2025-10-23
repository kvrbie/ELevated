<script setup lang="tsx">
import Footer from "./components/footer.vue";
import Header from "./components/header.vue";
</script>

<template>
    <div class="flex min-h-screen flex-col">
        <Header />
        <main class="flex-1">
            <NuxtPage />
        </main>
        <Footer />
    </div>
</template>
