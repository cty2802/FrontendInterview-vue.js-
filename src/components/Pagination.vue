<script>
export default {
  methods: {

  }
}
</script>

<template>
  <section class="pagination">
    <button
      class="pagination-button pagination-prev"
      @click="handleChangePrev()"
    >
    &lt; Попередня
    </button>

    <button
      class="pagination-button pagination-next "
      @click="handleChangeNext()" 
    >
      Наступна >
    </button>
</section>
</template>

<style></style>