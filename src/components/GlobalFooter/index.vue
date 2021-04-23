<template>
  <global-footer class="footer custom-render">
    <template v-slot:links>
      <a href="https://github.com/Yanoona/Project_System_WEB" target="_blank">2021 颜洁平所开发</a>
    </template>
  </global-footer>
</template>

<script>
import { GlobalFooter } from '@ant-design-vue/pro-layout'

export default {
  name: 'ProGlobalFooter',
  components: {
    GlobalFooter
  }
}
</script>
