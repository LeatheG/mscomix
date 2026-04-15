<template>
  <div>
    <!--made on 5/1/25-->
    <h1>Subscribe to Us!</h1>
    <!--updated content on 5/7/25-->
    <br />
    <div class="form-container">
      <form style="width: 22rem">
        <div data-mdb-input-init class="form-outline mb-4">
          <input type="text" id="form5Example1" class="form-control" />
          <label class="form-label" for="form5Example1">Name</label>
        </div>

        <div data-mdb-input-init class="form-outline mb-4">
          <input type="email" id="form5Example2" class="form-control" />
          <label class="form-label" for="form5Example2">Email address</label>
        </div>

        <div class="form-check d-flex justify-content-center mb-4">
          <input
            class="form-check-input me-2"
            type="checkbox"
            value=""
            id="form5Example3"
            checked
          />
          <label class="form-check-label" for="form5Example3">
            I have read and agree to the terms
          </label>
        </div>

        <button
          data-mdb-ripple-init
          type="button"
          class="btn btn-dark btn-block mb-4"
        >
          Subscribe
        </button>
      </form>
    </div>
  </div>
</template>

<style scoped>
.form-container {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>

<script>
export default { name: 'Contact' };
</script>
