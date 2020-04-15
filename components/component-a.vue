<template>
  <p > {{text}} </p>
</template>

<script>
export default {
  name: 'textBar',
  props: {
    text: String
  },
  data () {
    return {
      dom: null
    }
  }
}
</script>