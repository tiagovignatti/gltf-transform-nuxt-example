<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        gltf-transform-nuxt-example
      </h1>
      <div class="links">
        <a
          @click="readFile"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Read glb draco'ed file
        </a>
        <a
          @click="doSomeStuff"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Do some stuff
        </a>
      </div>
    </div>
  </div>
</template>

<script type="text/javascript" src="./script.js" />

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
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
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
