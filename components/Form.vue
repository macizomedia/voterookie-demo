<template>
    <i-form>
        <i-form-group>
            <i-form-label>Email</i-form-label>
            <i-input class="rookie" v-model="input" placeholder="your email..." />
        </i-form-group>
        <i-form-group>
            <i-form-label>Password</i-form-label>
            <i-input class="rookie" type="password" v-model="input" />
        </i-form-group>

        <i-form-group>
            <i-button type="submit">Submit</i-button>
        </i-form-group>
    </i-form>
</template>

<script>
export default {

}
</script>

<style >


.rookie {
    background: #ffffff;
    /* Primary Brand */

    border: 1px solid #2047ff;
    box-sizing: border-box;
    border-radius: 5px;
}

</style>
