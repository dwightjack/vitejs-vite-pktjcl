<script setup lang="ts">
import VueTypes from 'vue-types';

const props = defineProps({
  params: VueTypes.object.def({}),
});
</script>

<template>
  <p>{{ params }}</p>
</template>
