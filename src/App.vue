<template>
  <div id="app">
    <!-- <v-login></v-login> -->
    <!-- <v-signUp></v-signUp> -->
    <!-- <v-userInfo></v-userInfo> -->
    <!-- <v-sellMod></v-sellMod> -->
    <v-sellRecord></v-sellRecord>
  </div>
</template>

<script>
import login from './components/login'
import userInfo from './components/userInfo'
import sellMod from './components/sellMod'
import signUp from './components/signUp'
import sellRecord from './components/sellRecord'
import wx from 'weixin-js-sdk'
import axios from 'axios'
export default {
  components: {
    'v-login': login,
    'v-userInfo': userInfo,
    'v-sellMod': sellMod,
    'v-signUp':signUp,
    'v-sellRecord':sellRecord
  }
}
</script>

<style>
#app {
  width: 100%;
  height: 100vh;
}
</style>
