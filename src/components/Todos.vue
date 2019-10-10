<template>
    <div>
        <div v-bind:key="todo.id" v-for="todo in todos">
            <TodoItem v-bind:todo="todo" v-on:del-todo="deleteTodo"/>
        </div>
    </div>
</template>

<script>
    import TodoItem from "./TodoItem";
    export default {
        name: "Todos",
        components: {TodoItem},
        props: ["todos"],
        methods: {
            deleteTodo(id) {
                this.$emit('delete-todo', id);
            }
        }
    }
</script>

<style scoped>

</style>
