<script setup lang="ts">
import MovieCard from '~/components/MovieCard.vue';
import { VCard, VBtn } from 'vuetify/components';

</script>

<template>
    <VCard
        class="mx-auto"
        color="surface-variant"
        image="https://cdn.vuetifyjs.com/docs/images/cards/dark-beach.jpg"
        max-width="340"
        subtitle="Take a walk down the beach"
        title="Evening sunset">
        <template v-slot:actions>
            <v-btn
                append-icon="mdi-chevron-right"
                color="red-lighten-2"
                text="Book Activity"
                variant="outlined"
                block
            />
        </template>
    </VCard>
</template>