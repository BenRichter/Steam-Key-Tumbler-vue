<template>
      <div class="key-input">
        <p>Put in Steam Keys and share the Key with your Community {{message}}</p>
         <textarea name="steamkeys" cols="60" rows="8" v-model="message"></textarea>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Add keys here'
            }
        }
    }
</script>

<style scoped>
    textarea {
        width: 100%;
    }
</style>
