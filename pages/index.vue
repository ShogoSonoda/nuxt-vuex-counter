<template>
  <section class="container">
    <div>
      <Counter></Counter>
      <hr>
      <Counter></Counter>
      <hr>
      <Counter></Counter>
      <hr>
    </div>
  </section>
</template>

<script>
import Counter from '~/compornents/Counter.vue'

export default {
  components: {
    Counter
  }
}
</script>
