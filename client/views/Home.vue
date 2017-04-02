<template>
    <div>
        <header>
            <div class="container">
                <h1>Steam Key Tumbler</h1>
            </div>
        </header>

        <div class="container">
            <key-input>Benson</key-input>

            <hr/>

            <key-output></key-output>

            <counter unit="eggs"></counter>

            <p>Share Link: <code>/share?id=123</code></p>
        </div>
    </div>
</template>

<script>
import counter from 'components/Counter'
import keyInput from 'components/KeyInput'
import keyOutput from 'components/KeyOutput'

export default {
  components: {
      counter,
      keyInput,
      keyOutput
  }
}
</script>
