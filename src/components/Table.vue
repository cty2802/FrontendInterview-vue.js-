<script>
  import items from '../../db.json';

  export default {
    data() {
      return {
        items,
      }
    }
  }
</script>

<template>
  <div 
    class="article" 
    v-for="items of items.articles"
    v-bind:key="items.id"
  >
    <div class="article__picture">
      <img class="article__picture-img" alt=""/>
    </div>    

    <div class="article__info">
      <p class="article__info-title"> {{ items.title }}</p>
      <p class="article__info-fields">{{ items.fields }}</p>
    </div>
   </div>
</template>

<style></style>