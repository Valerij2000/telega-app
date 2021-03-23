<template>
  <div>
    <form action="telegram.php" method="post">
      <div class="mb-3">
      <label  
      class="form-label"
        >Email address</label
      >
      <input
        name="mail"
        type="email"
        class="form-control"
        placeholder="name@example.com"
      />
    </div>
    <div class="mb-3">
      <label class="form-label"
        >Example textarea</label
      >
      <textarea
        name="text"
        class="form-control"
        rows="3"
      ></textarea>
    </div>

    <div class="modal-footer">
      <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">
        Close
      </button>
      <button type="submit" class="btn btn-primary">Send Telegram</button>
    </div>
    </form>
  </div>
</template>


<script>

import axios from 'axios'

export default {
    data() {
        return {
           
        }
    },


    methods: {

    },


    


}
</script>