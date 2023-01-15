<template>
  <div class="app-container">
    <aside>
      Master Data List
    </aside>

    <ul>
      <li>Shop Type</li>
      <li>Shops</li>
      <HorizontalCard buttonText="Test Button" buttonURL="https://eslint.vuejs.org/user-guide/"/>


    </ul>
  </div>
</template>

<script>
import HorizontalCard from '@/components/Card/HorizontalCard.vue';
export default {
  name: 'MasterData',
  components: {
    HorizontalCard,
  },
}
</script>
