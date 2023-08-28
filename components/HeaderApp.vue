<template>
  <nav class="navbar p-2 fixed-top">
    <div class="container-fluid">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon" />
      </button>

      <a class="navbar-brand text-white" href="#">Food Recipe</a>

      <div class="navbar-icon">
        <img src="~/assets/icon/user.svg" alt="Icon User" width="15px">
        <img class="ms-2" src="~/assets/icon/notif.svg" alt="Icon Notify" width="15px">
      </div>

      <div id="navbarNav" class="collapse navbar-collapse text-center">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active text-white" aria-current="page" href="#">My Food</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">My List</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Recipes</a>
          </li>
        </ul>
      </div>
      
    </div>
  </nav>
</template>
