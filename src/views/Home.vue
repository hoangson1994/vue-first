<template>
    <div id="app">
        <HomePage/>
    </div>
</template>

<script>

    import axios from "axios";
    import HomePage from "../components/HomePage";

    export default {
        name: 'home',
        components: {
            HomePage
        },
        data() {
            return {
                todos: []
            }
        },
        methods: {
            list() {
                axios.get('https://jsonplaceholder.typicode.com/todos?_limit=5')
                    .then(res => this.todos = res.data)
                    .catch(err => console.log(err))
            },
            create(todo) {
                axios.post('https://jsonplaceholder.typicode.com/todos', todo)
                    .then(res => this.todos = [...this.todos, res.data])
                    .catch(err => console.log(err))
            },
            deleteTodo(id) {
                axios.delete(`https://jsonplaceholder.typicode.com/todos/${id}`)
                    .then(res => this.todos = this.todos.filter(todo => todo.id !== id))
                    .catch(err => console.log(err))
            }
        },
        created() {
            this.list();
        }
    }
</script>
