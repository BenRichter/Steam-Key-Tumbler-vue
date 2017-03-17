<template>
    <div class="key-input">
        <p>Put in Steam Keys and share the Key with your Community: {{message}}</p>
        <textarea name="steamkeys" cols="60" rows="8" v-model="message"></textarea>

        <ul>
            <li v-for="name in names">{{name}}</li>
        </ul>

        <input type="text" v-model="newName"/>
        <button @click="addName">Add name</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                names: ['first', 'second', 'third'],
                message: 'd\u00F6rp',
                newName: ''
            }
        },
        methods: {
            addName() {
                this.names.push(this.newName);
                this.newName = '';
            }
        },
        mounted() {
            console.log("### ready");
        }
    }
</script>

<style scoped>
    textarea {
        width: 100%;
    }
</style>
