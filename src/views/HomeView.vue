<template>
  <div class="main-content">
    <div>
      <BookList></BookList>
    </div>
  </div>
</template>

<script>
import BookList from '@/components/BookList.vue'

export default {
  components: {
    BookList
  }
}

</script>

<style scoped>
.main-content {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
</style>
