<template>
    <div class="key-input">
        <p>Put in Steam Keys and share the Key with your Community: {{message}}</p>
        <textarea name="steamkeys" cols="60" rows="8" v-model="message"></textarea>

        <ul>
            <li v-for="item in array">{{item}}</li>
        </ul>

        <input type="text"/>
        <button>Add name</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                array: ['first', 'second', 'third'],
                message: 'd\u00F6rp'
            }
        },
        mounted() {
            console.log("ready");
        }
    }
</script>

<style scoped>
    textarea {
        width: 100%;
    }
</style>
