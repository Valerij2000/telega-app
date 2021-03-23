<template>
    <div>
        <!-- Modal -->
<div class="modal fade" id="mail" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Email Form</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <FormMail />
      </div>
    </div>
  </div>
</div>
    </div>
</template>


<script>

import FormMail from '@/components/FormMail.vue'



export default {
    components: {
      FormMail
    }
}
</script>