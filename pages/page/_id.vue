<template>
  <main>
    {{ $route.params.id }}
  </main>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'MyPage',
});
</script>

<style scoped>
main {
  background: red;
}
</style>
