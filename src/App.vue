<script>
import Table from './components/Table.vue';
import Pagination from './components/Pagination.vue';

export default {
  components: {
    Table,
    Pagination,
  }
}
</script>
<template> 
  <main class="app">
    <header>
      <img src="./assets/styles/img/logo.png" alt="Autoline" class="logotype" />
    </header>
    <section class="articles">

      <Table />
    </section>

    <Pagination />

  </main>
</template>

<style></style>
