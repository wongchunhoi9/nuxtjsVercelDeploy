<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        nuxtjs
      </h1>
      <h2 class="subtitle">
        My astonishing Nuxt.js project
      </h2>
      <model-viewer src="https://poly.googleusercontent.com/downloads/c/fp/1585475837775703/7seQO9AGzkB/2IzMN2H3kfF/model.gltf" ios-src="https://poly.googleusercontent.com/downloads/c/fp/1585475837775703/7seQO9AGzkB/91Vm5NgSfKv/model.usdz" alt="Orange B by Wong Chun Hoi" background-color="##ffffff" camera-controls auto-rotate ar ar-scale="auto" quick-look-browsers="chrome safari" unstable-webxr> </model-viewer>
      <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
  <script nomodule src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>     
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>

  
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
