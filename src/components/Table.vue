<template lang="pug">
    table
        tr.desc
            th #
            th IP
            th NAME
            th CPU%
            th RAM
            th DISC USED %
            th STATUS
            th ACIONS
            th 
        tr.data
            th 1
            th 192.168.0.1
            th server 1
            th 56
            th 512/1024
            th 40
            th online
            th 
                //SmallButton   stop
            th 
                //SmallButton   restart
        tr.data
            th 1
            th 192.168.0.1
            th server 1
            th 56
            th 512/1024
            th 40
            th online
            th 
                //SmallButton   stop
            th 
                //SmallButton   restart
</template>

<script>
export default {
    
}
</script>

<style lang="stylus">
.desc
    background-color #43A09B

.data
    background-color #3D3F7C
</style>