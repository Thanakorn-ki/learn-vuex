<template>
  <div>
    <Display></Display>
    <Increment></Increment>
  </div>
</template>

<script>
import Display from './components/Display.vue'
import Increment from './components/Increment.vue'
import store from './vuex/store' // import the store we just created

export default {
  components: {
    Display,
    Increment
  },
  store // make this and all child components aware of the new store
}
</script>
