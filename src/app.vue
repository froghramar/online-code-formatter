<template>
    <v-app>
        <v-navigation-drawer app>
            <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link>
        </v-navigation-drawer>
        <v-content>
            <router-view/>
        </v-content>
    </v-app>
</template>

<style lang="scss" src="./app.scss"></style>

<script lang="ts">

    export default {
        name: 'App',
        components: { },
        data: () => {
            return { };
        },
    };
</script>
