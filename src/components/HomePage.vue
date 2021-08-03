<template>
  <div class="home-page">
    {{ forumData }}
  </div>
</template>

<script>
import forumData from '@/data.json';

export default {
  name: 'HomePage',
  data() {
    return {
      forumData
    }
  },
};
</script>

<style scoped>
</style>
