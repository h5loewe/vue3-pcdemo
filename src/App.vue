<template>
  <div class="page">
    <router-view />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import 'bootstrap/dist/css/bootstrap.min.css';

export default defineComponent({
  name: 'app'
});
</script>

<style lang="scss"></style>
