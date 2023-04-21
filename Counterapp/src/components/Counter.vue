<template>
    <div>
        <h1  class="count">Couter: {{ counter }}</h1>
        <button @click="counter = counter + 1">INC</button>
        <button @click="counter = counter - 1">DEC</button>
    </div>
</template>
<script>
export default {
    name: "Counter",
    data() {
        return {
            counter: 0
        }
    }
}
</script>
<style>
.count{
   color: orange;
}
</style>