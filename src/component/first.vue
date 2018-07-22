<template>
    <div id="first">
        <em>{{ msg }}</em>
    </div>
</template>

<script>
    export default {
        name: 'first',
        data () {
            return {
                msg: 'hello, everything will be good!'
            }
        }
    }
</script>

<style>
    em {
        color: orange;
    }
</style>