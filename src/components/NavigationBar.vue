<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">
        <i class="bi bi-house-door-fill"></i>
        My App
      </a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav-collapse" aria-controls="nav-collapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="nav-collapse">
        <ul class="navbar-nav me-auto">
          <!-- Left Icon -->
          <li class="nav-item">
            <a class="nav-link" href="#">
              <i class="bi bi-envelope-fill"></i>
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
            </ul>
          </li>
        </ul>

        <ul class="navbar-nav">
          <!-- Right Icon -->
          <li class="nav-item">
            <a class="nav-link" href="#">
              <i class="bi bi-bell-fill"></i>
            </a>
          </li>

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              User
            </a>
            <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Profile</a></li>
              <li><a class="dropdown-item" href="#">Logout</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  </template>
  <script>
  export default {
    name: 'NavigationBar'
  };
  </script>
  
  <style scoped>
  /* Add any custom CSS styles here */
  </style>
  