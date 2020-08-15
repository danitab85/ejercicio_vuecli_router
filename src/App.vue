<template>
  <div id="app">
    <div id="nav" class="container">
      <ul class="nav justify-content-center">
        <li class="nav-item">
          <router-link class="nav-link active" to="/">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/blog/1">Blog</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" :to="{name:'Contact'}">Contacto</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/servicios">Servicios</router-link>
        </li>
      </ul>
      <router-view />
    </div>
  </div>
</template>
