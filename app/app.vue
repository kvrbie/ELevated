<script setup lang="tsx">
import Footer from "./components/footer.vue";
import Header from "./components/header.vue";
</script>

<template>
    <div class="flex flex-col">
        <Header />
        <main>
            <NuxtPage />
        </main>
        <Footer />
    </div>
</template>
