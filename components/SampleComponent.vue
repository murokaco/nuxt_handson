<template lang="html">
  <div class="sample">
    <div>
      <nuxt-link to="/about">about</nuxt-link>
    </div>
  </div>
</template>
​
<script>
export default {
  methods: {
    plus() {
      this.num++
    }
  },
  mounted() {
    console.log('mounted')
  },
  props: {
    title: {
      type: String,
      default: 'Defalut Title'
    }
  },
  data() {
    return {
      name: 'takanorip'
    }
  },
}
</script>
​
<style lang="scss" scoped>
.hide {
  display: none;
  &.seven {
    display: block;
  }
}
</style>
