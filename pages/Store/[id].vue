<template>
    <div>
         <h3>store  for {{ id }}</h3>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui nobis
             atque iusto repellat obcaecati tempora pariatur explicabo sapiente accusamus fuga.</p>
    </div>
</template>

<script setup>
const {id}= useRoute().params
</script>

<style  scoped>

</style>