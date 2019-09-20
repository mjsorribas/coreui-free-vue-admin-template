<template>
  <div class="app">
    <DefaultHeader/>
    <div class="app-body">
      <DefaultLeftSidebar />
      <main class="main">
        <Breadcrumb :list="list"/>
        <div class="container-fluid">
          <router-view></router-view>
        </div>
      </main>
      <AppAside fixed>
        <!--aside-->
        <DefaultAside/>
      </AppAside>
    </div>
    <DefaultFooter
      title="CoreUI"
      title_url="https://coreui.io"
      copyrigth_text="© 2018 creativeLabs."
      power_by_text="CoreUI for Vue"
      power_by_url="https://coreui.io"
    />
  </div>
</template>
<script>
import { Aside as AppAside, Breadcrumb } from '@coreui/vue'
import DefaultAside from './DefaultAside'
import DefaultHeaderDropdownAccnt from './DefaultHeaderDropdownAccnt'
import DefaultHeader from './DefaultHeader'
import DefaultFooter from './DefaultFooter'
import DefaultLeftSidebar from './DefaultLeftSidebar'

export default {
  name: 'DefaultContainer',
  components: {
    AppSidebar,
    AppAside,
    Breadcrumb,
    DefaultAside,
    DefaultHeaderDropdownAccnt,
    DefaultFooter,
    DefaultHeader,
    DefaultLeftSidebar,
    SidebarForm,
    SidebarFooter,
    SidebarHeader,
    SidebarNav,
    SidebarMinimizer
  },
  data () {
    return {
      nav: nav.items
    }
  },
  computed: {
    name () {
      return this.$route.name
    },
    list () {
      return this.$route.matched.filter((route) => route.name || route.meta.label )
    }
  }
}
</script>
