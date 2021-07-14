<template>
    <div>
        <div class="overlap-group">
            <img class="rectangle-3" src="../assets/img/rectangle-3@2x.png" />
            <img class="cover" src="../assets/img/image-1-1@2x.png" />
            <div class="navigation-bar">
                <img
                    class="voterookie-logo"
                    src="../assets/img/voterookie-logo-weiss-pinke-karte-weisse-umrandung-2@2x.png"
                />
            </div>
            <nuxt-link to="/mobile">
                mobile
            </nuxt-link>
        </div>
        <div class="flex-row">
            <div class="rectangle-4"></div>
            <h1 class="text-2">
                Be part of the change
            </h1>
        </div>
        <p class="text-1">Your tool for civic participation</p>

        <!-- <Button :variant="1">LOGIN</Button>
        <Button :variant="2">START AS A CITIZEN</Button>

         -->
    </div>
</template>

<script>
/* }-<((('> */
import Button from '../components/Button.vue'
export default {
    components: {
        Button,
    },
}
</script>

<style>
.overlap-group {
    height: 420px;
    margin-left: 0.5px;
}
.cover {
    height: 309px;
    left: 0;
    position: absolute;
    top: 111px;
    width: 375px;
}
.rectangle-3 {
    height: 233px;
    left: 0;
    position: absolute;
    top: 0;
    width: 375px;
}

.navigation-bar {
    align-items: center;
    display: flex;
    flex-direction: column;
    left: 0;
    min-height: 152px;
    position: absolute;
    top: 0;
    width: 375px;
}

.voterookie-logo {
    padding-top: 2rem;
    height: 61px;
    object-fit: cover;
    width: 121px;
}
.flex-row {
    align-items: center;
    display: flex;
    height: 64px;
    margin-right: 8px;
    min-width: 299px;
}

.rectangle-4 {
    background-color: var(--rookie-pink);
    height: 62px;
    width: 5px;
}
.text-2 {
    padding-bottom: 2rem;
    letter-spacing: 0.6px;
    line-height: 31px;
    margin-left: 8px;
    min-height: 64px;
    min-width: 286px;
    width: 286px;
    /* Heading */

    font-family: Rubik;
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 32px;
    /* or 107% */

    letter-spacing: 0.02em;

    /* Rookie Blue */

    color: #2047ff;
}

.text-1 {
    margin-right: 31px;
    margin-top: 10px;
    min-height: 19px;
    min-width: 276px;
    width: 276px;
    /* Body */

    font-family: Rubik;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 19px;
    /* identical to box height */

    /* Text */

    color: #343846;
}

.onboarding .text-4 {
    position: absolute;
    height: 11px;
    left: 112px;
    top: 719px;

    /* Caption */

    font-family: Rubik;
    font-style: normal;
    font-weight: 300;
    font-size: 12px;
    line-height: 11px;
    /* identical to box height, or 92% */

    text-align: center;
    letter-spacing: 0.05em;

    /* Rookie Blue */

    color: #2047ff;
}

.onboarding .text-3 {
    letter-spacing: 0.6px;
    line-height: 11px;
    margin-left: 2px;
    margin-top: 25px;
    min-height: 11px;
    min-width: 172px;
    text-align: center;
    white-space: nowrap;
}

.text-5 {
    position: absolute;
    height: 11px;
    left: 102.5px;
    top: 755px;

    /* Caption */

    font-family: Rubik;
    font-style: normal;
    font-weight: 300;
    font-size: 12px;
    line-height: 11px;
    /* identical to box height, or 92% */

    text-align: center;
    letter-spacing: 0.05em;

    /* Rookie Pink */

    color: #da3675;
}
</style>
