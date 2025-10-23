<template>
    <footer class="flex flex-row bg-brand-white p-8">
        <section class="flex flex-col w-64">
            <NuxtLink href="/">
                <img src="~/assets/Logo.png" class="w-48" alt="">
            </NuxtLink>
            <p>Questions?</p>
            <p>If you need any questions, comments or concerns answered, please <NuxtLink href="/contact" class="underline">contact us.</NuxtLink></p>
        </section>
        <section class="flex flex-col">
            <p class="mb-2">Links</p>
            <nav class="flex flex-col">
                <NuxtLink href="/">
                    Home
                </NuxtLink>
                <NuxtLink href="/about">
                    About Us
                </NuxtLink>
                <NuxtLink href="/services">
                    Services
                </NuxtLink>
                <NuxtLink href="/blog">
                    Blog
                </NuxtLink>
                <NuxtLink href="/contact">
                    Contact Us
                </NuxtLink>
            </nav>
        </section>
    </footer>
</template>
