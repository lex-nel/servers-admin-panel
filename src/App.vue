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
    TotalBlockS,
  },
}
</script>

<style lang="stylus">
@font-face
  font-weight: 500
  font-style: normal
  font-family: 'Roboto'
  src: url('./assets/fonts//Robotomedium.ttf') format('truetype')

@font-face
  font-weight: 700
  font-style: normal
  font-family: 'Roboto'
  src: url('./assets/fonts/Robotobold.ttf') format('truetype')

html
  background-color: #2C313D

body
  margin: 0

.sidebar
  position: fixed
  margin: 0
  padding: 0
  width: 300px
  height: 100%
  background-color: #343945

h1,
h3
  color: #FFFFFF

h3
  font-weight: 500
  font-family: Roboto

h1
  font-weight: 700
  font-family: Roboto

button
  outline: none
  border: none
  text-align: center
  cursor: pointer
</style>
