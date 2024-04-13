<template>
  <div>
        <Banner title="Contact"></Banner>
  </div>
  <section class="my-md-5 my-3 pb-md-2 pb-1">
    <h2 role="heading" class="text-secondary fw-semibold text-center">Send Us an Email</h2>
    <p class="fs-4 pt-md-3 pt-1 text-center">
      Use the form below to send us an email and book your visit.
      <br>
      Feel free to also write a message with questions and suggestions.
    </p>
    <div class="container bg-white shadow col-12 mt-md-5 mt-4">
      <form class="row fs-5 g-3 p-md-3 pb-3">
        <div class="col-md-6">
          <label for="inputName" class="form-label">Full Name*</label>
          <input type="text" class="form-control" id="inputName" placeholder="">
        </div>
        <div class="col-md-6">
          <label for="inputEmail" class="form-label">Email*</label>
          <input type="email" class="form-control" id="inputEmail" placeholder="">
        </div>
        <div class="col-12">
          <label for="inputSubject" class="form-label">Subject</label>
          <input type="text" class="form-control" id="inputSubject" placeholder="">
        </div>
        <div class="col-12">
          <label for="inputMessage" class="form-label">Message*</label>
          <textarea type="text" class="form-control" id="inputMessage" placeholder=""></textarea>
        </div>
        <div class="col text-center">
          <button type="submit" class="btn btn-primary" aria-label="Send email">Send ></button>
        </div>
      </form>
    </div>
  </section>
</template>

<script setup>

</script>

<style scoped>

</style>