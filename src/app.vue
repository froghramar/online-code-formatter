<template>
    <div class="grid-container" id="app">
        <div class="ocf-header">Online Code Formatter</div>
        <div class="ocf-left-nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
        <div class="ocf-main-content">
            <router-view/>
        </div>
        <div class="ocf-footer">Footer</div>
    </div>
</template>

<style lang="scss" src="./app.scss"></style>
