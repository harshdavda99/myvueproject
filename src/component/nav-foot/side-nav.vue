<template>
  <div class="accordion accordion-flush p-1" id="accordionFlushExample">
    <div class="accordion-item">
      <h2 class="accordion-header arrow">
        <button class="accordion-button" type="button">Dashboard</button>
      </h2>
    </div>
    <!-- /**/1 Contacts*/ -->
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-headingOne">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapseOne"
          aria-expanded="false"
          aria-controls="flush-collapseOne"
        >
          Contacts
        </button>
      </h2>
      <div
        id="flush-collapseOne"
        class="accordion-collapse collapse"
        aria-labelledby="flush-headingOne"
        data-bs-parent="#accordionFlushExample"
      >
        <div class="accordion-body">
          <ul class="" >
            <li><a class="dropdown-item" href="#">Add Contact</a></li>
            <li><a class="dropdown-item" href="#">View contact</a></li>
            <li><a class="dropdown-item" href="#">Export Contact</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!-- /** Email*/ -->
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-headingtwo">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapsetwo"
          aria-expanded="false"
          aria-controls="flush-collapsetwo"
        >
       Email
        </button>
      </h2>
      <div
        id="flush-collapsetwo"
        class="accordion-collapse collapse"
        aria-labelledby="flush-headingtwo"
        data-bs-parent="#accordionFlushExample"
      >
      <div class="accordion-body">
          <ul>
            <li><a class="dropdown-item" href="#">Add Email Details </a></li>
            <li><a class="dropdown-item" href="#">View Email</a></li>
            <li><a class="dropdown-item" href="#">Export Email</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!-- /**/ Invoice*/ -->
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-heading3">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapse3"
          aria-expanded="false"
          aria-controls="flush-collapse3"
        >
          Invoice 
        </button>
      </h2>
      <div
        id="flush-collapse3"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading3"
        data-bs-parent="#accordionFlushExample"
      >
      <div class="accordion-body">
          <ul>
            <li><a class="dropdown-item" href="#">Profit </a></li>
            <li><a class="dropdown-item" href="#">Loss  </a></li>
            <li><a class="dropdown-item" href="#">Customer Bill</a></li>
            <li><a class="dropdown-item" href="#">Payable bill</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!-- /**/  Starter Motor*/ -->
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-heading4">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapse4"
          aria-expanded="false"
          aria-controls="flush-collapse4"
        >
          Starter Motor
        </button>
      </h2>
      <div
        id="flush-collapse4"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading4"
        data-bs-parent="#accordionFlushExample"
      >
      <div class="accordion-body">
          <ul class="" >
            <li><a class="dropdown-item" href="#">Bendix</a></li>
            <li><a class="dropdown-item" href="#">Armature</a></li>
            <li><a class="dropdown-item" href="#">Carbon</a></li>
            <li><a class="dropdown-item" href="#">Body</a></li>
            <li><a class="dropdown-item" href="#">Swtich</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!-- /**/ */ -->
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-heading6">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapse6"
          aria-expanded="false"
          aria-controls="flush-collapse6"
        >
        Alternator
        </button>
      </h2>
      <div
        id="flush-collapse6"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading6"
        data-bs-parent="#accordionFlushExample"
      >
        <div class="accordion-body">
          Placeholder content for this accordion, which is intended to
          demonstrate the <code>.accordion-flush</code> class. This is the first
          item's accordion body.
        </div>
      </div>
    </div>
    <!-- /**/ Accessories*/ -->
    <div class="accordion-item">
      <h2 class="accordion-header" id="flush-heading5">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapse5"
          aria-expanded="false"
          aria-controls="flush-collapse5"
        >
       Accessories
        </button>
      </h2>
      <div
        id="flush-collapse5"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading5"
        data-bs-parent="#accordionFlushExample"
      >
      <div class="accordion-body">
          <ul>
            <li><a class="dropdown-item" href="#">Music system</a></li>
            <li><a class="dropdown-item" href="#">Lamps</a></li>
            <li><a class="dropdown-item" href="#">Fog Lights</a></li>
            <li><a class="dropdown-item" href="#">Horn</a></li>
            <li><a class="dropdown-item" href="#">Wiring Kit</a></li>
          </ul>
        </div>
      </div>
    </div>

  </div>
</template>

<style>
.arrow .accordion-button:not(.collapsed)::after {
  /* background-image:{216242_home_icon.svg}; */
  background-image: url(../../assets/216242_home_icon.svg);
  transform: rotateZ(360deg);
}
</style>
