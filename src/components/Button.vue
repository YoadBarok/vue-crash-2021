<template>
    <button :style="{background: color}" class="btn">{{ text }}</button>
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
        }

    }

</script>

<style>


</style>