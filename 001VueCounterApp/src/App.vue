<script setup>
import {ref} from "vue"
const count = ref(0);
</script>

<template>
<h3>Count is now ...</h3><br/>
<h1> {{ count }} </h1><br/>
<button @click="count--">-</button>
<button @click="count++">+</button>
</template>

<style scoped>

</style>
