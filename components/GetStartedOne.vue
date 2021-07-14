<template>
    <div>
        <div class="get-started-1 screen">
            <div class="overlap-group">
                <img
                    class="voterookie-logo-sse"
                    src="../assets/img/voterookie-logo-weiss-pinke-karte-weisse-umrandung-2@2x.png"
                />
            </div>
            <div class="progress-bar">
                <strong>PROGRESS BAR</strong>
            </div>
            <h1 class="text-1">
                <span class="span">Hello! Great that you are joining </span
                ><span class="span">Vote Rookie!</span>
            </h1>
            <p class="text-2">
                To personalise Vote Rookie for you, I would like to ask you a
                few questions.<br /><br />Please fill in the details below
            </p>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Rubik:400,300,700|Roboto:400|Manrope:500');
.get-started-1 {
    align-items: center;
    background-color: var(--background);
    display: flex;
    flex-direction: column;
    height: 812px;
    width: 375px;
}
.get-started-1 .overlap-group {
    height: 102px;
    position: relative;
    width: 375px;
}
.get-started-1 .progress-bar {
    align-items: flex-end;
    border-radius: 100px;
    display: flex;
    height: 41px;
    margin-top: 22px;
    min-width: 350px;
    padding: 0 1px;
}

.get-started-1 .voterookie-logo-sse {
    height: 41px;
    margin-right: 5px;
    margin-top: 7px;
    object-fit: cover;
    width: 121px;
}

.get-started-1 .text-1 {
    letter-spacing: 0.6px;
    line-height: 32px;
    margin-left: 2px;
    margin-top: 49px;
    min-height: 96px;
    min-width: 306px;
    text-align: center;
    width: 306px;
}

.get-started-1 .span {
    letter-spacing: 0.18px;
}
.get-started-1 .text-2 {
    color: var(--text);
    margin-left: 2px;
    margin-top: 14px;
    min-height: 76px;
    min-width: 318px;
    text-align: center;
    width: 318px;
}
</style>
