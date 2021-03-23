<template>
    <div>
       <section class="home-section">
           <div class="container">
               <div class="row">
                   <div class="col-xl-12">
                       
<ButtonModal />

        <Modal />

                   </div>
               </div>
           </div>
       </section>
    </div>
</template>


<script>

import Modal from '@/components/Modal.vue'
import ButtonModal from '@/components/ButtonModal.vue'

export default {
   components: {
       Modal, ButtonModal
   },
}
</script>



<style lang="scss" scoped>

    .home-section {
        background-color:rgba(202, 177, 63, 0.74);
        padding-top: 30px;
        min-height: 100vh;
    }


</style>