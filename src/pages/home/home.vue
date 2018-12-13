<template>
    <div class="home-container">
        Home
        <format-editor/>
    </div>
</template>
<style lang="scss" src="./home.scss"></style>
<script lang="ts">
    import { Component, Vue } from 'vue-property-decorator';
    import FormatEditor from '@/components/format-editor/format-editor.vue';

    @Component({
        components: {
            FormatEditor,
        },
    })
    export default class Home extends Vue {}
</script>
