<template lang="pug">
section.modal_add
  .modal__content
    h2.visually-hidden Add Server
    h3 Name
    input(type="text")
    h3 OS
    .os
      label.ubuntu
        input(type="radio" value="ubuntu" name="os")
        span
      label.debian
        input(type="radio" value="debian" name="os")
        span
      label.centos
        input(type="radio" value="centos" name="os")
        span
    //BigButton     ok
    //BigButton     cancel
    button.modal__button.button-close(type="button")
</template>

<script>
export default {}
</script>

<style lang="stylus"></style>
