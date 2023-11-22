<template>
    <div>

        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Blanditiis ea delectus quaerat voluptas? Consequatur quas, qui voluptate, quisquam recusandae dolor facilis magni laboriosam omnis, perferendis nisi? Quia iusto magnam placeat?</p>

    </div>
</template>

<script setup>
   const{ id } = useRoute().params
   definePageMeta({
    layout: 'products'
})
</script>

<style scoped>

</style>