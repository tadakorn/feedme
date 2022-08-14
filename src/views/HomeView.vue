<template>
  <main class="mt-4">
    <div class="row justify-content-center">
      <div class="col col-6">
        <SearchForm />
      </div>
    </div>

    <div v-for="n in 10" :key="n" class="row justify-content-center mt-4">
      <div class="col col-6">
        <StoreCard />
      </div>
    </div>
  </main>
</template>

<script>
import StoreCard from '../components/home/StoreCard.vue';
import SearchForm from '@/components/home/SearchForm.vue'

export default {
  components: {
    SearchForm,
    StoreCard
  }
}
</script>