<template>
    <div>
            <li>{{book.title}}:{{book.author}}</li>   
    </div>
</template>
<script>
    export default {
        name: 'BookItem',
        prop: ['book']
    }
</script>
<style>
    li {
        display: block;
        margin: 0 10px;
    }
</style>
