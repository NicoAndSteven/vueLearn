<template>

    <div class="sss">
        <h1>hello</h1>
        <h3>{{ student }}</h3>
    </div>
    </template>
    
    <script>
    export default{
        data(){
            return{
                student:"Steven"
            }
        }
    }
    
    </script>
    
    <style>
        .sss{
        background-color: skyblue;
        box-shadow: 0 0 10px;
        border-radius: 10px;
        padding: 20px;
        }
    </style>