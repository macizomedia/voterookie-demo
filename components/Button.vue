<template>
    <div :class="`figma-button-${variant}`">
        <div class="text-3">
            <slot> </slot>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        variant: {
            type: Number,
            default: 'default',
        },
        onClick: {
            type: Function,
            required: true,
        },
    },
    data: () => ({}),
}
</script>

<style>
.figma-button-1 {
    /* Buttons */

    position: absolute;
    width: 314px;
    height: 56px;
    left: 24.83px;
    top: 558px;

    /* Gradient */

    background: linear-gradient(244.58deg, #da3675 0%, #2047ff 100%);
    /* Shadow */

    box-shadow: 0px 10px 20px rgba(40, 38, 109, 0.18);
    border-radius: 5px;
}
.figma-button-2 {
    /* Buttons */

    position: absolute;
    width: 314px;
    height: 56px;
    left: 24.83px;
    top: 628px;

    /* Rookie Pink */

    border: 1px solid #da3675;
    box-sizing: border-box;
    border-radius: 5px;
}
</style>
