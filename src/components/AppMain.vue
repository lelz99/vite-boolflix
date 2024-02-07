<script>
import AppSection from './AppSection.vue';

export default {
    name: 'AppMain',
    components: { AppSection },
}
</script>

<template>
    <main class="container">
        <AppSection id="films" />
        <AppSection id="series" />
    </main>
</template>

<style lang="scss" scoped ></style>