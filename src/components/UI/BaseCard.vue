<template>
    <div>
        <slot />
    </div>
</template>


<script>
export default{
    name: 'BaseCard',
}
</script>

<style scoped>
div {
    border-radius: 12px;
    padding: 1rem;
    margin: 2rem auto;
    max-width: 40rem;
}
</style>