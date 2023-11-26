<template>
   <div>
    <p> LAMBA DURUMU :   
    <button @click="openLamp"> Lambayı aç/Kapa {{sta }}</button></p>
   </div>
 

</template>

<script>
import func from "../vue-temp/vue-editor-bridge"
  

export default defineComponent({
    data() {
        
        return {
            status: "kapalı"
        }
    },
    methods: {

        openLamp(){
            this.status="acik.."

        }

    }


})
</script>


<style >

</style>