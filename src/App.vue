<template>
  <div id="app">
    <h1>{{ message }}</h1>
    <p>Count is: {{ counter.count }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello World!',
      counter: {
        count: 0
      }
    }
  }
}
</script>