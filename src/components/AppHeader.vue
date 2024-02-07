<script>
import SearchFilms from './SearchFilms.vue';
export default {
    name: 'AppHeader',
    components: { SearchFilms },
}
</script>

<template>
    <header class="container py-5 d-flex justify-content-between">
        <h1>Logo</h1>
        <SearchFilms />
    </header>
</template>

<style lang="scss" scoped ></style>