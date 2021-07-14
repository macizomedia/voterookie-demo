<template>
    <div class="cardObject">
        <div class="title">
            <p>{{ title }}</p>
        </div>
        <div class="cardObject-tag">
            <p>{{ tag }}</p>
        </div>
        <div class="cardObject-content">
            <p>{{ content }}</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Card',
    props: ['title', 'tag', 'content'],
}
</script>

<style>
.cardObject {
    display: grid;
    grid: auto-flow / 1fr 1fr 1fr;
}
.cardObject title {
    background-color: gray;
}
</style>
