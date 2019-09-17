<template lang="pug">
  .app
    .sidebar    
      TotalSmall
      TotalLarge
      ServerSide
      BigButton
      TotalBlockS
      //wow

</template>

<script>
import TotalSmall from '@/components/TotalSmall.vue'
import TotalLarge from '@/components/TotalLarge.vue'
import ServerSide from '@/components/ServerSide.vue'
import BigButton from '@/components/BigButton.vue'
import TotalBlockS from '@/components/TotalBlockS.vue'

export default {
  name: 'home',
  components: {
    TotalSmall,
    TotalLarge,
    ServerSide,
    BigButton,
    TotalBlockS
  }
}
</script>

<style lang="stylus">
@font-face 
  font-family: 'Roboto'
  src: url('./assets/fonts//Robotomedium.ttf') format('truetype')
  font-weight: 500
  font-style: normal

@font-face 
  font-family: 'Roboto'
  src: url('./assets/fonts/Robotobold.ttf') format('truetype')
  font-weight: 700
  font-style: normal

html
  background-color #2C313D

body
  margin 0

.sidebar
  background-color #343945
  height 100%
  width 300px
  position fixed
  margin 0
  padding 0

h1 
h3 
  color #FFFFFF

h3 
  font-family Roboto
  font-weight 500

h1
  font-family Roboto
  font-weight 700

button 
  border none
  text-align center
  cursor pointer
  outline none
</style>
