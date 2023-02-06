<script setup>
import {ref} from "vue"
const count = ref(0);
const addCount = ()=>{
    count.value = count.value+1
}
const subtractCount = ()=>{
    count.value = count.value-1
}
</script>

<template>
<h3>Count is now ...</h3><br/>
<h1> {{ count }} </h1><br/>
<button @click="subtractCount">-</button>
<button @click="addCount">+</button>
</template>

<style scoped>

</style>
