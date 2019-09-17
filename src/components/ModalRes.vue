<template lang="pug">
    section.modal_restart
            .modal__conten_restart
                h2.visually-hidden Restart Server
                h3 Restart server?
                h3 Please, enter the name of the server to delete it
                input(type="text")
                br
                //BigButton     ok
                //BigButton     cancel
                button.modal__button.button-close(type="button")
</template>

<script>
export default {
    
}
</script>

<style lang="stylus">

</style>