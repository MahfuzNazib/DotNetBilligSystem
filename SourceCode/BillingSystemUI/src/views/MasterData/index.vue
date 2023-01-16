<template>
  <div class="app-container">
    <aside>
      MASTER DATA LIST
    </aside>

    <div>
      <div class="row">
        <div class="col-md-2">
          <HorizontalCard buttonText="Shop Category" @click="$router.push('/dashboard')"/>
        </div>

        <div class="col-md-2">
          <HorizontalCard buttonText="Shop List" />
        </div>

        <div class="col-md-2">
          <HorizontalCard buttonText="Test Button" />
        </div>

        <div class="col-md-2">
          <HorizontalCard buttonText="Test Button" />
        </div>

        <div class="col-md-2">
          <HorizontalCard buttonText="Test Button" />
        </div>

        <div class="col-md-2">
          <HorizontalCard buttonText="Test Button" />
        </div>
      </div>
    </div>
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
