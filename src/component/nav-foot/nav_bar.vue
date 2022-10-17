<template>
<div>
<header>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <div>

      <button
      class="navbar-toggler m-2"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#sidebarMenu"
      aria-controls="sidebarMenu"
      aria-expanded="false"
      aria-label="Toggle navigation"
      >
      <span class="navbar-toggler-icon"></span>
    </button>
    <img class="navbar-brand Logo" src='../../assets/DavdaAuto1.png' href=""/>
  </div>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="https://www.youtube.com/embed/_5Tw_oI9kKg">Tutorial</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="https://www.iconfinder.com/search?q=home">Svg Icon</a>
        </li>
       </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-light" type="submit">Search</button>
        <button class="btn btn-outline-light btn-lg ms-2" type="submit" ><router-link style="text-decoration: none; color: inherit;" to="/login" >Login</router-link></button>
      </form>
    </div>
  </div>
</nav>
  <!-- Sidebar -->
  <nav
       id="sidebarMenu"
       class=" d-lg-block sidebar collapse bg-white"
       >
    <div class="position-sticky">
      <!-- <div class="list-group list-group-flush mx-3 mt-4">
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple active"
           aria-current="true"
           >
          <i class="fas fa-tachometer-alt fa-fw me-3"></i><span>Main dashboard</span>
        </a>
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple active"
           >
          <i class="fas fa-chart-area fa-fw me-3"></i
            ><span>Webiste traffic</span>
        </a>
      </div> -->
      <div class="accordion accordion-flush p-1 scrollspy" id="accordionFlushExample">
    <div class="accordion-item">
      <h2 class="accordion-header arrow">
        <button class="accordion-button" type="button">
          <img src="../../assets/216242_home_icon.svg" id="listicon" />
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
          <img src="../../assets/contacts-book.png" id="listicon" />
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
          <ul class="">
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
          <img src="../../assets/email.png" id="listicon" />
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
          <img src="../../assets/bill.png" id="listicon" />
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
            <li><a class="dropdown-item" href="#">Loss </a></li>
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
          <img src="../../assets/starter.png" id="listicon" />
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
          <ul class="">
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
          <img src="../../assets/Altenator.png" id="listicon" />
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
          <ul class="">
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
          <img src="../../assets/Accessories.png" id="listicon" />
          <span> Accessories</span>
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
          <img src="../../assets/ball-bearing .png" id="listicon" />
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
          <img src="../../assets/bushing.png" id="listicon" />
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
    </div>
  </nav>
  <!-- Sidebar -->

  <!-- Navbar -->
  
  
  <!-- Navbar -->
</header>
<!--Main Navigation-->

<!--Main layout-->
<main style="margin-top: 58px">
  <div class="container pt-4">
dsfsdsfdsdsdsfdsfdsf
  </div>
</main>
</div>
<!--Main layout-->
</template>

<style>
.Logo{
  width: 12vw;
}
body {
  background-color: #fbfbfb;
}
@media (min-width: 991.98px) {
  main {
    padding-left: 240px;
  }
}

/* Sidebar */
.sidebar {
  position: fixed;
  top: 66px;
  bottom: 0;
  left: 0;
  padding:0; 
  box-shadow: 0 2px 5px 0 rgba(206, 39, 39, 0.05), 0 2px 10px 0 rgba(202, 191, 191, 0.05);
  width: 240px;
  z-index: 600;
}

@media (max-width: 991.98px) {
  .sidebar {
    width: 100%;
    position: absolute;
    top: 55px;
    bottom: 0;
    padding: 0
  }
}
.sidebar .active {
  border-radius: 5px;
  box-shadow: 0 2px 5px 0 rgb(0 0 0 / 16%), 0 2px 10px 0 rgb(0 0 0 / 12%);
}

.sidebar-sticky {
  position: relative;
  top: 0;
  height: calc(100vh - 48px);
  padding-top: 0.5rem;
  overflow-x: hidden;
  overflow-y: auto; /* Scrollable contents if viewport is shorter than content. */
}
.arrow .accordion-button:not(.collapsed)::after {
  background-image: none;
  /* background-image: url(../../assets/216242_home_icon.svg); */
  transform: rotateZ(360deg);
}
#listicon {
  margin: 0px 32px 0px 0px;
}
.scrollspy{
  height: calc(100vh - 75px);
    overflow-y: auto;
}
</style>