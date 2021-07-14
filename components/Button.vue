<template>
    <div v-on:click="greet" :class="`figma-button-${variant}`">
        <div :class="`action-${variant}`">
            {{ title }}
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
        },
        title: {
            type: String,
        },
    },
    methods: {
        greet: function(event) {
            // `this` inside methods points to the Vue instance
            alert('Hello ' + this.name + '!')
            // `event` is the native DOM event
            if (event) {
                alert(event.target.tagName)
            }
        },
    },
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

    /* White */
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
.action-1 {
    position: absolute;
    height: 19px;
    left: 132.5px;
    right: 132.5px;
    top: 18.5px;

    /* Button Text */

    font-family: Rubik;
    font-style: normal;
    font-weight: bold;
    font-size: 16px;
    line-height: 19px;
    /* identical to box height */

    display: flex;
    align-items: center;
    text-align: center;
    text-transform: uppercase;

    /* White */

    color: #ffffff;
}

.action-2 {
    position: absolute;
    height: 19px;
    left: 77.5px;
    right: 78.5px;
    top: 18.5px;

    /* Button Text */

    font-family: Rubik;
    font-style: normal;
    font-weight: bold;
    font-size: 14px;
    line-height: 19px;
    /* identical to box height */

    text-align: center;
    text-transform: uppercase;

    /* Text */

    color: #343846;
}
</style>
