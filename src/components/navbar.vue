<template>
    <div>
      <header class="header">
        <h1 class="main-heading">My Website</h1>
        <nav class="navbar">
          <ul>
            <li>
              <router-link to="/" tag="h1">Home</router-link>
            </li>
            <li>
              <router-link to="/about" tag="h1">About</router-link>
            </li>
            <li>
              <router-link to="/contact" tag="h1">Contact</router-link>
            </li>
          </ul>
        </nav>
      </header>
      <router-view></router-view>
    </div>
  </template>
  


  <script>
  export default {
    name: 'Header'
  }
  </script>

<link rel="stylesheet" href="./assets/main.css">

