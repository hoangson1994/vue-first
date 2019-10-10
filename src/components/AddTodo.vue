<template>
    <form @submit.prevent="addTodo">
        <input type="text" name="add-todo" v-model="title">
        <input type="submit" class="btn" value="Add Todo"/>
    </form>
</template>

<script>
    export default {
        name: "AddTodo",
        data() {
            return {
                title: ''
            }
        },
        methods: {
            addTodo() {
                const newTodo = {
                    title: this.title,
                    completed: false
                };
                this.$emit('add-todo', newTodo);
                this.title = '';
            }
        }
    }
</script>

<style scoped>
    form {
        display: flex;
    }

    input[type="text"] {
        flex: 10;
        padding: 5px;
    }

    input[type="submit"] {
        flex: 2;
    }
</style>
