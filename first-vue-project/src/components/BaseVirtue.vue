<template>
    <div class="base-virtue">
        <slot/>
        <slot name ="image"/>
        <h3>
            <slot name ="title" />
        </h3>
        <p>
            <slot name="description"/>
        </p>
        <slot/>
    </div>
</template>

<script>
    export default {
        name: "BaseVirtue"
    }
</script>

<style scoped>
.base-virtue{

}
</style>