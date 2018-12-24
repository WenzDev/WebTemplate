<template>
  <div id="app">
    <HubMeta></HubMeta>
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
import HubMeta from '@/components/HubMeta.vue'

export default {
  name: 'App',
  components: {
    NavbarComponent,
    PageHeadingComponent,
    HubMeta
  }
}
</script>
