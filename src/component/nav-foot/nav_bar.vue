<template>
<div>
<header>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <!-- <img class="navbar-brand Logo" src='../../assets/DavdaAuto1.png' href=""/> -->
    <!-- <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button> -->
    <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#sidebarMenu"
              aria-controls="sidebarMenu"
              aria-expanded="false"
              aria-label="Toggle navigation"
              >
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
      <div class="list-group list-group-flush mx-3 mt-4">
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           aria-current="true"
           >
          <i class="fas fa-tachometer-alt fa-fw me-3"></i
            ><span>Main dashboard</span>
        </a>
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple active"
           >
          <i class="fas fa-chart-area fa-fw me-3"></i
            ><span>Webiste traffic</span>
        </a>
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-lock fa-fw me-3"></i><span>Password</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-chart-line fa-fw me-3"></i
          ><span>Analytics</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           >
          <i class="fas fa-chart-pie fa-fw me-3"></i><span>SEO</span>
        </a>
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-chart-bar fa-fw me-3"></i><span>Orders</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-globe fa-fw me-3"></i
          ><span>International</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-building fa-fw me-3"></i
          ><span>Partners</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-calendar fa-fw me-3"></i
          ><span>Calendar</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-users fa-fw me-3"></i><span>Users</span></a
          >
        <a
           href="#"
           class="list-group-item list-group-item-action py-2 ripple"
           ><i class="fas fa-money-bill fa-fw me-3"></i><span>Sales</span></a
          >
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
    top: 56px;
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
</style>