<template>
  <h1>{{ msg }}</h1>
  <p class="mb-5">
    With fully functional configrations for Vuex, Router, SCSS, Vuetify themes,
    Direcsstives, Middlewares, mixins and plugins. <br />
    All written in typescript Modular form with single file component and script
    setup mode for vue.
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
