<template>
  <div class="accordion accordion-flush p-1" id="accordionFlushExample">
    <div class="accordion-item">
      <h2 class="accordion-header arrow">
        <button class="accordion-button" type="button">
          <img src='../../assets/216242_home_icon.svg' id="listicon"/>
        <span>Dashboard</span>
        </button>
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
        <img src='../../assets/contacts-book.png' id="listicon"/>
        <span>Contacts</span>
          
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
        <img src='../../assets/email.png' id="listicon"/>
        <span>Email</span>
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
          <img src='../../assets/bill.png' id="listicon"/>
        <span>Invoice </span>
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
          
            <img src='../../assets/starter.png' id="listicon"/>
        <span>Starter Motor </span>
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
       
        
            <img src='../../assets/Altenator.png' id="listicon"/>
        <span> Alternator</span>
        </button>
      </h2>
      <div
        id="flush-collapse6"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading6"
        data-bs-parent="#accordionFlushExample"
      >
        <div class="accordion-body">
          <ul class="" >
            <li><a class="dropdown-item" href="#">Rotor</a></li>
            <li><a class="dropdown-item" href="#">Stater</a></li>
            <li><a class="dropdown-item" href="#">Diode Plate </a></li>
            <li><a class="dropdown-item" href="#">Regulator</a></li>
            <li><a class="dropdown-item" href="#">Pully</a></li>
            <li><a class="dropdown-item" href="#">Body</a></li>
            <li><a class="dropdown-item" href="#">Stater Ring</a></li>
          </ul>
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
        <img src='../../assets/Accessories.png' id="listicon"/>
        <span>  Accessories</span>
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
    <!-- //**Bearing */ -->
     <div class="accordion-item">
      <h2 class="accordion-header" id="flush-heading7">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapse7"
          aria-expanded="false"
          aria-controls="flush-collapse7"
        >
               <img src='../../assets/ball-bearing .png' id="listicon"/>
        <span>Bearing</span>
        </button>
      </h2>
      <div
        id="flush-collapse7"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading7"
        data-bs-parent="#accordionFlushExample"
      >
      <div class="accordion-body">
          <ul>
            <li><a class="dropdown-item" href="#">Roller Bearing</a></li>
            <li><a class="dropdown-item" href="#">Boll Bearing</a></li>
          </ul>
        </div>
      </div>
    </div>
<!-- //**Boushing */ -->
     <div class="accordion-item">
      <h2 class="accordion-header" id="flush-heading8">
        <button
          class="accordion-button collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#flush-collapse8"
          aria-expanded="false"
          aria-controls="flush-collapse8"
        >
        <img src='../../assets/bushing.png' id="listicon"/>
        <span>Bushing</span>
        </button>
      </h2>
      <div
        id="flush-collapse8"
        class="accordion-collapse collapse"
        aria-labelledby="flush-heading8"
        data-bs-parent="#accordionFlushExample"
      >
      <div class="accordion-body">
          <ul>
            <li><a class="dropdown-item" href="#">Cylinder Bushing</a></li>
            <li><a class="dropdown-item" href="#">Coller Bushing</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.arrow .accordion-button:not(.collapsed)::after {
  background-image: none;
  /* background-image: url(../../assets/216242_home_icon.svg); */
  transform: rotateZ(360deg);
}
#listicon{
  margin: 0px 25px 0px 0px;
}
</style>
