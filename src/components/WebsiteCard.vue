<template>
    <v-card
        class="website-card"
        min-width="400"
        max-width="500"
        prepend-avatar="https://cdn.vuetifyjs.com/images/lists/1.jpg"
        title="Minecraft"
    >
        <v-card-text
            @mouseenter="
                () => {
                    console.log('enter');
                }
            "
            @mouseleave="
                () => {
                    console.log('leave');
                }
            "
        >
            我的世界官方网站
        </v-card-text>
    </v-card>
</template>

<script setup lang="ts"></script>

<style scoped>
    .website-card {
    }
    .website-card:hover {
        background-color: #f9f9f9;
        transform: scale(1.05);
        transition: all 0.3s;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
</style>
