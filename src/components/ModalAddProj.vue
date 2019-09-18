<template lang="pug">
section.modal_add
  .modal__content
    h2.visually-hidden Add Project
    h3 Name
    input(type="text")
    h3 Domain
    input(type="text")
    h3 Visibility
    .visibility
      input(type="radio" value="online" name="visibility") online
      input(type="radio" value="offline" name="visibility") offline
    h3 SSL
    input(type="checkbox")
    //BigButton     ok
    //BigButton     cancel
    button.modal__button.button-close(type="button")
</template>

<script>
export default {}
</script>

<style lang="stylus"></style>
