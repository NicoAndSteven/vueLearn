<template>
<h1>this is it!</h1>
<div :class="on">{{ student }}</div>
</template>

<script>
export default{
    data(){
        student:"Steven"
    }
}

</script>

<style>
    .on{
    background-color: #ddd;
    box-shadow: 0 0 10px;
    border-radius: 10px;
    padding: 20px;
    }
</style>