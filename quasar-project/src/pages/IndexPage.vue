<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
    <InputPage/>
    <FunctionPage/>
  </div>
</template>

<script>
import InputPage from "src/pages/InputPage.vue"
import FunctionPage from "src/pages/FunctionPage.vue"


export default {
  name: 'HtmlComponent',
  components: {InputPage, FunctionPage},
  data() {
    return {
      title: 'Chaiyut Suntharote'
    };
  }
}
</script>