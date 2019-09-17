<template lang="pug">
    .total-m
        TotalBlockS
        TotalLarge
</template>

<script>
import TotalBlockS from '@/components/TotalBlockS.vue'
import TotalLarge from '@/components/TotalLarge.vue'

export default {
  name: 'home',
  components: {
    TotalBlockS,
    TotalLarge
  }
}
</script>