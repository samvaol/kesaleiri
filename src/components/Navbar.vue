<template>
    <nav class="navbar">
      <ul class="navbar-nav left">
        <li class="nav-item">
          <a href="#">Etusivu</a>
        </li>
        <li class="nav-item">
          <a href="#">Teema</a>
        </li>
      </ul>
      <ul class="navbar-nav right">
        <li class="nav-item">
          <a href="#"></a>
        </li>
        <li class="nav-item">
          <a href="#">Yhteystiedot</a>
        </li>
        <li class="nav-item">
          <a href="#">Yhteystiedot</a>
        </li>
      </ul>
    </nav>
  </template>
  
  <style scoped>
  .navbar {
    display: flex;
    align-items: center;
  }
  
  .navbar-nav {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  .nav-item {
    margin-left: 16px;
  }
  
  .nav-item:first-child {
    margin-left: 0;
  }
  </style>
  
  <link rel="stylesheet" href="./assets/main.css">