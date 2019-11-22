<template>
    <div class="todo-item">
         <p>{{todo.title}}</p>
    </div>
</template>
<script>
export default {
    name:'TodoItem',
    props:["todo"]
}
</script>
<style scoped>
.todo-item{
    background: #f4f4f4;
    padding: 10px;
    border-bottom: 1px #cccccc dotted
}
.is-Complete{
    text-decoration: line-through
}
.del{
background: #ff0000;
color:#f4f4f4;
border:none;
padding: 5px 9px;
border-radius: 50%;
cursor: pointer;
float: left;
}
</style>