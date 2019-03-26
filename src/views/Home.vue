<template>
  <div class="home">
    <h1>{{ $store.state.constant.VIDEO1 }}</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home'
}
</script>
