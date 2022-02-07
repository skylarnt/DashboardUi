<template>
    <div>
        <div id="destop_view">

            <desktop  />
        </div>
       <div id="mobile_view">

        <mobile  />
       </div>
        
    </div>
</template>
<script>
import Desktop from '../components/Desktop.vue'
import Mobile from '../components/Mobile.vue'
export default {
  components: { Desktop },
    

    Mobile}
</script>
<style scoped>
    #mobile_view {
        display: none;
    }
    @media screen and (max-width: 900px) {
        #destop_view {
            display: none;
        }
        #mobile_view {
            display: block;
        }
    }
</style>