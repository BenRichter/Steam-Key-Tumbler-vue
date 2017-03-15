<template>
    <div class="page">
        <h1>Steam Key Tumbler</h1>

        <KeyInput></KeyInput>

        <counter></counter>

        <p>Share Link: <code>/share?id=123</code></p>
    </div>
</template>

<script>
import Counter from 'components/Counter'
import KeyInput from 'components/KeyInput'

export default {
  components: {
      Counter,
      KeyInput
  }
}
</script>
