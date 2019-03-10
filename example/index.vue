<script>
import VueShinyButton from '../src/vue-shiny-button.vue'

export default {
  name: 'Example',
  components: {
    VueShinyButton,
  },
  methods: {
    handleClick () {
      // eslint-disable-next-line
      console.log('CLICK!')
    },
  },
}
</script>

<template>
  <div id="example">
    <VueShinyButton @click="handleClick" type="button" />
  </div>
</template>

<style scoped>
#example {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 17px;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  display: -webkit-flex;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
