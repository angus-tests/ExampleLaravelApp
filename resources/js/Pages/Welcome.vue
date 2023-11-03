<script setup>
import { Head, Link } from '@inertiajs/vue3';
import GuestLayout from "@/Layouts/GuestLayout.vue";
import PageContainer from "@/Components/_util/PageContainer.vue";

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <GuestLayout title="Home">
        <PageContainer>
            <h1 class="h1"> Welcome to Laravellous </h1>
            
        </PageContainer>
    </GuestLayout>
</template>

