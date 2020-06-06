<template>
  <div>
    login
    <el-button @click="login">登陆</el-button>
  </div>
</template>

<script>
import { login } from '@/api/user'
export default {
  methods: {
    login() {
      login().then((res) => {
        console.log('res')
      })
    }
  }
}
</script>

<style lang="sass" scoped>

</style>
