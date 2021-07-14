<template>
    <div class="container-center-horizontal">
        <Header />
    </div>
</template>

<script>
import Header from '../components/Header.vue'
export default {
    components: { Header },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Rubik:400,300,700|Roboto:400|Manrope:500');
.component-wrapper * {
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
    pointer-events: none;
}

.component-wrapper a *,
.component-wrapper input,
.component-wrapper video,
.component-wrapper iframe {
    pointer-events: auto;
}

.component-wrapper.not-ready,
.component-wrapper.not-ready * {
    visibility: hidden !important;
}

.screen a {
    display: contents;
    text-decoration: none;
}

.container-center-horizontal {
    display: flex;
    flex-direction: row;
    justify-content: center;
    pointer-events: none;
    width: 100%;
}

.container-center-horizontal > * {
    flex-shrink: 0;
    pointer-events: auto;
}

.valign-text-middle {
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.valign-text-bottom {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
}

.listeners-active,
.listeners-active * {
    pointer-events: auto;
}

.hidden,
.hidden * {
    pointer-events: none;
    visibility: hidden;
}
</style>
