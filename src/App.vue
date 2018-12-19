<template>
  <div id="app">
    <navbar-component></navbar-component>
    <div class="container">
      <page-heading-component></page-heading-component>
    </div>
    <router-view/>
  </div>
</template>

<script>
import NavbarComponent from '@/components/NavbarComponent.vue'
import PageHeadingComponent from '@/components/PageHeadingComponent.vue'

export default {
  name: 'App',
  components: {
    NavbarComponent,
    PageHeadingComponent
  }
}
</script>
