<template>
    <div class="h-screen flex-col bg-red-500">
        <div class="p-2 my-2 hover:bg-red-300 hover:rounded-full w-min
        dark:hover:bg-white/20" :class="defaultTransition">
            <NuxtLink to="/">
                <div class="w-8 h-8">
                    <LogoTwitter />
                </div>
            </NuxtLink>
        </div>
    </div>
</template>
<script setup>
    
</script>