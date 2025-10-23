<template>
    <footer class="flex flex-row bg-brand-white p-8">
        <section class="flex flex-col w-64">
            <img src="~/assets/Logo.png" class="w-48" alt="">
            <p>Questions?</p>
            <p>If you need any questions, comments or concerns answered, please <NuxtLink href="#" class="underline">contact us.</NuxtLink></p>
        </section>
        <section class="flex flex-col">
            <p class="mb-2">Links</p>
            <nav class="flex flex-col">
                <NuxtLink href="/">
                    Home
                </NuxtLink>
                <NuxtLink href="#">
                    About Us
                </NuxtLink>
                <NuxtLink href="#">
                    Services
                </NuxtLink>
                <NuxtLink href="#">
                    Blog
                </NuxtLink>
                <NuxtLink href="#">
                    Contact Us
                </NuxtLink>
            </nav>
        </section>
    </footer>
</template>
