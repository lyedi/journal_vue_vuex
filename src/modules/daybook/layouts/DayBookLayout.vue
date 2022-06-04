
<template>

    <navbar/>
  <div class="d-flex">
      <div class="col-4">
          <EntryList/>
      </div>
      <div class="col">
          <router-view/>

      </div>
  </div>
</template>

<script>
import { defineAsyncComponent } from 'vue'
// import navbar  from '../components/navbar.com'
export default {
    components: {
        navbar: defineAsyncComponent(() => import('../components/navbar.vue')),
        EntryList: defineAsyncComponent(() => import('../components/EntryList.vue')),
    },
}
</script>