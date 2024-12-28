<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        

        <q-toolbar-title>

        <q-img src="logo.png"
        style="width: 120px;"></q-img>
          
        </q-toolbar-title>

        <div class="gt-sm">
          <q-btn outline  flat color="white" class="q-mr-sm" label="COURSES" />
          <q-btn outline rounded color="white" class="q-mr-sm" label="SIGN UP" />
          <q-btn outline rounded color="white" label="SIGN IN" />
          </div>

          <div class="lt-md">
            <q-btn
          flat
          dense
          round
          icon="menu"
          aria-label="Menu"
          @click="toggleLeftDrawer"
        />
          </div>
      </q-toolbar>
    </q-header>

    <q-drawer
      v-model="leftDrawerOpen"
      bordered
    >
      <q-list>
        <q-item-label
          header
        >
          Essential Links
        </q-item-label>

        <EssentialLink
          v-for="link in linksList"
          :key="link.title"
          v-bind="link"
        />
      </q-list>
    </q-drawer>


    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer elevated>
        <q-toolbar>
        <q-space />
        &copy; Innorium Business Solutions 2025.
        <q-space />
        </q-toolbar>
      </q-footer>

  </q-layout>
</template>

<script setup>
import { ref } from 'vue'
import EssentialLink from 'components/EssentialLink.vue'

const linksList = [
  {
    title: 'SIGN IN',
    caption: 'sign in here..',
    // icon: 'school',
    // link: 'https://quasar.dev'
  },
  {
    title: 'SIGN UP',
    caption: 'sing up here',
    // icon: 'code',
    // link: 'https://github.com/quasarframework'
  },
  {
    title: 'COURSES',
    caption: 'course details',
    // icon: 'chat',
    // link: 'https://chat.quasar.dev'
  },
  
]

const leftDrawerOpen = ref(false)

function toggleLeftDrawer () {
  leftDrawerOpen.value = !leftDrawerOpen.value
}
</script>
