<template>
    <div class="ClearAllcontainer">
        <span class="clearAllBtn" @click="clerTodo">Clear All</span>
    </div>
</template>

<script>
export default {
    methods:{
        clearTodo(){
            localStorage.clear()
        }
    }
    
}
</script>

<style>
.ClearAllcontainer{
    width: 8.5rem;
    height: 50px;
    line-height: 50px;
    background-color: white;
    border-radius: 5px;
    margin: 0 auto;
}
.clearAllBtn{
    color: #e20303;
    display: block;
}
</style>