<template>
    <div id="app">
        <AppHeader />
        <router-view></router-view>
    </div>
</template>

<script>
import AppHeader from './components/Header';

export default {
    name: 'App',
    components: {
        AppHeader,
    },
};
</script>

<style></style>
