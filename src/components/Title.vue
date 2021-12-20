<template>
  <h1>{{ msg }}</h1>
  <p class="mb-5">
    Vuex, Router, SCSS, Vuetify themes,
    Directives, Middlewares, mixins and plugins. <br />
    All written in typescript SFC
  </p>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  props: {
    msg: {
      type: String
    }
  },
  setup(props) {
    return { msg: props.msg }
  }
})
</script>
