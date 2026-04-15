<template>
  <div>
    <!--made on 5/1/25-->
    <br />
    <!--updated content on 5/7/25-->
    <h1>Frequently Asked Questions</h1>
    <br />
    <div class="accordion accordion-flush" id="accordionFlushExample">
      <div class="accordion-item ">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseOne"
            aria-expanded="false"
            aria-controls="flush-collapseOne"
          >
            Do you really only use MS paint to draw these comics?
          </button>
        </h2>
        <div
          id="flush-collapseOne"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            Short answer is yes. Slightly longer answer is yesss. (I do also use a mouse and a keyboard).
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseTwo"
            aria-expanded="false"
            aria-controls="flush-collapseTwo"
          >
            How do you come up with these scenarios?
          </button>
        </h2>
        <div
          id="flush-collapseTwo"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            These are all interactions I have had. You can tell that the crazy haired gal in the drawings (that's me!!) is always in the one dealing with the surroundings.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseThree"
            aria-expanded="false"
            aria-controls="flush-collapseThree"
          >
            What inspired you to start drawing comics?
          </button>
        </h2>
        <div
          id="flush-collapseThree"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            I have been drawing comics since elementary school. What inspired me to start drawing my own life was after someone told me, "Your life sounds like a sitcom, somethings always happening with you."
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Comp4',
  props: {
    msg: String,
  },
};
</script>
