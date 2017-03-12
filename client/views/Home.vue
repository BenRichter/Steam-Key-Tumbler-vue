<template>
    <div class="page">
        <h1>Steam Key Tumbler</h1>

        <p>Put in Steam Keys and share the Key with your Community</p>

        <textarea name="steamkeys" id="key-input" cols="60" rows="8"></textarea>

        <counter></counter>

        <p>Share Link: <code>/share?id=123</code></p>
    </div>
</template>

<script>
import Counter from 'components/Counter'

export default {
  components: {
    Counter
  }
}
</script>
