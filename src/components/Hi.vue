<template>
    <div id="hi">
        hi
        <helloWorld></helloWorld>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from './HelloWorld.vue';

@Component({
    components: {
        HelloWorld
    }
})
export default class Hi extends Vue {}
</script>

<style lang="scss">
</style>
