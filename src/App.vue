<template>
  <topBar appName="CRUD - Vue.Js"/>
  <itemsForm/>
  <foot/>
</template>

<script>

import topBar from './components/topBar.vue'
import itemsForm from './components/itemsForm.vue'
import foot from './components/foot.vue'

export default {
  name: 'App',
  components: {
    topBar,
    itemsForm,
    foot,
  },
}
</script>
