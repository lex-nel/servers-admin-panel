<template lang="pug">
section.modal_stop
  .modal__content_stop
    h2.visually-hidden Stop Server
    h3 Stop server?
    h3 Please, enter the name of the server to stop it
    input(type="text")
    br
    //BigButton     ok
    //BigButton     cancel
    button.modal__button.button-close(type="button")
</template>

<script>
export default {}
</script>

<style lang="stylus"></style>
