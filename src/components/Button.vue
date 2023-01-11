<template>
    <button :style="{background: color}" @click="onClick()" class="btn">{{ text }}</button>
</template>


<script>
    export default{ 
        name: 'Button',
        props: {
            text: String,
            color: {
                type: String,
                default: 'black'
            }
        },
        methods: {
            onClick() {
                this.$emit('btn-click')
            }
        }

    }

</script>

<style>


</style>