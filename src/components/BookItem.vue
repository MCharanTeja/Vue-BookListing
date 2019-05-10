<template>
    <div>
            <li>{{roll.title}}:{{roll.author}}</li>   
    </div>
</template>
<script>
    export default {
        name: 'BookItem',
        props: ['roll']
    }
</script>
<style>
    li {
        display: block;
        margin: 0 10px;
    }
</style>