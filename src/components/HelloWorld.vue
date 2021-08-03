<template>
  <div class="hello">
    {{ forumData }}
  </div>
</template>

<script>
import forumData from '@/data.json';

export default {
  name: 'HelloWorld',
  data() {
    return {
      forumData
    }
  },
};
</script>

<style scoped>
</style>
