<template>
  <div class="home">
    {{ forumData }}
  </div>
</template>

<script>
import forumData from '@/data.json';

export default {
  name: 'Home',
  data() {
    return {
      forumData
    }
  },
};
</script>

<style scoped>
</style>
