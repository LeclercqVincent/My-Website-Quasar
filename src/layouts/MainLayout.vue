<template>
  <q-layout view="hHh lpR fFf">
    <q-header
      reveal
      elevated
      class="text-white"
      height-hint="98"
      style="background-color: rgba(25, 28, 31, 0.8)"
    >
      <q-tabs align="center">
        <q-route-tab to="/page1" label="Home" />
        <q-route-tab to="/page2" label="About Me" />
        <q-route-tab to="/page3" label="Page Three" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer reveal elevated class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg" />
          </q-avatar>
          <div>Title</div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'MainLayout',
  setup() {
    return {};
  },
});
</script>
